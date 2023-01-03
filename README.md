'''

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
open_new_tab()

'''
