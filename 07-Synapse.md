---
layout: lesson
title: Exporting data from spreadsheets
root: .
---

Authors:**Kenneth Daily**<br>

## Learning Objectives
* Upload data into Synapse
* Add provenance to describe data improvements
* Document your changes in a Wiki

## Upload Data

Let's store our work in Synapse. You should have created new files 
during previous parts of this lesson. Each was derived from another file
via some cleaning steps that you performed to improve data usability. You should have 
cleaned up the original spreadsheet and then exported that file to a text file format (csv).

1. First, let's create a Project in Synapse - this will be your personal space to work.
   You can share this space (or individual elements within it) later.
   
   [Click Here To Create a Project](https://www.synapse.org/#!ProjectsHome:0)
   
1. Navigate to the files tab, and click `Upload or Link to File`, and find the `csv` file you made.
1. Let's add provenance to it - using the `Tools` menu, click `Edit Provenance`. We'll add the file that
   we started with (syn4951755) as a file we `used`. Let's name our activity "Data processing", and add in some text about what we did. Click save.

So, what did we do? We stored a copy of our data in Synapse. Then, we described the transformation that we performed on the Excel spreadsheet to get it into a clean, standardized format.

However, this doesn't describe the nuances that we found when mucking with the data. This is a great place to use a Wiki! The result of the previous step should keep you on the file you just uploaded. Using the `Tools` menu again, click `Edit File Wiki`. This will bring up a box where you can type in text about this particular file. This way, your notes about it will be right with the file. You can do all kinds of fancy formatting (click the `Formatting Guide` button at the top).

Previous: [Caveats of popular data and file formats.](06-data-formats-caveats.html)
