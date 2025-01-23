KEYLOGGER

_OVERVIEW_
This is the first project of my cybersecurity journey. I figured that a little keylogger would get the ball rolling, and help understand how this attack works. 
  It's very simple using the keyboard from the pynput module which I had to install, and just one function that begins logging when a key is pressed in the main funct that uses the Listener class.
      This tool was simply to demonstrate that even a low level attack with simple implementation has the opportunity to grab your information. 

 _Running_
Simple and straightforward to run, you can simply download the logger.py and strokes.txt or make a strokes.txt yourself in the same directory. From then you just run the program, type whatever you want wherever you want,
    and then see for yourself the strokes that were logged in the .txt file. 

_UsageNotes_ 
Only thing that this is used for right now is on your local machine obviously. This shouldn't be inserted into anyone else's system as you can see that whatever application you type in, the strokes get logged.
    Also it's worth mentioning that backspace and enter strokes are not logged. 
