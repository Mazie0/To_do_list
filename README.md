# To_do_list
TITLE: CodTech IT Solutions Internship - Task Documentation: “To-DO LIST” Using CSS, HTML, JAVASCRIPT.
INTERN INFORMATION: 
Name: Sai Kumar Thota
ID: ICOD6501
INTRODUCTION
Regarding personal productivity and organising tools, the to-do list is a mainstay, widely acknowledged for its ease of use and efficiency in handling chores and priorities. The transition from paper-based to digital platforms has greatly increased the usefulness and accessibility of to-do lists, making them an essential resource for anyone trying to effectively manage their obligations and maximise their free time. Through the creation of a To-Do List application, this project seeks to further innovate in this field by leveraging the capabilities of contemporary web technologies, such as HTML, CSS, and JavaScript. 

The shift to digital to-do lists has created a wealth of opportunities for accessibility across devices, real-time collaboration, and customisation. Even if the market is filled with many applications, there is still a good chance to build a tool that is more adaptable, intuitive, and meets the wide range of needs of users. The goal of this project is to provide a better task management experience by utilising web technologies' adaptability and JavaScript's capabilities.

Implementation
	JavaScript Framework: Utilize a modern JavaScript framework for building the frontend application.
	HTML/CSS: Use HTML5 and CSS3 for structuring and styling the user interface, ensuring compatibility with various web browsers.
	Responsive Design: Implement responsive design principles to ensure optimal viewing experience across desktop and mobile devices.
	User Interface Components: Utilize UI libraries for designing interactive and visually appealing components.



CODE EXPLAINATION
Sure, I’d be happy to explain the code you’ve provided. It’s a simple To-Do List application built with HTML, CSS, and JavaScript.
HTML: The HTML structure of the application is quite straightforward. It consists of a container div that holds the entire To-Do List application. Inside this container, there’s a div with the class todo-app that contains an h2 element for the title, a div for the input row, and an ul for the list container.
CSS: The CSS code is used to style the HTML elements. It sets the font, colors, sizes, and other visual properties of the elements. For example, it sets the background color of the container, the size and color of the text, and the appearance of the input box and button.
JavaScript: The JavaScript code is where the functionality of the To-Do List application is implemented. Here’s a breakdown of what each function does:
•	addTask(): This function is called when the “Add” button is clicked. It creates a new li element, sets its innerHTML to the value of the input box, and appends it to the list container. It also creates a span element that serves as the delete button for each task.
•	Event Listener on listContainer: This event listener is set on the listContainer. If a list item (li) is clicked, it toggles the checked class which strikes through the text. If the delete button (span) is clicked, it removes the parent list item.
•	saveData(): This function is called after a task is added, checked off, or deleted. It saves the current state of the list container to the local storage.
•	showTask(): This function is called when the page loads. It retrieves the saved tasks from local storage and displays them in the list container.
USAGE
1.	Add a Task: Enter the task in the input field labeled “Add your text” and click the “Add” button. The task will appear in the list below.
2.	Mark a Task as Completed: Click on a task in the list to mark it as completed. A line will appear through the text of the task, indicating that it is completed.
3.	Delete a Task: Each task has a small ‘x’ on the right. Click on the ‘x’ to delete the task from the list.
Technical Details: The app is built with HTML, CSS, and JavaScript. The HTML defines the structure of the app, the CSS styles the app, and the JavaScript provides the functionality. The JavaScript code uses local storage to save the state of the task list, so your tasks will still be there even if you refresh the page or close and reopen your browser.

COCLUSION
The To-Do List App is a simple, user-friendly, and efficient tool for managing tasks. It’s built with standard web technologies (HTML, CSS, and JavaScript), making it accessible on any device with a web browser. The app provides essential features for task management, including adding tasks, marking tasks as completed, and deleting tasks. It leverages the local storage of the browser to persist data across sessions, providing a seamless user experience. However, as a client-side application, it’s important to note that the data is not backed up on a server and clearing the browser’s local storage will result in loss of data.
OUTPUT
 



 

