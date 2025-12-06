Sanah White

Debugging is a common term used in coding that basically means to find the problem in your code. The code often communicates this by sending error messages or unexpected results from your code. How I go about debugging is I would open visual studio code then I’d run the debugger and if something is wrong, that specific line of code will be highlighted and a message will be displayed explaining my mistake. I’d then use that error message to find and fix my mistake. I’d often run breakpoints between the lines of code if I want to be specific. 

<center>
<img src="/blog/images/SPACECOUNT2.jpg" alt= "Counting space" width="200">
</center>

An example of this can be this snippet of code here.The point of the code was to count the number of spaces in the given string, “Hello, world, my name is” instead it didn’t count the number of spaces and remained at zero. The problem that I found with the code was that there was no space in between the quotations of the if statement if char=="". It’s a simple mistake with an easy fix: just put a space in between the quotation marks. How I went about it was using the debugging tool and inspecting each variable. 


<center>
<img src="/blog/images/EVENODD2.jpg" alt= "Even or Odd" width="200">
</center>

Another snippet of code that needed some debugging is this one right here. The purpose of the code was if numbers 1 to n were even or odd. The problem that I had discovered was it printed each number out as odd  if it was even also there was no integer function. My original thoughts were to go through each line of code and find the syntax error. After I discovered the faulty line of code I used the breakpoint tool so it’ll tell me exactly what’s wrong so I can fix it. I then found out the input function needed an integer function (int) in front of it so the user could enter numbers. The second issue being with you had to replace the less than sign to an equal sign.


<center>
<img src="/blog/images/Factorial.jpg" alt= "Factorial" width="200">
</center>

The third snippet of code had minor issues but even minor issues can cause a code to fail. The purpose of the code was to give a factorial number of whatever number they had entered. The problem that I had found was that the last print statement was missing the string function ‘str’ for the two variables “num” and “result”. What I did to figure this out was first go through each line of code but when I couldn’t see what was wrong because it was a small mistake I used the run and debug tool which pauses the code when an error is found and leaves a message on exactly what the error is and what line it is on. This tool comes in handy because it’s easy for me to miss mistakes similar to that. 


<center>
<img src="/blog/images/PASSWORD2.jpg" alt= "Guess password" width="200">
</center>

This last snippet of code’s purpose is supposed to ask the user to enter the correct password but they only get 3 attempts. The problem with it was even if the user put the correct answer it was still counted as incorrect. The steps I took while solving this was setting a breakpoint then looking through the variables. After doing that I figured out that the first if statement was equal to the wrong thing it had to be equal to the variable correct_password. 



Debugging is something that requires patience when doing. This is because you can easily think there’s this huge mistake you have to fix when all along it’s a simple syntax error such as missing colon or misspelled word. Thankfully debugging will help me in the future with my coding because I’ll know now to look for the basics like missing things.
 


