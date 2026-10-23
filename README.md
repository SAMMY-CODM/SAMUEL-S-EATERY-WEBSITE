# Samuel's Eatery Restaurant Website

## 1. Project Overview
Samuel's Eatery is a restaurant website created as a front-end web design project. It is built with HTML, CSS, and JavaScript and follows the dark, low-fidelity wireframe style shown in the Figma prototype. The design uses a black background, thin outlined panels, compact navigation links, rectangular content areas, food photography, and a consistent footer.

The website is intended to help visitors learn about the restaurant, browse the menu, understand available services, make an order enquiry, and contact the restaurant.

## 2. Project Goals
- Present information about Samuel's Eatery in a clear and organised way.
- Reproduce the layout and structure of the six-page Figma prototype as closely as practical in a responsive website.
- Make the header navigation and page links clickable.
- Include food and restaurant images to replace some of the image placeholders in the wireframe.
- Provide menu, order, and contact interactions for demonstration.
- Keep the website code easy to edit in Visual Studio Code.

## 3. Files and Their Purpose
- `index.html` — Home page; introduces Samuel's Eatery and links visitors to other parts of the site.
- `about.html` — About page; explains the restaurant's story, purpose, mission, vision, and values.
- `menu.html` — Menu page; displays sample meals, descriptions, prices, images, and menu categories.
- `services.html` — Services page; describes dining, order enquiries, and group-meal services.
- `order.html` — Order page; contains a form for customer details and order information.
- `contact.html` — Contact page; displays contact information and a message form.
- `style.css` — Shared styling for the dark theme, typography, borders, layouts, cards, images, responsive behaviour, and footer.
- `script.js` — JavaScript interactions, including the mobile navigation toggle, active navigation link, current year in the footer, and demo form feedback.
- `README.md` — Project documentation and instructions.

## 4. Technologies Used
### HTML
HTML provides the structure of each page. Semantic elements such as `header`, `nav`, `main`, `section`, `form`, and `footer` organise the content. Links connect the six pages.

### CSS
The shared `style.css` file controls the visual appearance. It creates the dark background, light text, outlined rectangular panels, spacing, menu cards, form fields, food-image areas, and shared footer. Responsive rules help the layout adapt to smaller screens.

### JavaScript
The `script.js` file adds client-side behaviour. It toggles the navigation menu on smaller screens, marks the current page in the navigation, updates the footer year automatically, and shows a confirmation message when a demo form is submitted.

## 5. How the Website Works
1. When a visitor opens `index.html`, the Home page is displayed.
2. The header contains links to Home, About, Menu, Services, Order, and Contact. Selecting a link opens the corresponding HTML page.
3. Each page shares a common header style and footer so the site feels consistent.
4. The Menu page presents example dishes and food images to help visitors explore the restaurant's offerings.
5. The Order page allows a visitor to enter their name, phone number, meal/order details, and other information.
6. The Contact page allows a visitor to enter their contact details and message.
7. JavaScript prevents the demonstration forms from reloading the page and displays an on-screen confirmation message.
8. The CSS responsive rules adjust layouts for desktop, tablet, and mobile screen sizes.

## 6. Design and Relationship to the Figma Prototype
The Figma prototype uses a dark, wireframe-inspired design. The website translates that visual direction into working web pages by using:
- A black/dark page background.
- Thin grey or light borders around major sections and cards.
- Compact uppercase headings and navigation labels.
- Rectangular image and content areas.
- Clear page titles and grouped information.
- A consistent footer with quick links and restaurant details.
- Food and restaurant photographs to make the prototype more realistic.

The website is an implementation inspired by the supplied prototype; exact pixel-for-pixel matching can vary with screen size, browser, font loading, and image availability.

## 7. How to Open the Website in Visual Studio Code
1. Extract the project ZIP file into a folder on your computer.
2. Open Visual Studio Code.
3. Select **File → Open Folder**.
4. Choose the extracted `Samuels_Eatery_Website_Color` project folder.
5. Check that the HTML files, `style.css`, and `script.js` are in the same folder.
6. Open `index.html`.
7. For local preview, install the **Live Server** extension if it is not already installed.
8. Right-click `index.html` and choose **Open with Live Server**. The website should open in your browser.
9. Use the header links to test all six pages.

You can also open `index.html` directly in a browser, but Live Server is convenient while editing because it refreshes the preview when files change.

## 8. How to Edit the Website
- Edit page headings, paragraphs, sample dishes, and links in the relevant `.html` file.
- Change colours, borders, spacing, and layout in `style.css`.
- Change navigation and form behaviour in `script.js`.
- To change a picture, replace its image URL in the relevant HTML file with another image URL or a local image path.
- Update sample restaurant contact details and menu prices before presenting or publishing the website.

## 9. Important Limitations
- The order and contact forms are demonstration forms. They show a confirmation message in the browser but do not send information to a restaurant, email address, or database.
- The food images are loaded from Unsplash URLs, so an internet connection is needed for those images to appear.
- Menu items, prices, opening hours, phone numbers, and email addresses are sample content and should be verified and replaced with the restaurant's actual information before publication.
- The website is a front-end project. A live restaurant service would need a back-end or form service to receive and manage orders and contact messages.

## 10. Conclusion
Samuel's Eatery demonstrates how a Figma wireframe can be translated into a multi-page website using HTML, CSS, and JavaScript. Its six pages provide a clear navigation structure, a consistent dark design, restaurant imagery, and basic interactive demonstrations. The project can be opened and edited in Visual Studio Code and can later be extended with real order processing and contact functionality.
