# Quarto Homework Template

This repository is a reusable starter for Introduction to Data Science
homework. Copy or fork it, rename the project, and put all answers in
`homework.qmd`.

## Start

1. Copy or fork this template repository.
2. Rename the repository and update the title and author in `homework.qmd`.
3. Replace the problem placeholders with the assigned problems.
4. Write complete explanations around any code, tables, or figures.

Keep source files, data descriptions, and environment specifications under
version control. Do not commit virtual environments, generated output, caches,
credentials, or private data.

The course's semester-specific notes provide the assignment instructions,
rendering and PDF requirements, and submission procedure.

## Render

Assuming `quarto` has been installed properly;

```
quarto render homework.qmd
```

If successful, the rendered html output file `homework.html` will show,
which can then be reviewed. If edits or revision is needed, edit the
`homework.qmd` file with your favorite editor (e.g., Codium or Emacs),
save, and rerender. Iterate until the html output is satisfactory.

## Print to pdf

The html output could be printed to a pdf file for ease of grading.
