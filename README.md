# TaskPlanner
A basic task planner using ReactJs


# Design

The landing page of the website asks the user to enter the user’s name and the employee type that best describes their position. The user can either choose “Employee” or “Manager/Supervisor”. This was done to create a customized view based on the user’s needs as obtained from the survey data and the designed personas.

The task organizer page is designed based on many existing task management software such as Trello and Monday.com. This will create a more familiar view to the user thereby improving the learnability of the system. It will also positively impact their performance and overall satisfaction of the system.

The top left corner of the screen has “Create New Category” button which the user can click on as many times as they need. Each time the button is clicked, a category is created with a single task line. This design decision was implemented instead of creating a category after a user types a category name and clicks a button. It will allow for categories to be reused which can ultimately speed the process of organizing tasks for the user and increase their performance. The category name will initially be an empty input field that the user can modify at any time they want without having to recreate the category and the associated items. The user can also add rows to the category as they see fit by clicking on “Add Row” located at the bottom of each category container. In addition to that, for each row created, a “Delete” button is shown so that the user can delete individual lines. All the mentioned features give the impression that the software is flexible enough to give the user control over their task management process.

For each category created an “X” delete button is placed in the top right corner of the container. The choice of designing it as an “X” instead of a regular button was solely to avoid confusion between it and the delete button for the row. A tooltip was also added to inform the user that the “X” will delete the category. In addition to that, the category was implemented with a collapsible container to expand and shrink the category details. This will help the user focus only on the category they are currently working on and potentially enhancing the user’s satisfaction. 

In “Manager/Supervisor” view, the priority column is a color-coded dropdown with options as Low, Medium, High, and Critical. For example, the low priority is colored green, medium is colored yellow, high is colored red, and critical is colored crimson. Once the user selects a priority, the associated color will be displayed in the dropdown’s background color for the user to see at all times. Color coding severity will help the user visualize it better and act accordingly. This will improve the user’s overall performance. It was also designed based on Color-Coding guidelines in Research-Based Web Design & Usability Guidelines which stated that “when using color-coding on your Web site, be sure that the coding scheme can be quickly and easily understood”, which I believe was accomplished in this case [3]. 

One additional feature that was added to the task organizer was sorting for each of the columns associated with a task. Sorting was implemented for both views of the system to help users reorder tasks associated with categories as they see fit. This will give the user a better control over their task organizer.

# How to run the application
To run the web application, simply download the files in the repo and open index.html from any browser (preferrably Chrome).
