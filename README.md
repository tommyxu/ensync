# ensync
Put a local file into a note in specified Evernote notebook or vice versa.

## Requirement

Python 2.6 or 2.7 (official evernote-api only supports Python 2)


## Dependencies

* easysettings
* evernote

You can install via pip:

```bash
pip install easysettings evernote
```

## Usage

Make alias or put into PATH environment:

```bash
alias ensync="~/projects/remote.ensync/ensync"
```

## Sample

* put this file into configured notebook.

```bash
  ensync put README.txt
```

* list all files

```bash
  ensync list
```


