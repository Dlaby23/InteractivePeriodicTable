# InteractivePeriodicTable
This code implements an interactive periodic table application using JavaScript, HTML, and CSS, allowing users to explore and view information about chemical elements.

# Interactive Periodic Table
The code consists of three files: index.js, main.html and style.css. Together, they create an interactive periodic table that's running on website. The application loads element data from a JSON file hosted on github and displays all information about the element when interacting with the element.

# JavaScript (index.js)
-Variables
main: Represents the <main> element in the HTML document.
categories: An array containing different categories of chemical elements.
activeElement: Represents the currently selected element in the periodic table.
  
# Function: loadElements()
This function loads element data from a JSON file using the XMLHttpRequest.

# Function: outputElements(elements)
Generates the periodic table by creating slot for each category. The function also adds click event to display information and highlight the selected element.
  
# Function: showInfo(element)
It shows all the information found in the Json file and writes it to the generated table.
  
# Events
Click event on each table element: When a table element is clicked, it removes the focus class from the previously selected element and adds the focus class to the clicked element, then it updates the activeElement variable and calls 'ShowInfo'. Element is then called and all informations are writen in the table bellow

# HTML (main.html)
The HTML file represents the structure of the web page. It contains the <main> element that holds the periodic table and the <article> element that displays detailed information about the selected chemical element.

# CSS (style.css)
The CSS file contains styles for the elements in the web page, including the periodic table and the information article. It defines the layout, colors, and animations for the elements.
  
# Conclusion
This documentation provided an overview of a web application built with React using Typescript. The application displays the periodic table of elements by reading data from a JSON file. The application is responsive and can be used on various devices and platforms. The application uses few components like: loadElements, outputElements, ShowInfo to display the periodic table and its properties. The data is stored in a JSON file located in repository on Github.

  
UML DIAGRAM:  
+-----------------+        +-----------------+        +------------------------+
|     index.js    |        |    main.html    |        |       style.css        |
+-----------------+        +-----------------+        +------------------------+
|    JavaScript   |        |     HTML/CSS    |        |       CSS Styles       |
|      code       |        |     Markup      |        |   Styling definitions  |
|                 |        |   Structure     |        |                        |
|   - Functions   |        |  - Main layout  |        |                        |
|   - Variables   |        |  - Element info |        |                        | 
|   - Event       |        |   display area  |        |                        |
|     listeners   |        |                 |        |                        |
+-----------------+        +-----------------+        +------------------------+
