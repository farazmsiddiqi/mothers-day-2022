# For Mama

You've invested so much of your time into raising Faiz and I. 
We would not be who we are today without your efforts and love.
I know that you have spent a lot of time raising us, and that is time that you will never get back.

The best gift I can give you for Mothers Day is time.
You should use your time on stuff that you enjoy doing.

Stop wasting time telling your bosses that you are online.
This program moves your mouse when you are away!
No longer do you have to call me to move your mouse while you are not on your computer :)
Microsoft Teams and Skype will think you are online as well!!


## Installation

Call Faraz for installation

```
cd move-mouse
pip3 install pynput
cd src
python move-mouse.py -s 1 -m both -p 10
```


## Arguments

```
-h, --help                        show this help message and exit
            
-s SECONDS, --seconds SECONDS     Define in seconds how long to wait after a user is
                                  considered idle. Default 300.

-p PIXELS, --pixels PIXELS        Set how many pixels the mouse should move. Default 1.

-c, --circular                    Move mouse in a circle. Default move diagonally.

-m MODE, --mode MODE              Available options: keyboard, mouse, both; default is mouse. 
                                  This is the action that will be executed when the user is idle. 
                                  If keyboard is selected, the program will press the shift key. 
                                  If mouse is selected, the program will move the mouse. 
                                  If both is selected, the program will do both actions.
```
