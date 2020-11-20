# pyxterm.js


## Installation

Clone this repository, enter the `pyxtermjs` directory, then run:

```
python3 -m venv venv  # must be python3.6+
venv/bin/pip install -r requirements.txt
venv/bin/python -m pyxtermjs
```

## Documentation
```
>> pyxtermjs --help
usage: pyxtermjs [-h] [-p PORT] [--debug] [--version] [--command COMMAND]
                 [--cmd-args CMD_ARGS]

A fully functional terminal in your browser.
https://github.com/cs01/pyxterm.js

optional arguments:
  -h, --help            show this help message and exit
  -p PORT, --port PORT  port to run server on (default: 5000)
  --debug               debug the server (default: False)
  --version             print version and exit (default: False)
  --command COMMAND     Command to run in the terminal (default: bash)
  --cmd-args CMD_ARGS   arguments to pass to command (i.e. --cmd-args='arg1
                        arg2 --flag') (default: )

```
