```
usage: rdbmanage [-h] [-c CONF_FILE] (-l | -j JOB | -m MAX_OPS | -t CHECK_JOB)

optional arguments:
  -h, --help    show this help message and exit
  -c CONF_FILE  string: path to rdbmanage configuration file
  -l            list increments of all jobs
  -j JOB        string: job to update (backup and clear)
  -m MAX_OPS    integer: maximum number of increments to fetch (-1 implies no
                maximum), -m is ignored if -j is provided.
  -t CHECK_JOB  string: check configuration of given job
```
