**Overview**

This project is a web-based clone of Microsoft Excel, built entirely using vanilla JavaScript, HTML, and CSS. It replicates some of the core functionalities of Excel, providing users with a powerful and accessible spreadsheet interface directly in their browser. Whether you need to perform simple data entry tasks or complex calculations, this web app offers a familiar and intuitive environment.

**Features**

2D Grid, Rows, Columns, and Sheets: A fully functional spreadsheet grid that allows for easy data input and manipulation across multiple sheets.

Formula and Address Bar: Implemented using pure JavaScript, the formula bar allows users to enter and calculate formulas, with references to cell addresses.

Text Styling: Optional features to change font size, font type, text alignment, and other styling options for enhanced visual presentation.

Algorithmic Formula Handling:

DFS Algorithm: Used for parsing and applying formulas across cells.

Infix Stack Evaluation: Utilized for evaluating the entered formulas, ensuring accurate calculation results.

**Getting Started**

To get started with this project, clone the repository and open the index.html file in your preferred web browser.

**How It Works**

Formula Implementation: The app uses a Depth-First Search (DFS) algorithm to traverse the dependencies of cells when a formula is entered. This ensures that all referenced cells are correctly calculated.

Formula Evaluation: The entered formulas are evaluated using an infix stack evaluation method, allowing for complex mathematical operations to be handled accurately.

**Contributing**

Contributions are welcome! Feel free to submit issues or pull requests to enhance the functionality or fix any bugs.
