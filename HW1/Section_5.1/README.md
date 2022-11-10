# HW1 - Section 5.1


Using dpkg, let's list all the packages installed :

```
dpkg -l > dpkg_list_installed_packages.txt
```


Now let's check the firefox version :

```
dpkg -l | grep firefox
```

The output is like bellow :


```
ii  firefox                                       105.0+build2-0ubuntu0.18.04.1                   amd64        Safe and easy web browser from Mozilla
ii  firefox-locale-en                             105.0+build2-0ubuntu0.18.04.1                   amd64        English language pack for Firefox
```

- [X] So the version is **105.0**
