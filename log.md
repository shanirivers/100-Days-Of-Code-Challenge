---
layout: post
title: 100 Days Of Code Log
---
# 100 Days Of Code - Log

### Day 028: December 6, 2017

**Today's Progress**: Implemented UIPicker for categories. Added category property to my model. 

**Thoughts**: Didn't take too long to figure it out, since its pretty similar to date picker but with more methods to implement, as date picker is kind of prepackaged.

### Day 027: December 5, 2017

**Today's Progress**: Added UIPicker to view and had fun with figuring out how to control constraints in code. 

**Thoughts**: Was really surprised that you could create connections to constraints and control their values. I know, I'm weird. LOL!

### Day 026: December 4, 2017

**Today's Progress**: Adding another attibute for tasks, categories. Designed icons in Sketch yesterday (Dec 3). Began learning about UIPickerView and how to implement it.  

**Thoughts**: Picker view is interesting, just did a dry test run in a temp project to test it out. 

### Day 025: December 2, 2017

**Today's Progress**: Changed the style of the section headers for my tableview programmatically. Apparently, I didn't fix my edit and new item bugs - so I positive that I did this time. 

**Thoughts**: Just when you think that you've fixed something and than you find out that you didn't. 

### Day 024: November 30, 2017

**Today's Progress**:   Fixed edit and segue issues. Onto adding categories.

**Thoughts**: Bejeezus! It's truly amazing how a fresh pair of eyes can solve a problem.  My edit bug was just a logic issue, just had to change a == to a !=. 

### Day 023: November 29, 2017

**Today's Progress**: Worked on trying to solve edit bug and segue issues. 

**Thoughts**: Redid segue setup and removed code for the navigation bar that I did for the edit view. Was able to get it to work and for the correct pop/modal behavior I wanted for the two actions - edit and add. Still couldn't get the edit item to replace the existing. 

### Day 022: November 28, 2017

**Today's Progress**: Fixed nav bar appearance and started researching on how to solve my the save edit bug. 

**Thoughts**: It's amazing how a fresh pair of eyes can solve a problem.  

### Day 021: November 27, 2017

**Today's Progress**: Worked on getting the navigation bar styling and buttons to work. 

**Thoughts**: Implementing a nav bar programmatically. 

### Day 020: November 26, 2017

**Today's Progress**: Started to implement editting functionality. 

**Thoughts**: Got the segue to edit view to work, but working out issues/bugs with the navigation bar styling and saving to the same item that was originally selected. 

### Day 019: November 25, 2017

**Today's Progress**: Implemented shake-to-undo-delete gesture. 

**Thoughts**: Took a good part of the morning to tinker with it, but it works like a charm. Just hoping it continues to work. 

### Day 018: November 24, 2017

**Today's Progress**: Implementing code for removing item(s) from the main array.

**Thoughts**: After discovering that the items weren't getting deleted, I found that it was much easier to just work on the main data structure and have updates stem from that. It's working like it wanted - yay, for delegates!

### Day 017: November 22, 2017

**Today's Progress**: Attempted to work on table reload, but realized that the delete functionality was not working correctly. 

**Thoughts**: Reverted project back to state from the 21st, so that I could work on the delete functionality that was not implemented correctly (I basically didn't remove the item from the main array and only removed it from the tableview).  

### Day 015 & 016: November 20 - 21, 2017

**Today's Progress**: Learned that I need to programmatically implement cell. 

**Thoughts**: Studying up on how to code constraints for my cell - it's taking a couple of days.  

### Day 014: November 19, 2017

**Today's Progress**: Fixing my broke custom cell when I implemented gestures. 

**Thoughts**: With how I want the gestures to work, I broke my custom cell in the process. Two steps back for one step forward.  

### Day 013: November 18, 2017

**Today's Progress**: Started implementing gestures needed for app. 

**Thoughts**: Spent part of day testing it out on own test app, still not sure if what I'm implementing is going to work. 

### Day 011 & 012: November 16-17, 2017

**Today's Progress**: Still experimenting with gestures. 

**Thoughts**: Took all day to read up and experiment with gestures. Coding them manually, as I have a custom cell. It's taking a bit longer than I anticipated.


### Day 010: November 15, 2017

**Today's Progress**: Started working on adding more than one gesture to control edit and delete. 

**Thoughts**: Found out that I need to learn a bit more about handling more than one gesture and that it involves some code to get it to work. On the bright side, I'll be pretty familiar with creating custom tableview cells and how to manipulate their behaviour. Yay, me! 

### Day 009: November 14, 2017

**Today's Progress**: Disable save button, if there's invalid data, tap to complete functionality and implemented deletion with alerts.

**Thoughts**: I think working with a multi-dimensional array was the way to go on this project, found it was easy to wrap my mind around it and to implement all that I wanted to without too much trouble. 

### Day 008: November 13, 2017

**Today's Progress**: Implemented add functionality, because its important.

**Thoughts**: Took some brain grease to figure it out since I was using a multi-dimensional array. But I found it was easy enough.

### Day 007: November 12, 2017

**Today's Progress**: Implemented code for pulling date from a date picker.

**Thoughts**: Not as hard as I thought, much easier then the UISwitch. 

### Day 006: November 11, 2017

**Today's Progress**: Started implementing the 2nd view controller. 

**Thoughts**: Spent most of the hour or so trying to get my UISwitch from dismissing my VC, so annoying, but learned a bit more about the view controller lifecycles. Good times!

### Day 005: November 10, 2017

**Today's Progress**: Finished implementing the custom cell. Finished the 2nd view controller's UI. 

**Thoughts**: Working with xibs wasn't that hard, just had to work a bit on it.  

### Day 004: November 9, 2017

**Today's Progress**: Decided to create a custom tableview cell. Started implementing.

**Thoughts**: Since I programmatically implemented the tableview cell and sections, I'll have to create a custom cell as well, because I want to show more detail about each item. Too soon to tell if I'm implementing it correctly or not. 

### Day 003: November 8, 2017

**Today's Progress**: So much fun working with multidimensional arrays! Was able to implement the sections and row sort output based on whether item is complete or not. 

**Thoughts**: Found it a lot easier to programmatically implement the tableview cell and sections. I think this is due to figuring it out using Playground. 

### Day 002: November 7, 2017

**Today's Progress**: Implemented half of the tableview functionality for the app.

**Thoughts**: Working through implementing section output. 

### Day 001: November 6, 2017

**Today's Progress**: Implemented major portions of the design. Color scheme and uploaded custom font to project. 

**Thoughts**: Was interesting to learn about converting color hexidecimal to UIColor. Decided keep the color hex in the project to make it easier for me to update it in the future. 

**Link to the color hex method: [Convert Color Hex code to UIColor](https://github.com/shanirivers/Interesting-Code-Snippets/blob/master/ConvertHexToUIColor.swift)

### Day 00: November 5, 2017

**Today's Progress**: Worked on app's UI design and added assets 

**Thoughts:** I'm trying to get a handle on working with Sketch, but I've learned a lot about the updates over the past 2 days and now feel pretty comfortable with it and energized by first iteration of the app's UI. Learned how to turn hex code into UIColor using Swift 
