# AICS Annual Report FY2015

## Team/Unit Instructions

If you have any questions or need any help on the following instructions, please contact Naoya Maruyama.

In summary, here are the basic steps:

1. Download or clone this repository.
2. Make sure all the prerequisites are available on your environment.
3. Try typesetting to verify the software setup.
4. Write your report in main.tex.
5. Submit the final PDF report.

### Prerequisites

The following commands are used to typeset the report.

- pdflatex
- biber
- latexmk

Tested on Mac with MacTex 2015.

### Typesetting

On Mac/Linux, run the typeset.sh shell script. File main.pdf should be created.

### Per-group files
Each group has its own sub directory. Edit and create files only under your directory and avoid editing files not in your directory.

### Template
Use main.tex in your directory as a starting template for your group's report. Do not change the existing top-level section titles or add/remove top-level sections. Subsections may be used.

See annual-report-template.pdf for the typeset result.

### Cross referencing
To avoid naming conflicts when using cross referecing, use the ``localref`` and ``locallabel`` commands rather than the standard ``ref`` and ``label`` commands. They will automatically prefix the given label with the chapter number. See the main.tex template file.

### Publications

The publication list is created from the main.bib file in your directory. Each entry requires a ``keywords`` field to indicate the section where it should be displayed. For example, a journal article must have ``journal`` as the value of its ``keywords`` field. See main.bib for more details.

### Submission

Before submitting your report, please make sure that typesetting is done successfully with no errors.

Once ready, please upload all of the files to the RIKEN's briefcase at https://briefcase.riken.jp/ and notify the download URL to Naoya Maruyama.

Alternatively, you can send a pull request to @naoyam, which is actually preferred. Make sure that all your files are added to your repository.
