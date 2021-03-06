# GoogleHashCode2017  
![google hash code logo](./documentation/logo.png)
hash tags: #hashcode #2017 #googleHashCode 
[![Join the chat at https://gitter.im/GoogleHashCode2017/Lobby](https://badges.gitter.im/GoogleHashCode2017/Lobby.svg)](https://gitter.im/GoogleHashCode2017/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Build Status](https://travis-ci.org/LyashenkoGS/GoogleHashCode2017.svg?branch=master)](https://travis-ci.org/LyashenkoGS/GoogleHashCode2017)

##Pizza
Practice problem for the Google HashCode 2017.

##Effectiveness's for v0.02
Slicing of: example, small, medium slices took 2 Minutes on the Dell Workstation (
Results:
 * example 6
 * small 30
 * medium 33037
 * big - Was ran clustered  
 from  the commit and took 18.18 Minutes Accurateley Displaying a principle of the slicing method .(A Reurbished Experimental Workstation from Dell (Dell Precision M4800 (Nvidia K2100M Quadro GPU )
  
 
* original assignment - [Task.pdf](./documentation/TaskDescription.pdf)
* [input data sets](./inputDataSets)

##Prerequisites
* Java 1.8
* maven 3

##Run
To build and run the application execute:
       
       mvn clean install 
       mvn exec:java -Dexec.mainClass="com.google.hashcode.App"

##Submit task automation
Google provides an online mechanism to check the task results. It requires:
* archived source code
* at least one output file

To zip the source code execute :

    ./zipSourceCode.sh
    
    
## Deprecated
To automate interaction with online submission [SeleniumIDE](https://addons.mozilla.org/en-US/firefox/addon/selenium-ide/) can be done
 with a firefox browser.
* login  to the [submission page](https://hashcodejudge.withgoogle.com/#/rounds/6553823069863936/submissions/)
* setup selenium test suite(submitResultsViaSelenium) according to yours file system 
* execute the test case and see scores on web. See the [video instruction on YouTube](https://www.youtube.com/watch?v=Wg7s3CtIeCs&feature=youtu.be)
