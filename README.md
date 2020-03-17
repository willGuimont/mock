# mock
you caN'T coNVeY sArCASM tROugH WRitTeN tExT

# Installation

1. `mkdir ~/bin`
2. Copy mock into `~/bin`
3. `chmod +x ~/bin/mock`
4. Add `PATH=$PATH:$HOME/bin` at the end of your `~/.bashrc`
5. Use with `mock "You can't convey sarcasm trough written text"`

# Parameters
`mock --help`
>usage: mock [-h] [-x] [-p PROBABILITY] [-q] message
>
>positional arguments:
>  message               message to ironify
>
>optional arguments:
>  -h, --help            show this help message and exit
>  -x, --copy            copy ironyc message to clipboard
>  -p PROBABILITY, --probability PROBABILITY
>                        probability of upper case letters
>  -q, --quiet           does not print to terminal
