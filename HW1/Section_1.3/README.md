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

[List Of Packages](https://github.com/alijafari79/Python_Lab/blob/53f71ccb807607eaf9f224238e0f06ce76280efd/HW1/Section_1.3/list_of_packages_with_fortune_installed.txt#L255#L257)


Now let's remove **fortunes** :

```
sudo apt-get remove fortunes
```


Then see the list of packages :

```
apt list --installed
```
