# HW1 - Section 3.2


Create A & B directories in HOME :

```
mkdir ~/A ~/B
```


Now changing directory from **Desktop** to Folder **A** :

```
cd ~/Desktop
cd /home/ali/A
```


Then moving from **A** to **B** :

```
cd ../B
``` 

Now we are in B, creating a file in **A** and copy back to **B** :

```
cd ~/B

touch ~/A/test.txt && cp ~/A/test.txt ./
```

Now let's move the file in **A** to the Desktop :

```
mv ~/A/test.txt ~/Desktop
```


Then remove directory **B** and sub-folders and files :

```
rm -r ~/B
```
---
