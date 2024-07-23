# Module_01_PHIBOG534_jse2407_c_Phillip-Bogopane_JSF01

#SwiftCart
SwiftCart is a modern, responsive web application for browsing and shopping products online. It offers features such as product search, filtering, sorting, and viewing detailed product information in a modal. All product data is fetched from an external API.

#Table of Contents
Introduction
Technologies Used
Setup Instructions
Usage
Features

#Introduction
SwiftCart is a single-page application built with HTML, Tailwind CSS, and Alpine.js. It provides users with a seamless shopping experience by allowing them to browse products, view detailed product information in modals, and filter and sort products dynamically. The application fetches all its data from the Fake Store API, ensuring real-time updates and dynamic content.

Technologies Used
HTML5: For structuring the web page.
Tailwind CSS: For styling and making the application responsive.
Alpine.js: For handling the application's interactivity and state management.
JavaScript Fetch API: For making HTTP requests to fetch product data.
Setup Instructions
To set up the project locally, follow these steps:

Clone the repository:
bash

git clone https://github.com/your-username/swiftcart.git
Navigate to the project directory:
bash

cd swiftcart
Open index.html in your preferred browser:
bash

open index.html

#Usage
Once the project is set up, you can use the application as follows:

View Products: Upon opening the application, a grid of product cards will be displayed. Each card shows an image, title, price, and category of the product.
Search Products: Use the search bar to find products by title.
Filter Products: Use the category dropdown to filter products by category.
Sort Products: Use the sorting dropdown to sort products by price (low to high, high to low).
View Product Details: Click on a product card to open a modal with detailed information about the product, including the title, description, image, price, category, and rating.
Close Modal: Click outside the modal or use the close button to return to the product grid.
Features

#As a User:
Browse Products: View a grid of product cards, each displaying:
Product image
Product title
Product price
Product category

#View Detailed Product Information: Click on a product to open a modal showing:
Product title
Product description
Product image
Product price
Product category

#Product rating and number of reviews
Close Modal: Close the modal to return to the product grid.
Loading States: See a loading state while initial data and new data are being fetched.
Filter by Category: Filter products by category.
Sort by Price: Sort products by lowest and highest price.
Reset Filters and Sorting: Return to default filtering and sorting without refreshing the application.
Persistent Filters and Sorting: Applied filters and sorting persist after opening and closing the modal.