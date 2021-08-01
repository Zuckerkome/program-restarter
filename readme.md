# Program Restarter



This is a simple C++ application that restarts any process.



### Config.txt Setup:

Each setting has to be written in its own line:



1. Program Path (For starting the program)
2. Process Name (For exiting the program)
3. Delay
4. Pressed Button after Restart
5. Activation Button (Initiates Restart)



Note: Replacing any of the parameters with a blank line, will skip the step



##### 1. Program Path

Where the .exe file you want to execute is located.

e.g. C:\Program Files\Application\app.exe

Note: Dont forget to add the exe file to the path!



##### 2. Process Name

What the process name is. If you aren't sure what it is, most of the time it is the name of the .exe file declared at the program path.



##### 3. Delay

How long to wait before button press (key defined at 4.) is simulated. Only whole + positive numbers and in milliseconds.



##### 4. Pressed Button After Restart

The Keycode of the button to press after the process has started up again (+delay). Whole + positve number only. 

All useable keycodes can be found here: https://docs.microsoft.com/en-us/windows/win32/inputdev/virtual-key-codes

(the in the website listed hexadecimal numbers have to be converted to decimal first)



##### 5. Activation Button

The Keycode of the button that activates the program restart. (Same rules apply as in 4.)















