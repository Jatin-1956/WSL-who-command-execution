# WSL-who-command-execution

### #Open PowerShell

wsl

sudo bash -c "echo '[1] [00053] [~~  ] [runlevel] [~       ] [5.4.91-microsoft-standard-WSL2] [0.0.0.0    ] [2021-04-05T23:10:15,040218+00:00]' | utmpdump -r > /var/run/utmp" 2> /dev/null

### #Enter password

exit

wsl sudo login -f user &nbsp;&nbsp;&nbsp;_#Replace 'user' with your username_

### #Enter password

>(optional) /sbin/runlevel &nbsp;&nbsp;&nbsp;_#If 'unknown' is displayed, exit from the shell and redo the process carefully_

who

who -q

### #After work done

exit

exit          


## Thanks to [@therealkenc](https://github.com/therealkenc)

