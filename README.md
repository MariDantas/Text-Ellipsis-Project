# Text Ellipsis Project

This project was set by the Learn JavaScript website in order to learn how string methods work in JavaScript. The focus here is the **.substring( )** method.

In the **helpers.js** file, there's a function named **getDescription( )** that captures what the user typed and returns the first 10 characters using the **substring( )** method. This function is exported to the **index.js** file, which adds a listener to the text box that calls the **getDescription( )** function everytime something is typed. Those characters are passed to the property **textContent** of the **output** constant, which represents the area below the text box. And that's how the text is shown below the text box.
