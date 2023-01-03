<h1> My exciting python adventrure ig 🐍</h1> <br> 
<h3> Password checker code I guess: </h3> <br> 
<h4> What's required? </h4> 
<p> to make this simple program you will need python, a code editor like Spyder or VSCODE and the time and webbrowser modules. I am pretty sure both of these modules are included with your python install but if the code isn't working open you terminal (mac) or command prompt on windows and write 'pip install webbrowser' and/or 'pip install time'. once you've done this you can change things like where the correct password and username will take you and stuff like that. (the time and webbrowser modules aren't required you just won't be able to have the code wait or open tabs) </p>  

```python

from webbrowser import open_new_tab 
import time 

print ('If you ever have any questions or need assistance type "help" in the console')

Userstatus = input('Are you a new user? ')
if Userstatus == 'yes':
    while True:
            Username = input('Create username: ') 
            Password = input ('Create password: ')
            yes = input ('Is this correct? ')
            if yes == 'yes':
                break
    lenofuser = len(Username)
    lenofpass = len(Password)
    Userstatus = 'no'
    print('Username: ', '*' * lenofuser)
    print('password: ','*' * lenofpass)
    time.sleep(1)
    print()
    print('Username and password sucsessfully created! ')
    print ()
    time.sleep(0.8)
elif Userstatus == 'no':
    Username = ''
    Password = ''
    print ("Now let's get you logged in!")
while True: 
        Username2 = input('Enter username: ')
        if Username2 == Username: 
            break 
        elif Username2 == 'help':
            print (), print('Keep Coping bozo')
        elif Username2 != Username: 
            print ('Wrong username. Please try again')
while True: 
        Password2 = input('Enter password: ')
        if Password2 == Password:
            break 
        elif Password2 == 'help':
             print(), print('Keep Coping bozo')
        elif Password2 != Password: 
            print('Wrong password. Please try again')
time.sleep (0.8)
print ()
print ('Checking Username and Password one last time. Please wait')  
time.sleep(0.8)
print()     
print('Permission Granted!')
print ()
open_new_tab('https://github.com/Liamsimp69420/liamsimp69420/blob/main/README.md')

```
<h4> Why did I make this? </h3> <br>
<p> The simple answer is. I was bored. That also happens to be the complicated reason. idk why i'm writing this.</p> 
<br> 
<h3> A program that checks how many subscribers I have on youtube. </h3> <br>
<h4> What's required? </h4> 
<p> For this project you're going to need the requests module. You can install this by opening your terminal if you are on mac or command prompt if you are on windows and typing ``` pip install requests ``` you might need to install different modules for different projects. But since I wanted to make a robot yell at me I decided it was easiest to use the ``` open_new_tab('') ``` module. You can get this by writing ``` pip install webbrowser ``` in your terminal/command prompt. 
