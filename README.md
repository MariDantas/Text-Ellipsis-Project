# Text Ellipsis Project
<br>

## Description

This project was created in collaboration with the Learn JavaScript website to help understand how strings work in JavaScript. Each version of the project is a new challenge set by the website and, based on that challenge, I keep making small changes to the code.

The general idea is to capture user input with the function ```getDescription()``` and return the first 10 characters using the ```substring()``` method. In the first version, the characters were returned to the **index.js** file, responsible for adding an event listener to the text box and then displaying the characters below the text box. Currently, there's an ```if``` condition verifying if the text is below or equal to 10 characters. If it is, the whole text is returned. If not, the first 10 characters are returned with an ellipsis at the end.

## Executing the Project
As this project doesn't use the HTTP protocol and requires running on a local server because of the modules, I recommend the following steps for execution:

1. Download and install Visual Studio Code.
2. Click the gear icon and select "Extensions".
3. In the search box, type "Live Server" and select it from the search results to install the extension.
4. After installation, a new window will open; click the "Open Folder" button in the "Explorer" tab and select the project folder.
5. On the bottom right corner of the screen, locate the "Go Live" text and click it.
6. This will open the project in your default web browser for testing and execution.
7. To stop the server, simply click the same corner where the port number is now displayed, and the server will terminate.


Visual Studio Code's "Live Server" feature acts as a local server, providing an easy way to execute and test applications without any complications. Although mainly intended for developers, I found it an interesting and useful tool for running this particular application.

## Update History

### Part III
* Now the ellipsis is only displayed when the text has more than 10 characters.

### Part II
* Added ellipsis to the end of the characters returned.

### Part I
* Release of the Text Ellipsis Project, displaying the first 10 characters below the text box.

## Helpful Links
* [Learn JavaScript](https://www.learnjavascript.com/)
* [JavaScript String Methods Documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)
* [Visual Studio Code download](https://code.visualstudio.com/)
