# Planner
The purpose of this program is to provide the user with an easily understandable interface that allows them to fill in a daily planner with text. The planner is divided into segments according to the hour of the day (between 9am and 5pm), and each hour's row contains an input field and a clickable save button. Using a third-party API called moment.js, the current date is displayed at the top of the screen and the background of each input field changes color depending on whether or not it is in the past, present, or future. To achieve this, jQuery is used to dynamically adjust the CSS of each input field when it is compared to the time provided by moment.js. Similarly, jQuery is used to give functionality to the save buttons and, upon clicking, they grab the user input and save it to the local storage. To display the saved content, we loop through each row and retrieve the data with .getItem.

# Link to deployed application:


# Planner Screen:
 <img src="https://github.com/Gavin56/planner/blob/main/plannerMain.png?raw=true" alt="Planner Full Screen" width="400"/>
