Yeragam Organics Website

Project Overview

Yeragam Organics is a web-based platform for selling traditional jaggery and sathukkudi (sweet lime) products, crafted from organically-grown sugarcane. This project provides a user-friendly, visually appealing website to promote and facilitate the ordering process for Yeragam Organics' natural products.

The website consists of two main pages: an Index (Home) Page and an Order Page. The Home page introduces users to Yeragam Organics, while the Order page allows users to place orders by filling out a form that collects essential information such as product selection and quantity. Both pages are designed to be responsive, using a natural theme with a green color palette to reflect the organic nature of the products.

Project Features

1. Home (Index) Page
Header: Contains the Yeragam logo and title text styled with shadows to enhance visibility.
Product Showcase: Displays images of products with descriptive overlays and an "Out of Stock" badge for items that are temporarily unavailable.
Footer: Includes basic contact information and a link to the Order page.
Styling and Layout: The home page utilizes a clean, natural theme with a mix of green and white, giving a fresh look that aligns with Yeragam's organic branding.

2. Order Page
Order Form: Collects customer details (Name, Address, Phone Number, Email) and lets them choose a product and quantity.
Product Selection and Dynamic Quantity Input:
Users can select either "Jaggery," "Sathukkudi," or "Both" in the product dropdown menu.
Depending on the selection, specific quantity input fields appear to allow customers to specify their desired amount.
Total Price Calculation: A JavaScript function calculates the total price based on the product and quantity selected, which updates dynamically as the user changes inputs.
Price Verification Checkbox: Ensures customers verify the total amount before placing an order, requiring them to confirm the price via a checkbox.
Submission to Google Sheets: When the form is submitted, the data is sent to a Google Sheets script URL, which collects and stores all order information.
Confirmation Popup: After a successful form submission, a popup thanks the user for ordering.
