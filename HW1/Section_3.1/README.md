# HW1 - Section 1.3

Using command below to install fortune :

```
sudo apt install fortunes
```


Using Command below to list all packages :

```
apt list --installed 
```

We can search for **fortunes** in list of packages :

```
apt list --installed | grep "fortunes"
```

Now here is the list of packages with **fortunes** installed :

[List Of Packages](https://github.com/alijafari79/Python_Lab/blob/main/HW1/Section_3.1/list_of_packages_with_fortune_installed.txt#L255#L257)


Now let's remove **fortunes** :

```
sudo apt remove fortunes && sudo apt purge fortunes
```


Then see the list of packages :

```
apt list --installed
```

We can search for **fortunes** in list of packages :

```
apt list --installed | grep "fortunes"
```

Now here is the list of packages with **fortunes** removed :

[List Of Packages](https://github.com/alijafari79/Python_Lab/blob/main/HW1/Section_3.1/list_of_packages_with_fortune_removed.txt)
