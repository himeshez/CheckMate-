# CheckMate

## Introduction

In this project, we will learn how to create a Todo webpage named as ToDoer. This webpage can be used to make Todo lists, which are highly beneficial to prioritise and store daily tasks which need to be done. Unlimited number of new tasks can be added and removed as per user convenience. Once you complete a task, you can check it off as completed.

<hr>

## HTML Layout

The index.html file gives the basic framework for the webpage. In the head tag, we have linked the style.css file which provides the styling for the page and also imported fonts from fontawesome.

In the body tag, firstly we have used wrapper to center the contents of the webpage. Now, we have created a class named inputField with text type input to "Add Your New Todo List". Beside that, we have added a *"plus"* button to add in more fields.
Now, we add an unordered list tag with class as todoList.

In the footer class, we have added a span element showing the number of pending tasks. At the end, we have added a button *"Delete All"* to clear all the tasks from the list.

Lastly, we have linked the script.js file in the body tag.

<hr>

## CSS Styling

In the style.css file, we have styled the various elements of the webpage according to our will. We have specified the height, width, padding and background colour for the body of the page and also given different colours for user selections.

In the wrapper class, we have styled the header and inputField differently. The input field box has been given a flex display.

Further, we have styled the input in the input field. We have also added the hover feature to the inputField button.

Now, we have styled the various list items present in the unordered list.

<hr>

## JavaScript Interaction

Now, we'll talk about the JavaScript interaction which makes our page functional.

First, we have created variables for inputBox, addBtn, todoList, deleteAllBtn, and input. Then, we have added functioning for taking user input in the input field.

Further, we have created a showTasks function to show all the entered tasks in the list. Then, we have created a variable pendingTasksNumb to store the number of pending tasks for the user.

Following this, we have added an event listener for the input field to enable adding of new tasks through the ENTER key in the text field.

We have also added a functioning delete button beside each stored task to remove it from the list.

At the end, we have added a deleteAllBtn to delete all the stored tasks from the list.

## Overview
<div align="center">
<img width="1000px" height="395px" src="https://github.com/himeshez/CheckMate-/blob/0d38acc80924e9064bf32aecd63a1a105b4c8792/ToDO.gif"/>
</div>

<hr>

## Conclusion

We have successfully created a fully-functional Todo webpage using HTML, CSS and JavaScript.
