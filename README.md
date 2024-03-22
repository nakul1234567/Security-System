# Security-System
INTRO 

We are developing a security system that utilizes facial recognition technology to safeguard high-security environments such as secret research laboratories with confidential information or machinery. We have implemented a hierarchy system where people can attend to different tasks if they have enough authorisation. The facial recognition system uses a database to store the data that it uses to identify the scanned face and then grant or reject access depending on the authorisation level and the task.

There are a few restrictions to granting access, such as the face has to be facing the front and clear.

We have also implemented an error system and security alert system that is used when something goes wrong or when certain conditions are not met. The security alert automatically shuts the system and does not let you try again. The error shows a retry message that gives the user three tries(set as flags) to access the system and if the user does not gain access, the system does not allow for more tries.

How it Works:

Our security system takes into account 6 criteria for recognizing faces. The criteria are:
Whether or not the person has a beard.
Whether or not the person has a moustache.
Whether or not the person has spectacles.
Skin color
Hair color
Eye color

Also, our system requires the following criteria to be able to grant access without any chances of misconduct:
No signs of intoxication
No signs of sleepiness
A significant amount of light
Face facing towards the camera
Only one person in the camera frame
Clear face

Now all of these things can only be scanned with the help of a camera and supporting software which we do not have. So instead of getting information from the software about the above-mentioned criteria, in our code the above criteria will be input from the user.

We have made a hypothetical database as well which would allow you to run the code and test it.

To run our program, simply run the 204face_recProject.py file. The rest of the files are more information on our project or attempts to make something even better.
Hope you like our Project.
Made by:- Nakul Bhalla


