# InteractivePeriodicTable
This code implements an interactive periodic table application using JavaScript, HTML, and CSS, allowing users to explore and view information about chemical elements.
The code consists of three files: index.js, main.html and style.css. Together, they create an interactive periodic table that's running on website. The application loads element data from a JSON file hosted on github and displays all information about the element when interacting with the element.

## JavaScript (index.js)
Variables <br/>
Main: represents the "main" element in the HTML document. <br/>
Categories: An array containing different categories of chemical elements. <br/>
ActiveElement: Represents the currently selected element in the periodic table. <br/>
  
## Function: loadElements()
This function loads element data from a JSON file using the XMLHttpRequest.

## Function: outputElements(elements)
Generates the periodic table by creating slot for each category. The function also adds click event to display information and highlight the selected element.
  
## Function: showInfo(element)
It shows all the information found in the Json file and writes it to the generated table.
  
## Events
Click event on each table element: When a table element is clicked, it removes the focus class from the previously selected element and adds the focus class to the clicked element, then it updates the activeElement variable and calls 'ShowInfo'. Element is then called and all informations are writen in the table bellow

## HTML (main.html)
The HTML file represents the structure of the web page. It contains the "main" element that holds the periodic table and the <article> element that displays detailed information about the selected chemical element.

## CSS (style.css)
The CSS file contains styles for the elements in the web page, including the periodic table and the information article. It defines the layout, colors, and animations for the elements.
  
## Conclusion
This documentation provided an overview of a web application built with React using Typescript. The application displays the periodic table of elements by reading data from a JSON file. The application is responsive and can be used on various devices and platforms. The application uses few components like: loadElements, outputElements, ShowInfo to display the periodic table and its properties. The data is stored in a JSON file located in repository on Github.

  
## UML DIAGRAM
  ![image](https://github.com/Dlaby23/InteractivePeriodicTable/assets/107836719/9fadbcff-7ce7-49bc-90f3-d92a5e38d042)

