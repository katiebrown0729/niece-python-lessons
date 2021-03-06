# niece-python-lessons
This repo contains a bunch of lesson to help my nieces learn Python

## Tools used:
For these lessons we will rely on core material from the following online material:
* [Udemy Complete Pything Programming Course]( https://www.udemy.com/complete-python-programming-course-beginner-to-advanced/learn/v4/overview) I like this one because it starts people out using Jupyter notebook
* [Packt Beginning Python Video](https://www.packtpub.com/application-development/beginning-python-video) This one is more programmer centric

***
## January 1st session - Getting Started with Jupyter Notebook
In this session we'll review your installation of Anaconda and PyCharm.  And do some simple things with Jupyter notebook.
Jupyter notebook will be familar to you from your MATLAB experience from your engineering courses.
#### Prerequisites
Sections 1 - 3 of the Udemy Complete Python Programming Course
***
## January 7th session - User Input, Dictionaries
In this session we're going to review user input, dictionaries, and introduce for loops.
#### Prerequisites
Sections 4 and 5 of the Udemy Complete Python Programming Course

#### Exercises
* The exercises for the session can be found in this the lessons folder of this repo at: [Jupyter Notebook]( https://github.com/JohnFunkCode/niece-python-lessons/blob/dev/Jan%207%20-%20word%20count%20lesson.ipynb  )
* The stand alone code is available in the src folder of this repo at: [wordcount.py](https://github.com/JohnFunkCode/niece-python-lessons/blob/master/src/wordcount/wordcount.py)

***
## January 15th & January 21st session - Loops, Functions and Modules
In this session we're going to begin our discussions about functions and modules
#### Prerequisites
* Sections 6 and 7 of the Udemy Complete Python Programming course
* Section 6 and 7 of the Packt Beginning Python Video course
* Review sections 1-5 of the Packt Beginning Python Video course - most of this will be a review of material from the Udemy course

#### Exercises
* The exercises for the session can be found in this repo at: [Text Analytics Functions.ipynb](https://github.com/JohnFunkCode/niece-python-lessons/blob/master/January%2015%20-%20Loops%20Functions%20Modules%20.ipynb)

***
## January 28th Session - Using other peoples code 
Kids now days don't understand how lucky they are to have such broad collection of third party code to work with.  You can find a library of code someone else has written to do just about anything you can imagine now days.  In this session we're going to learn how to use add-on packages in Python.  

#### Prerequisites
* Read about using Python packages by reading the two following articles
  * [Python Package Tutorial](https://packaging.python.org/tutorials/installing-packages/)
  * [Python Package Documentation](https://docs.python.org/3/installing/index.html)
* Read about the [Python Standard Libraries](https://docs.python.org/3/library/index.html)  Don't worry about memorizing all of them or learning how to use all of them, for now just get familar with what's available.  Also pick one or two you want to explore.
* Read about [Matplotlib](https://matplotlib.org/)  Again don't worry about learning how to use all of Matplot, just get familar with what's available.   We'll start to explore it with some labs.

#### Exercises
We'll start the day learning how to plot the results of our analysis on a graph using Matplotlib.
Then our main exercise for this session will build on our text analytics theme.
We'll move away from simple user input and instead get the text for our analysis from files using capabilites of the python standar libraries.  
* Our first exercise is to learn to use Matplotlib the exercise for that is [Jan 28 - Matt Plot Experimentation.ipynb](https://github.com/JohnFunkCode/niece-python-lessons/blob/master/Jan%2028%20-%20Matt%20Plot%20Experimentation.ipynb)
* Our second exercise using text analytics is in [Jan 28 - File Reading Experiements.ipynb](https://github.com/JohnFunkCode/niece-python-lessons/blob/master/Jan%2028%20-%20File%20Reading%20Experiements.ipynb)


***
## February 4th Session - It's time for Pi
We've been learning the core of the Python language for a month now.  Let's change it up and have some fun and build our first Raspberry Pi project.

### Prerequisites
* Get a [Raspberry Pi starter kit](https://github.com/JohnFunkCode/niece-python-lessons/blob/master/RaspberryPIStarterKit.md)
* Read the [Packt Python Programming with Raspberry Pi](https://www.packtpub.com/hardware-and-creative/python-programming-raspberry-pi) book.  (or at least as much of it as you can)
* Download [GitHub for Windows](git@github.com:xacaxulu/niece-python-lessons.git).  After installing GitHub for Windows - reboot your system.   Then open a command window and type *git* and you should see a list of github options.
* Read the [GitHub Tutorial](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)

### Exercises
#### Exercise 1 - Get your Raspberry Pi running
* If you haven't already, we'll format your memory card and load NOOBS.  Follow the instructions in the [How to get NOOBS tutorial](
https://www.raspberrypi.org/documentation/installation/noobs.md)

#### Exercise 2 - VNC to your Raspberry Pi
The next thing you need is to be able to remotely control your Raspberry Pi from your laptop.
* To do that you need to install VNC on both your latptop and your Raspberry Pi.
Follow the step in [Raspberry Pi VNC Tutorial](https://www.raspberrypi.org/documentation/remote-access/vnc/)
* Install [Real VNC Viewer on Windows](https://www.realvnc.com/en/connect/download/viewer/windows/)

#### Exercise 3 - Sharing Code with your Raspberry Pi via Github
* Create a new repository with a very simple README stating this is your first Raspberry Pi project.
* On your laptop use git clone to clone your new repository into your code directory.
* Using Atom or Pycharm create a simple Python program that prints the digits 1 - 10
* Commit those changes and push them back to the repo
* On your raspberry pi clone your new repository into a directory called code

#### Exercise 4 - built a circuit to connect a LED to a GPIO Pin
There is a great tutorial on this at [ThePiHut](https://thepihut.com/blogs/raspberry-pi-tutorials/27968772-turning-on-an-led-with-your-raspberry-pis-gpio-pins)
Don't worry much about the code, we'll get the code in the next exercise

#### Exercise 5 - Code to Control the GPIO pins of your Raspberry PI
* We will be using the Gpiozero library for all of our code.  They have a great [documentation and recipies site](https://gpiozero.readthedocs.io/en/stable/)
* fork my repository at https://github.com/JohnFunkCode/RaspberryPiTutorial-1 if you need help see: https://help.github.com/articles/fork-a-repo/
* clone your repository to laptop
* change the code to make it blink the LED 10 times in a for loop
* push it back to github and clone it down to your Raspberry Pi

#### Exercise 6 - Extra Credit - More advanced interactions with Rasberry Pi
Using VNC to remote to the Rasberry Pi is easy and it gives you a lot of functionality.  Pulling Code from Github is also a very good practice and it allows you to use more powerful tools on your laptop in your development.  But you should also know the quick and dirty ways to interact with the Rasberry Pi.  The fastest way to get access to these tools is to install Ubuntu Linix on you Windows 10 laptop.  This sounds complicated, but in the Windows 10 Fall Creators update Microsoft made it really easy.  Just follow the steps on the [Developer's Tidbits blog](https://devtidbits.com/2017/11/09/ubuntu-linux-on-windows-10-how-to/)

One you have it open you can learn to use a few unix tools to interact with your Raspberry Pi
* SSH - SSH allows you to open a remote terminal session to your Raspberry Pi - Here is a good [tutorial](https://www.raspberrypi.org/magpi/ssh-remote-control-raspberry-pi/)
* SCP - SCP allows you to directly copy files to and from your Raspberry Pi - Here is a good [tutorial](https://www.raspberrypi.org/documentation/remote-access/ssh/scp.md)

***
## February 11th Session - Simple Components with Raspberry Pi
Now that we got the Raspberry Pi's running and know how to get code on them via Github we're going to continue
last week's exercises to build some simple circuits and write a bunch of code on the Raspberry.

#### Exercise 1
Build a circuit to connect an LED to a GPIO pin and write some code to make it blink.   Look back at Excercise 4 from 
last week for more details

#### Exercise 2
Build a circuit to connect a bunch of LEDs to GPIO pins and write some code to make them race up and down.  Example code for this
is in src/gpiozero-racingLED.py

#### Excercise 3
Play with Pulse Width Modulation to vary the duty cycle you put on your LEDs to make them glow etc.  Example code for this 
is in src/gpiozero-pwmLED.py

#### Excercise 4
Add some buttons to your LED circuit and write some code to do things with them.   I suggest first just making sure your buttons
work, then make them start your string of LEDs racing.   Example code for this is in src/gpizero-buttons.py

***
## February 17th Session - Creating Web UI with Flask - Part 1
After taking a brief side trip to explore building circuites and programming hardware with our Raspberry Pi's its time to get back to more code.  This week we're going to begin creating web UI's in python so our code can be more interactive.  There are a lot of new concepts for you to learn so this will most likely take a few sessions.

Homework Assignment:
To get an understanding of where we're going listen to the entire [Flask Tutorial Step by Step](https://www.udemy.com/python-flask-tutorial-step-by-step/learn/v4/content) course on Udemy.  This first time through, don't try to do any of the lectures, I just want you to get a broad understanding of what the Flask framework does so we can work through it piece by piece. 

We are also going to step up our game and start working with Pycharm which is a more professional integrated development environment (IDE).  Please review the [Pycharm Quick Start Guide](https://www.jetbrains.com/help/pycharm/quick-start-guide.html)

Another handy reference you'll need is the [W3Schools](https://www.w3schools.com/) HTML web development site.

#### Exercise 1 - building your first flask application
Using Pycharm we're going to create a new project and build a very simple flask app.  I like the folder structure Santiago uses to organize his work in the Udemy [Flask Tutorial Step by Step](https://www.udemy.com/python-flask-tutorial-step-by-step/learn/v4/content), so we'll mimic it.
* First create a new project in Pycharm - put in in your code directory in a directory called **flask-textanalytics**
