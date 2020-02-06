# FaceRecognition

Using facial recognition means that the banking customer has only one face which can allow them access to all their bank accounts. 
In cybercrime, a hacker can infiltrate a person’s social media profile and learn key information which can enable them to answer 
security questions such as ‘what was the name of your first pet?’ The biometric software only authenticates a customer based on 
who they are. A hacker can only manage to access a bank account based on what they know about the customer. So this makes 
it easier for a banking customer to transact online on a mobile device by using a device that has authorized access and secondly b
y using a live facial image of themselves via the phone’s camera.

How it works:
•	It recognizes faces using gray levels.
•	Each image is mapped to a long vector of gray levels.
•	Several views of each person are collected in the database during implementation.
•	During recognition a vector corresponding to unknown face is compared with all the vectors available in the database.
•	The face from the database which is closest to the unknown face is declared as a recognized face.
•	K-NN algorithm will be used for both classification and regression. 


