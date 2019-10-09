
# mknote

A command line interface used to create course work and note files. Optionally creates script files like R scripts / Python scripts and opens them in your editor of choice.

## Installation

```
$ git clone https://github.com/mkomod/mknote
```

## Usage

```
Usage: mknote [-pr] [-t template_dir] [-n template_name ] project_name 

Positional Arguments:
  project_name 		The name of the project

Optional Arguments:
  -p			Generates a python script
  -r			Generates a R script
  -t template_dir	Copies template from path into project folder
  -n template_name	Identifies the tex file used as the tamplate
```

**Note** there is a default template variable set in the source, the path should be changed.


