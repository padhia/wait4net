wait4net
========

wait for network to get connected, then optionally run the command passed as a parameter

usage: `wait4net [-t] [-p] [cmd [arg ...]]`

Options<br/>
`-t <seconds>`: Timer, defaults 60 seconds<br/>
`-p <seconds>`: Polling interval, defaults to 5 seconds

Examples:
```
wait4net
wait4net SpiderOakONE
wait4net -t 600 -p 60
```
