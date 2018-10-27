# X-Team 28 yourCalender

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

You have a variety of events and you do not know if they all conflict with each other. yourCalender has a custom data structure that contains events from previous inputs into the program and from current inputs. It is, in all intents and purposes, a calender that reports when you have conflicts.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)  
yourCalender 

2. Output: Describe the output your program will produce.  Include and example format of the output produced.
tastScehduler will output wether or not there are any conflicts in your given task schedule.  
For example:  
You have a conflict on Oct 25th. "Date with the guys" Oct 25th, 5pm-7pm conflicts with "CS400 Midterm" Oct 25th, 5pm-7pm.  
The out put of the program would soley be based on the input of the program, and the text file saved with previous inputs. 


3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.
The data is taken from System.in inputs from the user's keyboard. The format will be strict, and given to the user on startup.   For example:  
"What is your event?"   
-Date with the guys  
"When is your event (Month day timeStart timeEnd)?  
-blalblablah 25h 5pm - 7pm  
"The time input was not formated correct, an example "Oct 25 5pm 7pm".  
-October 25 5pm 7pm  
" "Date with the guys" on Oct. 25th, 5pm to 7pm has been added to your calender."  

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.  
Three text boxes. One for inputting a date, one for removing a date, an one for showing all dates. Input a date would trigger the   sequence as shown above, remoiving a date would print the data structure and you would input what event on what day to remove.   Showing all datas would print the data structure in order.   


5. Types List: Break your solution idea down into units that you think can be implemented with a single class.  
Data Structure: Holds the dates and decription of the events. IE AVL Tree, hashtable   
Main Method: governs data input/output   
data structure methods: Insert, remove, etc..  
calenderNode methods/vars: Data associated with the nodes inserted into the data structure.  
calender methods: conflicts, printing out data about conflicts, etc..  

Name each interface or class and briefly describe its function or purpose.
HashTableADT - interface for a hashtable implementations   
yourCalender - class that governs the methods associated with the implementation of a celender   
calenderNode - class that governs the data within a node inserted into the calender.   

## Edit and Submit this file and any figures referenced by this document.

