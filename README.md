```
usage: rdbmanage [-h] [-c CONF_FILE] [-j JOB] [-m MAX_OPS] [-f]

optional arguments:
  -h, --help    show this help message and exit
  -c CONF_FILE  string: path to rdbmanage configuration file
  -j JOB        string: job to update (backup and clear)
  -m MAX_OPS    integer: maximum number of increments to fetch (-1 implies no
                maximum), -m is ignored if -j is provided.
  -f            flag: force fetch a backup, -f is ignored if -m is provided.
```
