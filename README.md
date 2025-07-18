# ASG Control E-commerce Website

This project is a single-page e-commerce website for "ASG Control," a fictional electronics and industrial control components store. The website is built using HTML, Tailwind CSS, and vanilla JavaScript, and it simulates a multi-page experience with category and product detail views.

## Features

- **Fully Responsive Design**: The layout adapts to all screen sizes, from mobile to desktop.
- **Dynamic Page Navigation**: JavaScript is used to switch between different "pages" (Home, Categories, Product Details) without reloading the browser.
- **Product Catalog**: Products are organized into categories and stored in a JavaScript object, acting as a simple database.
- **Detailed Product Pages**: Each product has its own detail page with a larger image, technical specifications, and a description.
- **Product Suggestions**: Product detail pages show a list of similar items from the same category to encourage further browsing.
- **Functional Shopping Cart**:
    - Add items to the cart from category or detail pages.
    - View and manage items in a slide-out cart modal.
    - Update item quantities or remove them from the cart.
    - The total price is calculated automatically.
- **Light/Dark Theme Toggle**:
    - A button in the header allows users to switch between light and dark themes.
    - The theme preference is saved in `localStorage` and persists across sessions.
    - The site defaults to the user's system theme preference on the first visit.
- **RTL Language Support**: The entire site is designed for Arabic with a right-to-left layout and the "Cairo" font for excellent readability.

## File Structure

For the website to function correctly with all images, you must create the following folder structure in the same directory as the `index.html` file:


/ASG Control Website/
|-- index.html
|-- Maroon Mobile Gadgets and Electronics Shop Business Logo (2).jpg
|-- /كونتاكتورات LS/
|   |-- mc-9b.jpg
|   |-- mc-12b.jpg
|   |-- mc-18b.jpg
|   |-- mc-32a.jpg
|   |-- mc-50a.jpg
|   |-- mc-85a.jpg
|   |-- mc-150a.jpg
|   |-- mc-225a.jpg
|
|-- /ريليه حراري 3 فاز من LS/
|   |-- mt-32.jpg
|   |-- mt-63.jpg
|   |-- mt-95.jpg
|
|-- /LS قواطع كهربائية/
|   |-- abn103c.jpg
|   |-- abn203c.jpg
|   |-- abn403c.jpg
|   |-- abn803c.jpg


**Note:** The image names must be exactly as listed above (in lowercase) for the website to find and display them.

## Technologies Used

- **HTML5**: For the structure of the website.
- **Tailwind CSS**: For all styling and layout. It is loaded via a CDN.
- **Vanilla JavaScript**: For all dynamic functionality, including page navigation, cart management, and theme toggling.
- **Google Fonts**: The "Cairo" font is used for the Arabic text.

## How to Use

1.  Save the HTML code as `index.html`.
2.  Create the folders and add the product images and logo as described in the **File Structure** section.
3.  Open the `index.html` file in any modern web browser (like Chrome, Firefox, or Edge).

The website is now ready to be used.
