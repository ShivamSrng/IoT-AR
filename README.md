# IoT-AR: Internet of Things coupled with Augmented Reality

## Introduction
IoT-AR is a project by which a user can control the device without even physically touching it. Moreover most distinctive feature in this project is that the controls for any specific machine or machine apperas in form of augmented reality on the user's mobile screen, thereby reucing any chances of errors.


## Developing of Markers
Markers are the most important part of this entire project. Through these markers, the application is able to sort out and identify different machine. These markers need to be uploaded on to the Vuforia website which generates certain points on marker by which it can uniquely identify a marker. More the number of configurations on the marker, easier it will be for Unity application to recognize.


## Working in Unity Engine
The entire application is developed using C# as the language. The result of Vuforia portal is imported to Unity project. Now rendering of components is done in Unity Engine. Along this hardware implementation is done with the help of a lamp, NodeMCU, Jumper Wires, etc. The code for NodeMCU is written and uploaded using ArduinoIDE. And communication between Unity Engine and NodeMCU module is done with the help of requests. Also, to maintain the secrecy of application information like username, password is collected from user, so that no one can masquerade the user and get unauthorized access to machine. So, to store the user specific information PlayFab Database is used. At the end, every thing is grouped together to an app.


## Actual Implementation



https://user-images.githubusercontent.com/67229090/209555089-2f5c99c1-c63b-42e2-977c-0b671e43d8b1.mp4



