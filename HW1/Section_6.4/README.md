# HW1 - Section 6.4

Let's Start the ping process :

Since I don't have access to University network, I'll ping 8.8.8.8


```
ping 8.8.8.8 >log.txt 2>&1 &
```

The command returns the Process ID for the process running in the background ...


#### Check the process :

* First method :

using "jobs" command to see the running processes ...

```
jobs
```

The output is like this :

```
[1]  + running    ping 8.8.8.8 > log.txt 2>&1
```


* Second method :

using "ps" command, to see the running processes :

```
ps
```

The output is Here :

```
   PID TTY          TIME CMD
 14244 pts/0    00:01:42 zsh
 40574 pts/0    00:00:00 ping
 40636 pts/0    00:00:00 ps

```


#### Finish the process :

Put the background process ID instead of <PID> in command bellow :

```
kill -9 <PID>
```


now the process is killed ... :)


The ping command output is saved [HERE](https://github.com/alijafari79/Python_Lab/blob/main/HW1/Section_6.3/log.txt).
