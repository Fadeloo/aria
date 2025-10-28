## 使用方式

`@convert2docs.md`

## 上下文

- 论文：`docs/10-manuscript.md`
- 论文补充材料：`docs/10-manuscript-supplement.md`
- 投稿附信：`docs/10-cover-letter.md`
- 结果：`data/output/`

## 流程

- 编写一个python脚本，使用`md2docx-python`将目标markdown文件转换为docx文件。
- 使用`uv run`运行python脚本。
- 将结果目录中的对应图表和表格插入到docx文件的相应位置，根据内容进行操作。
- 使用`docx`库对docx文件进行操作。
- 检查docx文件的内容是否正确。
- 再次检查插入的图表和表格是否正确，与上下文内容和参考关系一致。