# HW1 - Section 6.2


Now let's get the process ID's for firefox and kill all PIDs :

```
ps ax | grep firefox | awk '{print $1}' | xargs kill
```

