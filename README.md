# Version-Controlled Resume

Just some simple scripts for generating a pdf resume from a latex file.

## Quickstart

You need [pdflatex](//linux.die.net/man/1/pdflatex) installed and on your path.

1. Copy the `.config` file to `~/.resume` and modify.
2. Symlink the `bin/resume` binary to somewhere on your path.

## Command Usage

```
Usage: resume [command]

  help     Shows this help menu
  edit     Opens the resume file in editor of choice. 
  build    Runs pdflatex using your configuration variables.
  view     Runs xdg-open on the built PDF file.
  config   Opens the configuration file in editor of choice.
```

## Configuration

```bash
# .config

resume_dir			The absolute path of your resume project.
resume_source		The filename of your input file.
resume_template		The filename of your PDF output file.
resume_editor		The editor you want to use.
resume_viewer		The PDF viewer you want to use.
```
