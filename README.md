# Quarto Homework Template

This repository provides the starter files for Introduction to Data Science
homework. Put all of your answers in `homework.qmd`.

## Start

### If your assignment uses Classroom50.org

Classroom50.org automatically adds these files to your homework repository.
Clone that repository to your computer; do not copy, fork, or rename it.

### If you are using this template without Classroom50.org

Copy or fork this template repository, rename the resulting project, and clone
it to your computer.

### Complete your homework

1. In your local clone, update the title and author in `homework.qmd` as
   directed by your instructor.
2. Complete the assigned problems in `homework.qmd`, writing explanations
   around any code, tables, or figures. If an assignment uses supplied data,
   download it from the source identified by your instructor into the local
   relative path expected by your code. For the Chapter 5 311 exercise, use
   `data/311_nypd_lbdwk_2026.csv.zip`. Do not add that archive or generated
   data products (such as `data/illegal_parking.feather`) to Git. The grader
   will place the same source data at that path before rendering your
   submission; your code should assume it is present and create derived files
   as part of rendering.
3. Save your progress in multiple meaningful Git commits as you work.
4. Render the homework and review the result. Continue editing, committing,
   and reviewing until you are satisfied.
5. Push all of your commits to your homework repository.

Keep source files, data descriptions, and environment specifications under
version control. Do not commit local data files, virtual environments,
generated output, caches, credentials, or private data. The `.gitignore` file
excludes the Chapter 5 source archive and derived Feather file from Git
tracking.

The course's semester-specific notes provide the assignment instructions,
environment requirements, and submission procedure. Unless an assignment
explicitly requests a PDF, submit the `.qmd` source; the grader renders it.

## Render

Assuming `quarto` has been installed properly;

```
quarto render homework.qmd
```

If successful, the rendered html output file `homework.html` will show,
which can then be reviewed. If edits or revision is needed, edit the
`homework.qmd` file with your favorite editor (e.g., Codium or Emacs),
save, and rerender. Iterate until the html output is satisfactory.
