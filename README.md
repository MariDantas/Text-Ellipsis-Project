# Text Ellipsis Project

This project was created in collaboration with the Learn JavaScript website to help understand how string methods work in JavaScript, with a particular focus on the **substring()** method.

In the **helpers.js** file, there's a function called **getDescription()** that captures user input and returns the first 10 characters using the **substring()** method. This function is then exported to the **index.js** file, which attaches a listener to the text box, invoking **getDescription()** every time the user types something. The resulting characters are assigned to the **textContent** property of the **output** constant, representing the area below the text box.

# Executing the Project
As this project doesn't use the HTTP protocol and requires running on a local server because of the modules, I recommend the following steps for execution:

1. Download and install Visual Studio Code.
2. Click the gear icon and select "Extensions".
3. In the search box, type "Live Server" and select it from the search results to install the extension.
4. After installation, a new window will open; click the "Open Folder" button in the "Explorer" tab and select the project folder.
5. On the bottom right corner of the screen, locate the "Go Live" text and click it.
6. This will open the project in your default web browser for testing and execution.
7. To stop the server, simply click the same corner where the port number is now displayed, and the server will terminate.


Visual Studio Code's "Live Server" feature acts as a local server, providing an easy way to execute and test applications without any complications. Although mainly intended for developers, I found it an interesting and useful tool for running this particular application.
