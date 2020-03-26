# mock
you caN'T coNVeY sArCASM tROugH WRitTeN tExT

Works on Linux, Windows and MacOS.

# Installation

1. Install `xclip`
2. `mkdir ~/bin`
3. Copy mock into `~/bin`
4. `chmod +x ~/bin/mock`
5. Add `PATH=$PATH:$HOME/bin` at the end of your `~/.bashrc`
6. Use with `mock "You can't convey sarcasm trough written text"`

# Usage
`mock "You can't convey sarcasm trough written text" -p 0.75 -x -q`

`echo "You can't convey sarcasm trough written text" | mock`

## Interactive mode
`mock` then type sentences to mock.

# Parameters
`mock --help`

```shell
usage: mock [-h] [-x] [-p PROBABILITY] [-q] [message]

The best tool to convey sarcasm

positional arguments:
  message               message to ironify, alternatively you can pipe text into mock

optional arguments:
  -h, --help            show this help message and exit
  -x, --copy            copy ironyc message to clipboard, only works with last piped line
  -p PROBABILITY, --probability PROBABILITY
                        probability [0, 1] of upper case letters
  -q, --quiet           does not print to terminal
```

