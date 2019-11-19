# PassWord Locker

#### PassWord Locker App, 9th Nov, 2019
#### By **Wilbrone**
## Description
This app allows users to store their credentials and other social media account details. For users to use the app they have to log in 
or creat an account on the app. When creating the account credentials the user is prompted to either give there own password or allow the app to generate for them. They can finally save the credentials and view them.

## Technologies Used
This project was build using Python3.6.


## BDD
Once the user runs the program they are prompted with two choices, if they have an account on the app or not, if not they will have to create an account before they log in. If they do have an account they will just login, if the log in details are incorrect the system will give them a message and exit. If the logins are correct they move on th the next satge. Here they get options which are, they can create social media credentials by choosing `cc` or see the credentials they added by choosing `dc` . They also have an option of logging out by entering `ex`. When a User chooces to display there credentials and they have none, the system checks if they credential array for the logged in user is equal or less than `0` they will get a message telling them that they do not have any credentials saved yet, and ask tem to add or create a new one.
When a user decides to create a new credential, they will be asked to enetr the media for which they are creating the credentials, the user name and the email they will use. they are also to either enter their password or let the system generate for them. They can save the changes.
they can add as many credentials as they would have.


## Development server
Run `source env/bin/activate` to enter into the virtual environment and `./start.sh` to serve the app locally

https://wilbronenews.herokuapp.com/ to access the deployed application on heroku


## Support, Further help and contact details
wilbroneokoth@gmail.com

### License
*MIT License*
Copyright (c) 2019 **Wilbrone Baron**

