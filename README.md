# Sabhyasha-Retail

This project provides a multi-step "Add Product" form with fields for various product details such as name, SKU, category, descriptions, images, variants, pricing, and stock. The data is saved locally using localStorage, and a table dynamically displays saved product information with basic actions.

Features

Multi-Step Form: Form split into logical sections (Basic Details, Descriptions, Media, Variants, Pricing).
Category & Subcategory Selection: Conditional dropdown for subcategories based on selected category.
Local Storage: Saves product details to localStorage for persistent display in the table.
Product Table: Shows added products with essential details and an option to edit.
Dynamic Pricing Calculation: Calculates final price based on base price, discount, and shipping fee.
Responsive UI: Uses Bootstrap for a responsive design.

File Structure

HTML: Defines the form structure, input fields, and table.
CSS: Includes inline styles and Bootstrap for a consistent and responsive layout.
JavaScript: Provides form step navigation, data storage, and display functionality.

Getting Started

Prerequisites

No specific installations are required; the project only needs a web browser.
Running the Project
Download or clone this repository.
Open index.html in a web browser.

How to Use

Navigate Steps: Use "Next" and "Previous" buttons to navigate through form steps.
Input Product Information: Fill out each form section with product details.
Submit Form: On form submission, product data is saved to localStorage and displayed in the table below.
Edit Products: Click on the "Edit" button in the product table to modify an entry.

JavaScript Functions

showStep(step): Displays the specified form step.
nextStep() / prevStep(): Moves to the next or previous form step.
saveProduct(): Saves product details in localStorage.
displayProducts(): Loads and displays saved products in the product table.
calculateFinalPrice(): Calculates the final price based on base price, discount, and shipping fee.

Dependencies

Bootstrap v5.1.3: Used for styling and responsive design.

Notes

The project uses localStorage, so data is stored only in the local browser and not in a server database.
The "Edit" functionality currently loads saved data but does not allow updates.

Future Enhancements

Implement actual edit and delete functionalities for products.
Integrate with a backend server to enable persistent storage across devices.
Add validation messages for enhanced UX.
