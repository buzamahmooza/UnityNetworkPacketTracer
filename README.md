UnityNetworkPacketTracer

# Description
The program emulates a network environment, mainly focusing on the application and transport layers.
The library contains DataLink and NetworkEntity classes which are helpful for connecting and creating network simulations.
The project can be expanded and used to craete more complex networks.

This project started as a makeup question in my networking course at [KFUPM](http://www.kfupm.edu.sa/Default.aspx).
The example under [releases](https://github.com/buzamahmooza/UnityNetworkPacketTracer/releases), the program is emulating an environment where a host is sending an email through a web server, and initiating DNS lookups.
The main purpose is to show the process of communication between nodes and the approximating delays between the messages.

[Link to demo video](https://www.youtube.com/watch?v=OFGy0-Qt96c)

<img src="Screenshots/UnityNetworkPacketTracer%20recording%20fullscreen.gif" alt="General Screenshot"/>


# How to use:
For the example case in the [releases](https://github.com/buzamahmooza/UnityNetworkPacketTracer/releases), the options exist for changing link speeds/propagation delays, file size, and iterative/recursive search.
- Link speed/propogation:

  click the boxes near the link and enter a new value the format used is propogationDelay/linkSpeed
- File size:
  
  enter a value in the textbox on the top left corner
- Iterative/recursive DNS lookup:
  
  Click the checkbox if you want iterative search, otherwise recursive lookup is done by default

<img src="Screenshots/MakeupScreenshot.png" alt="General Screenshot" />


# Team members:
- Faris Hijazi

  Tasked with doing the programming and implementation.
- Mohammed Bejadi

  Tasked with the theoretical and calculation details.
