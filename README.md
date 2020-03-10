# Setting up git (Windows/Mac)

**Important:** You have to do these steps for each device. For example , once for your laptop and once for uni computers. You only need to do this once for uni computers.

**1.**  If you dont have **git** in your computer already you can download it from [here](https://git-scm.com/downloads).

**Note:** Engineering lab computers should already have git installed.

**2.** Please follow these tutorials:
- [Mac](https://www.youtube.com/watch?v=8BLLShRqKd4) (3 mins)
- [Windows](https://www.youtube.com/watch?v=WgZIv5HI44o) (3 mins)



# Set up work environment

**Note:**  you only need to do this once/per device. You only need to do this once for uni computers.

## Step 1


1. Copy file path of **Desktop**
----

2. Open terminal:
	- **For Windows**: press windows key , then type "terminal" , then select **Command Prompt**

	
	- **For Mac** : press  **commnad + space** , then type "terminal" , select **ternimal**.
----

3. Run this command: **`` cd paste the Desktop path here``** .
		
	For example :	 **``cd C:\Users\ambib\OneDrive\Desktop\310-P1``**
----
	
4 Run this command: **`` git clone git@github.com:EEE-Team-12/310-P1.git``**



## Step 2

1. Copy the file path of the cloned project.
----

2. Open terminal:
	- **For Windows**: press windows key , then type "terminal" , then select **Command Prompt**

	
	- **For Mac** : press  **commnad + space** , then type "terminal" , select **ternimal**.
----

3. Run this command: **`` cd paste the file path here``** .
		
	For example :	 **``cd C:\Users\ambib\OneDrive\Desktop\310-P1``**
----

4. Run this command: ``git checkout -b local``


# Uploading your work to online repository ?

1. Copy the file path of the cloned project.
----

2. Open terminal:
	- **For Windows**: press windows key , then type "terminal" , then select **Command Prompt**

	
	- **For Mac** : press  **commnad + space** , then type "terminal" , select **ternimal**.
----


3. Run this command:  **`cd paste project file path here`**  

	For example :  **`cd C:\Users\ambib\OneDrive\Desktop\310-P1`**
----

4. Run this command: **`` git add --all``**
----
5.  Run this command: **``git commit -am " insert your message here"``**


	For example : **`` git commit -am "finished designing office room"``**
----
	
7. Run this command : **`` git checkout master``**
----
8. Run this command : **`` git pull origin master``**
----
9. Run this command : **`` git merge local``**
----
 
10. Run this command : **`` git push origin master``**
----

11. Run this command : **``git checkout local``**




































 





















