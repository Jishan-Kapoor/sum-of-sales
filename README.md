# Web Application: Regional Sales Filter

## Summary
This static web application provides an interactive interface for visualizing and filtering sales data by region. Users can select a region to filter sales data, and the application dynamically updates the sales summary and highlights the selected region.

## Setup

To deploy this application on GitHub Pages, follow these steps:

1. **Fork the Repository:**
   - Click on the fork button at the top-right corner of the GitHub repository page to create your copy.

2. **Clone the Repository:**
   - Navigate to your forked repository, then clone it using the following command:
     ```bash
     git clone https://github.com/<your-username>/<repository-name>.git
     ```

3. **Navigate to the Directory:**
   - Use the command line to enter the project's root directory:
     ```bash
     cd <repository-name>
     ```

4. **Commit and Push to GitHub:**
   - Ensure all changes are committed and pushed to the main branch:
     ```bash
     git add .
     git commit -m "Initial commit"
     git push origin main
     ```

5. **Enable GitHub Pages:**
   - Go to the repository's settings on GitHub.
   - Scroll to the "GitHub Pages" section.
   - Select the 'main' branch as the source for the GitHub Pages build and save.

## Usage

### Accessing the Page
- Once GitHub Pages is enabled, access the application via: `https://<your-username>.github.io/<repository-name>/`.

### Filtering Options
- **Regions Filter:** Use the selector `#region-filter` to choose a region. This selection filters the displayed sales data.

### Features
- **Dynamic Sum Update:** The element `#total-sales` reflects the total of the filtered sales.
- **Region Highlighting:** The `data-region` attribute is updated according to the region selected in the filter.

## Code Explanation

### Technical Overview
- **HTML:** The structure includes input elements for region selection and a display area for sales data.
- **JavaScript:** Implements the logic for filtering data and updating the display dynamically.

### Libraries and Dependencies
- Vanilla JavaScript is used without additional libraries, ensuring quick load times and simplicity.

### Key Logic
- **Event Listeners:** Event listeners on the `#region-filter` element detect changes and trigger updates.
- **Data Update:** Upon selection, JavaScript recalculates and updates `#total-sales` by summing the relevant sales data.

## License

This project is licensed under the MIT License. For more details, refer to the `LICENSE` file in the project's root directory.