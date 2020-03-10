# Setting up git (Windows/Mac)

**Important:** You have to do these steps for each device. For example , once for your laptop and once for uni computers. You only need to do this once for uni computers.

**1.**  If you dont have **git** in your computer already you can download it from [here](https://git-scm.com/downloads).

**Note:** Engineering lab computers should already have git installed.

**2.** Please follow these tutorials:
- [Mac](https://www.youtube.com/watch?v=8BLLShRqKd4) (3 mins)
- [Windows](https://www.youtube.com/watch?v=WgZIv5HI44o) (3 mins)

# Getting started with git 

There are 7 commands that we will mainly use for git.
- clone 
- add
- commit 
- push
- pull
- merge
- branch 
- checkout

##  add , commit & push

Consider you made changes to project folder (added file or edited files) and we want to push these changes online for the team to see (kind of like uploading files onto google drive).

- first ,  you need to tell git what files you want to "upload online". We do this using **`` git add --all``** 

the command **`` git add --all``** tells git that we want to **upload all edited and newly added files** into our project folder.

- then , you need to add a label to this upload batch , for example , if I were to upload new images online , I would label them "uploaded new images". We can do this using **`` git commit -am "uploaded new images"``**

Notice that the text inside the **``" "``** will be contain the label for this upload batch.

- next we **click "send"** (like when typing message on messenger then clicking send) except the message is files we want to upload and the destination is the online team repository (kinda like google drive) . We can do this using **`` git push origin master``**.

###  summary ( git add ,  commit & push )

- **`` git add --all``** , to tell what files to upload.
- **`git commit -am " insert your label message here "`**  , to label the upload.
- **`git push origin master`** , to click "send" to our online repository.


## merge , branch , clone , checkout & pull

TODO 




































 





















