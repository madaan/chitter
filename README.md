chitter
=======
This script can be used if you have a list of recepients, which need to be allocated some piece of information (say a unique code). A bit IITB specific, but can be adopted to suit your purpose with minimal modifications to sendChits.py. 

###Usage
python sendChits.py attendeesFile chitsFile

#####attendeesFile format :
Username,IITB RollNumber
Eg.
Aman Madaan, 13305004

#####chitsFile format :
One chit (information to be distributed on each line)
Eg.
Yellow
Black

###Configuration
maildegs.py stores all the global configuration information

<code>
'''  
Global def  
'''   
senderEmail = ''  
senderName = 'Tarun Jain'  
eventName = 'test event'  
emailSubject = 'Chitcode for : ' + eventName  
</code>
