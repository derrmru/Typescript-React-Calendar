# Reusable React Calendar Component

React-only Calendar Component using Typescript superset.

![Calendar Screenshot](./screenshot.png)

## Installation

 - Download Calendar.tsx and Calendar.css files.
 - Drop both files into the same folder in your projects file system.
 - Import Calendar to parent component.

 ## Setup

 1. Calendar takes three props:
 - name: to identify the calendar with your own handle date selection function, helpful if you are using several instances of the component with one callback function.
 - date: the initial or seleted date.
 - updateCalendar: the function to be created by you in your parent component to handle a date selection. It is assumed you will have your own needs and these will require the Selected Date and Calendar Name as parameters.

 2. Obviously you will need React in your dependencies.

## Notes

No frills component. Easy to include, style and adapt as needed for your project.

Enjoy!