# HW1 - Section 6.3

Let's get the list of devices and save into out.txt :

```
cat /proc/devices > out.txt
```

Now then make and error intentionally to redirect it to the out.txt.
So instead of "/proc/cpuinfo" let's type "/proc/cpuinf" :

```
cat /proc/cpuinf >> out.txt 2>&1
```

The previous command raises an error for not finding the file "/proc/cpuinf" and the error message is redirected to
out.txt file.

Then run it again correctly to append the cpuinfo to the file :

```
cat /proc/cpuinfo >> out.txt 2>&1
```
