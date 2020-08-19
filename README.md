# LaTeX learning

This repository is a compilation of instances where I write a document in LaTeX as a means of sharpening my grammatical and technical skills.

## Compiling a .tex file

This section assumes you are running MacOS. Please see documentation for your OS otherwise.

### Prerequisites

Before starting:

  1. Ensure you have installed a tool capable of compiling LaTeX, such as [MacTeX](https://tug.org/mactex/).
  1. Know how to type a command in your terminal.

### Generating a PDF

Generating a PDF of a `.tex` file is stupid easy.

With `pdflatex`:

  1. In your terminal, `pdflatex /path/to/.tex`.

With `latexmk`, you can run the following command without an argument to genrate a PDF for each .tex in the current directory, or you can specify a .tex file to run for:

  1. In your terminal, `latexmk -pdf` or `latexmk -pdf /path/to/.tex`.
  1. (Optional) - In the directory where the `.tex` was compiled, the tool will create some temp files that you can optionally delete. To clean them up with the tool, `latexmk -c`.

### Index

This section is a list and description of each document I have written in LaTeX.

  - [ww2_artillery](essays/ww2_artillery.tex) - An essay I had to write as busy work per my platoon sergeant. The topic of this one was the 'Role and Implementation of Artillery in the European Theatre of WWII'.
