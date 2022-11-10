# HW1 - Section 4.1


Let's create a new user :

**useradd** help :

	-m : for user home directory
	-s : for user shell
	-G : for user groups

```
sudo useradd -s /bin/bash -m mahdi
```

Then setting the passwd to my Student-ID :

```
passwd mahdi
```

Now let's switch to the new user :

```
su mahdi
```


Now trying to add another user using **mahdi** user :

```
sudo useradd -s /bin/bash -m mahdi2
```

The output show that user **mahdi** is not in sudoers group :

```
mahdi is not in the sudoers file.  This incident will be reported.
```
---

#### Now let's fix the issue :


# * First Approach :



