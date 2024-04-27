# Flo's Cafe: Mobile Coffee Shop Platform
## Overview
Flo's Cafe is an innovative web platform designed for a mobile coffee shop that enables users to order coffee for delivery or book events, similar to services like Uber Eats. This repository houses the full-stack development project, including front-end enhancements and backend integrations, developed to provide a seamless, user-friendly experience for coffee enthusiasts.

## Technical Stack
- **Frontend**: HTML5, CSS3, JavaScript (ES6)
- **Backend**: Node.js (Express framework for routing and middleware)
- **Database**: MongoDB (NoSQL database for flexible data handling)
- **APIs**: Integration with EmailJS for email dispatching, Google Maps for location services
- **Frameworks/Libraries:**
   * Bootstrap v5: Ensures responsive and modern design
   * Handlebars: For HTML templating
   * Flickity: Touch, responsive, flickable carousels
  * Isotope: Filter & sort magical layouts
   * ImagesLoaded: Manage image loading
  * Lightbox: Overlay images on the current page
- **Others:**
  * Webpack for asset bundling
  * npm for package management

## Key Features
- Responsive Design: Utilizing Bootstrap v5, the site is fully responsive, ensuring that it performs flawlessly across all devices and screen sizes.
- Sorting and Searching: Custom algorithms are implemented to sort coffee products by popularity and price, enhancing the browsing experience.
- Event Booking: Users can easily book for events through a streamlined reservation system.
- Real-time Updates: Leveraging Node.js, the site provides real-time updates on order status and event bookings.

## Enhancements from Template
The original Touche template provided a great starting point with features like a dark mode toggle, a Mailchimp-powered newsletter, and pre-designed sections for various needs. Here are enhancements specific to Flo's Cafe:

- Custom Backend: Developed a custom Node.js backend to replace the template's contact and reservation functionality, improving performance and scalability.
- Dynamic Sorting: Enhanced the user interface with dynamic sorting capabilities for products based on popularity and price using JavaScript and Node.js.
- Design Overhaul: Conducted a complete design overhaul to align with Flo's Cafe branding, including custom graphics and an updated color scheme to enhance visual appeal.

## Project Structure
```lua
/flos-cafe
|-- /src
|   |-- /scripts
|   |-- /styles
|   |-- /images
|   |-- index.html
|-- /dist
|-- /node_modules
|-- server.js
|-- package.json
|-- README.md
```
## Setup and Launch
To get the platform running locally:

1) Clone the repository:
```bash
git clone [https://github.com/SNMeans/FullStack-CoffeeShop]
cd flos-cafe
```
2) Install Dependencies
```bash
npm install
```
3) Start the Server
``` bash
npm start
```
4) Navigate to http://localhost:3000 in your browser to view the site.

## Future Enhancements
- Integration of AI for personalized recommendations: Plan to leverage machine learning to offer personalized coffee and event recommendations based on user preferences.
- Expansion of payment options: Include more diverse payment methods to accommodate a broader user base.

## Conclusion
This project highlights my ability to integrate multiple technologies to create a comprehensive, user-friendly service. Flo's Cafe is poised to transform how coffee lovers interact with mobile coffee services, making it easier than ever to enjoy their favorite brews or plan coffee-themed events.

