## Usage

`@convert2docs.md`

## Context

- Manuscript: `docs/10-manuscript.md`
- Manuscript supplement: `docs/10-manuscript-supplement.md`
- Cover letter: `docs/10-cover-letter.md`
- Results: `data/output/`

## Process

- Write a python script to use `md2docx-python` to convert target markdown file to docx file.
- Use `uv run` to run the python script.
- Insert the corresponding figures and tables from Results directory into the appropriate places in the docx file according to the content.
- Operations on docx files can be performed using the `docx` library.
- Check whether the content of the docx file is correct.
- Double check whether the inserted figures and tables are correct with the context content and reference relationships.