# HW1 - Section 5.3

Using the command bellow, we'll find the lines starting with "GNU", ignoring the preceeding spaces :


```
grep "^[[:blank:]]*GNU" ./GPL-1
```

Here is the Output of the command :

```
                    GNU GENERAL PUBLIC LICENSE
                    GNU GENERAL PUBLIC LICENSE
    GNU General Public License for more details.
```

Now let's find all the words containing "cept" :

```
grep "cept" ./GPL-1
```

The result is Here :

![image](https://user-images.githubusercontent.com/50498845/201208976-c785111a-a3d8-4ea7-9372-4b81d3bfb0a6.png)
