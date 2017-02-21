# HashCode-2017
a multi language solution to the pizza problem statement 



To manipulate java Files :

Pizza

Practice problem for the Google HashCode 2017.

Effectiveness's for v0.02

Slicing of: example, small, medium slices took 10m 39 seconds on a MacBookPro Results:

example 6
small 30
medium 33037
big - too long to slicing. Was ran once from the commit and took about 20 hours.(a desktop PC with an Intel-I54670K)
original assignment - Task.pdf
input data sets
Prerequisites

Java 1.8
maven 3
Run

To build and run the application execute:

   mvn clean install 
   mvn exec:java -Dexec.mainClass="com.google.hashcode.App"
Submit task automation

Google provides an online mechanism to check the task results. It requires:

archived source code
at least one output file
To zip the source code execute :

./zipSourceCode.sh
Deprecated

To automate interaction with online submission can be used SeleniumIDE with a firefox browser.

login to the submission page
setup selenium test suite(submitResultsViaSelenium) according to yours file system
execute the test case and see scores on web. See the video instruction on YouTube






To manipulate python files : 

Option 1: Call the interpreter

For Python 2: python <filename>.py
For Python 3: python3 <filename>.py
Option 2: Let the script call the interpreter

Make sure the first line of your file has #!/usr/bin/env python.
Make it executable - chmod +x <filename>.py.
And run it as ./<filename>.py
