# Text ellipsis project

This project was set by the Learn JavaScript website in order to learn how string methods work in JavaScript. The focus here is the **substring( )** method.

In the **helpers.js** file, there's a function named **getDescription( )** that captures what the user typed and returns the first 10 characters using the **substring( )** method. This function is exported to the **index.js** file, which adds a listener to the text box that calls the **getDescription( )** function everytime something is typed. Those characters are passed to the property **textContent** of the **output** constant, which represents the area below the text box.

# Executing the project
Since this project is not using the HTTP protocol, requiring to be run it from a local server, the easiest way I found to execute it was as follows:

1. Download and install Visual Studio Code
2. Click the gear icon and select "Extensions"
3. In the search box, type "Live Server" and select it when it appears
4. When a new window opens, click to install the extension
5. In the "Explorer" tab, click the "Open Folder" button and select the folder of the project
6. On the bottom right corner of the screen, find the "Go Live" text and click it
7. When you do that, the project will be opened in your main browser
8. Whenever you want to quit, you can simply click the same corner, now with the port number written on it, and the server will be terminated


This feature provided by Visual Studio Code is basically a local server you can launch to execute your applications and test them without complications. It's mainly for developers, but I found it an interesting way to allow the execution of this particular application.
