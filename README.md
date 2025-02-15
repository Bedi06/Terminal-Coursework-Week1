# Terminal Coursework

In this coursework we want to test what you've learnt in the previous coursework.

## Tasks

### 1) Find my script

In this repository you'll find `MyDocuments` - this is all the documents that I use on my laptop.

I need to find the `script.js` file that is a part of MyFirstWebsite however you are **not** allowed to use a GUI, you must use Command Line and the Terminal.

What commands would I need to change directory to the directory containing `script.js`? In the section below, write all the commands you used.

Hint: You should use `cd` and `ls`.

#### 1) Answer

<!-- Write your answer here -->

First we type 'ls' to see our list files
Then type ' cd Mydocuments' to change directory and go to MyDocuments
Then use 'ls' to see the list of files we have on MyDocuments
Then use 'cd Projects' to change to Projects Directory
Type 'ls' to have a list of files on Projects again,
Then do 'cd MyfirstWebsite ' and then 'ls' again to see the list of files and 'cd scripts'
And then ls to see the script.js.

~/cyf/Terminal-Coursework-Week1$ ls
GRADING.md HOW-TO-GET-HELP.md HOW-TO-SUBMIT.md MyDocuments README.md
~/cyf/Terminal-Coursework-Week1$ cd MyDocuments
~/cyf/Terminal-Coursework-Week1/MyDocuments$ ls
Photos Projects Quiz Scripts
~/cyf/Terminal-Coursework-Week1/MyDocuments$ cd Projects
~/cyf/Terminal-Coursework-Week1/MyDocuments/Projects$ ls
JavaScript-Core1 MyFirstWebsite PortfolioWebsite
~/cyf/Terminal-Coursework-Week1/MyDocuments/Projects$ cd MyFirstWebsite
~/cyf/Terminal-Coursework-Week1/MyDocuments/Projects/MyFirstWebsite$ ls
index.html scripts style.css
~/cyf/Terminal-Coursework-Week1/MyDocuments/Projects/MyFirstWebsite$ cd scripts
~/cyf/Terminal-Coursework-Week1/MyDocuments/Projects/MyFirstWebsite/scripts$ ls
script.js

### 2) Find my Hotel Photo

Great work!

Next, I want to try and find the photo of my hotel from my holiday in July that I want to send to a friend.

**Note**: You should do this by moving from where you are after completing the previous task.

#### 2) Answer

<!-- Write your answer here -->

We write the following commands:
~/cyf/Terminal-Coursework-Week1/MyDocuments/Projects/MyFirstWebsite/scripts$ cd ..
~/cyf/Terminal-Coursework-Week1/MyDocuments/Projects/MyFirstWebsite$ cd ..
~/cyf/Terminal-Coursework-Week1/MyDocuments/Projects$ cd ..
~/cyf/Terminal-Coursework-Week1/MyDocuments$ ls
Photos Projects Quiz Scripts
~/cyf/Terminal-Coursework-Week1/MyDocuments$ cd Photos
~/cyf/Terminal-Coursework-Week1/MyDocuments/Photos$ ls
HolidayJuly HolidayJune
/cyf/Terminal-Coursework-Week1/MyDocuments/Photos$ cd HolidayJuly
~/cyf/Terminal-Coursework-Week1/MyDocuments/Photos/HolidayJuly$ ls
cyf.png Flight Hotel
~/cyf/Terminal-Coursework-Week1/MyDocuments/Photos/HolidayJuly$ cd Hotel
~/cyf/Terminal-Coursework-Week1/MyDocuments/Photos/HolidayJuly/Hotel$ ls

### 3) Counting Script

Next, I want you to run the script in this directory

```
/MyDocuments/Scripts/
```

You can run the script by typing

```
./count_to_100.sh
```

when you're in the correct directory.

For this task, I want you to **stop** the counter when I have counted to 10.

#### 3) Answer

Copy the output of the script here

<!-- Write your answer here -->

~/cyf/Terminal-Coursework-Week1/MyDocuments/Scripts$ ./count_to_100.sh
I have counted to 1
I have counted to 2
I have counted to 3
I have counted to 4
I have counted to 5
I have counted to 6
I have counted to 7
I have counted to 8
I have counted to 9
I have counted to 10
cyf@cyf-ThinkPad-T570-W10DG:~/cyf/Terminal-Coursework-Week1/MyDocuments/Scripts$

### 4) Quiz

In this directory you'll find a quick quiz for you to complete

```
/MyDocuments/Quiz
```

You should open the quiz in Visual Studio Code and complete it. You can do this either by opening this project in VSCode or by running the command

```sh
code QUIZ.md
```

when you're in the correct directory.
