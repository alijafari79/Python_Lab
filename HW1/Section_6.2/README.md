# HW1 - Section 6.2


Now let's get the process IDs for firefox and kill all PIDs :

```
ps ax | grep firefox | awk '{print $1}' | xargs kill
```

### Before Kill :

![image](https://user-images.githubusercontent.com/50498845/201216811-94a30a88-8832-4c1c-aa44-1fc75522c65e.png)


### After Kill :

![image](https://user-images.githubusercontent.com/50498845/201217768-2e0496bc-e1dd-4ba5-8f82-0997e51ffc25.png)

There's just the grep process looking for firefox process ... :)
