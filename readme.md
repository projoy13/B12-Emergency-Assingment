1. What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?

when we have to call specific or work with specific element at that time we use getelementById and must be id  name should be unique

when we have to do task with multipel element at thhat time we use getElementsByClassName so that we  can call all the element at the same time

we can use multipel elemet by useing querySelector / querySelectorAll**?

2. How do you **create and insert a new element into the DOM**?
 By useing document.createElement("p")



 3 .What is **Event Bubbling** and how does it work?
 It almost like a button ...in easy word if i use 
 <button id="push">fire</button>
 document.getElementById('push').addEventListener('click',function(e){
 console.log('push')
 } )
 so whenever i press the fire button it will print fire  
4.

5.  What is the difference between **preventDefault() and stopPropagation()** methods
preventDefault():it stop the default action of the event
stopPropagation():eit stop the event from bubbling
