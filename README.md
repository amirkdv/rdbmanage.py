```
usage: rdbmanage [-h] [-c CONF_FILE] [-j JOB] [-m MAX] [-f]

optional arguments:
  -h, --help    show this help message and exit
  -c CONF_FILE  string: path to rdbmanage configuration file
  -j JOB        string: job name to be updated (backup and clear)
  -m MAX        integer: maximum number of increments to fetch (-1 implies no
                maximum), ignored if -j is provided
  -f            flag: force fetch a backup, only considered with -j
```
