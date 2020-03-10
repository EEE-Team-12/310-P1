# Setting up Git (Windows)

**1.**  If you dont have **git** in your computer already you can download it from [here](https://git-scm.com/downloads).

**Note:** Engineering lab computers should already have git installed.

**2.**  Go to desktop then press right click , you should see the following:

![opening git bash](Images/01_readme.PNG)

then click **Git Bash Here**. You should see the following:

![git bash](Images/02_readme.PNG)

**3.** On the on the git bash terminal , type this command **`` ssh-keygen ``**.

![generating the ssh key](Images/03_readme.PNG)

press enter , then you should see the following:

![generating ssh key](Images/04_readme.PNG)

- press enter again. This time it will ask you to provide a **passphrase**. I recomend to make this passphrase short e.g. eee , lol , ez , asd ect...

![ssh pass phrase](Images/05_readme.PNG)

once the **passphrase** is configured successfully you should see this.

![success pass phrase](Images/06_readme.PNG)

- then on the terminal , type this command **`` eval $(ssh-agent -s) ``** then press enter.

- then type this command **`` ssh-add ~/.ssh/id_rsa``** then press enter. Then provide your passphrase. If successful you should see the following:

![adding sshkey to agent](Images/08_readme.PNG)

**4.** Go to [github](https://github.com/) , then log in to your account. 

Once your logged in:

- nagivate to settings in your account , located on top right.
![adding ssh to git hub](Images/09_readme.PNG)

- nagivate to **SSH and GPG keys** , then click ** New SSH Key**
![read me png](Images/10_readme.PNG)

- give title to ssh key , then paste the ssh key like so:

![adding ssh to github](Images/11_readme.PNG)

then press **add ssh key**








 





















