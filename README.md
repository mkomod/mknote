
# mknote

A command line interface used to create course work and note files.

## Installation

```
$ git clone https://github.com/mkomod/mknote
```

## Usage

```
usage: mknote [-h] [-t T] project_name

positional arguments:
  project_name  The project name.

optional arguments:
  -h, --help    show this help message and exit
  -t T          Template to use (default: note)
```

**Note** Default Templates directory set to `$HOME/Templates`. The directory should be of the form

```
Templates/
    - note/
    - pres/
    - templates
```

The `templates` file contains a description of the templates in the directory i.e

```
# templates

note	Note taking
pres	Presentations
```

