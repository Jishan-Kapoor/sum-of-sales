# Sales Total Calculator

## Summary
This static web application calculates the total sales amount from a given CSV file and displays it in the `#total-sales` element on the page.

## Setup
1. Clone this repository to your local machine.

2. Upload your CSV file with a Sales column to the project directory.

3. Commit your changes and push them to your GitHub repository.

4. Go to the "Settings" of your GitHub repository.

5. Scroll down to the "GitHub Pages" section.

6. Under "Source," select the branch where your code is located (usually `main`).

7. Click on the generated link to access the page.

## Usage
- Access the page by clicking [here](#) after deploying on GitHub Pages.
- No specific query parameters or configuration options are required.
- Key Feature: The app automatically calculates and displays the total sales amount from the CSV file.

## Code Explanation
This web app uses HTML, CSS, and JavaScript to read the CSV file and sum the values in the Sales column. Here's a simple overview:

```html
<body>
    <div id="total-sales"></div>
    <input type="file" id="fileInput" accept=".csv" />
</body>
<script src="script.js"></script>
```

Key Libraries:
- PapaParse: Used for parsing CSV files in JavaScript.

Important Logic:
1. Selecting the CSV file using an input element.
2. Parsing the CSV file and summing the values in the Sales column.
3. Displaying the total sales amount in the `#total-sales` element.

## License
This project is licensed under the MIT License.