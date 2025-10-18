# AirBnB Clone Project
This web app is a clone of the popular application AirBnB. The project aims to recreate the main features of the application, allowing users to browse properties and make bookings.

##Project Goals

1.  **Property Browsing:** Allow users to browse a collection of property listings via a responsive interface.
2.  **Detailed Viewing:** Enable users to select a specific property to view a detailed description, photo gallery, location, and host information.
3.  **Booking Functionality:** Implement a complete booking workflow, including selecting dates, viewing pricing, and completing a reservation.

##Tech Stack

| Technology | Purpose |
| :--- | :--- |
| **React** | JavaScript library for building the user interface. |
| **Tailwind CSS** | CSS framework for rapid and responsive styling. |

## UI/UX Design Planning

A successful booking platform relies heavily on a smooth, intuitive, and visually appealing user experience (UX). This section outlines the design philosophy and the core UI components for the AirBnB clone.

### Design Goals

1. **Easy Navigation:** Users can find and book properties quickly with simple, predictable navigation.  
2. **Modern Design:** Clean, photo-focused layout that highlights properties beautifully.  
3. **Fully Responsive:** Works smoothly across desktop, tablet, and mobile devices.  
4. **Clear & Transparent:** Pricing, availability, and host details are easy to read and trustworthy.  

### Key Features to Implement

| Feature Category | Key Features |
| :--- | :--- |
| **Search** | Search bar, date pickers, location filters and map view. |
| **Property Management** | Create, view, update and delete property listings. |
| **Booking & Checkout** | Availability calendar, price calculation, payment integration and booking confirmation. |
| **User Profile** | View and manage past bookings, update personal information. |

### Primary Page Descriptions

| Page Name | Description | Key UI Components |
| :--- | :--- | :--- |
| **Property Listing View** | Main page where users search, browse, and filter properties.| Search bar, filter bar, property cards (image, title, location, rating, price) and load more. |
| **Listing Detailed View** | Displays full details for a selected property. | Photo gallery, booking widget (dates, guests, price), description, amenities, host info, reviews and reservation link. |
| **Simple Checkout View** | Page to review and complete the booking.| Booking summary, payment form, payment terms and confirmation button. |

### Importance of User-Friendly Design in a Booking System

A user-friendly design is **critical** for a booking platform because it directly impacts conversion rates and user retention.

* **Smooth Experience:** Clear navigation and simple steps help users find properties, select dates, and book without frustration.
* **Trustworthy Interface:** A clean, professional design with clear pricing, policies, and reviews builds confidence in the platform.
* **Improves Experience:** Fast, responsive, and visually appealing pages make booking enjoyable and encourage repeat use.

### Figma Design Specifications
**Color Styles**
* Primary: Lochinvar #34967c
* Secondary: Web Orange #ffa800
* Background: Gallery #ededed
* Text: Bastille #151117
* Secondary Text: Mercury #eaeaea

**Typography**
* Primary: Family - Quicksand, Weight - 500, Size - 23px
* Secondary: Family - Quicksand, Weight - 500, Size - 20px
* Headings: Family - Quicksand, Weight - 700, Size - 31 to 50px

## Project Roles and Responsibilities

| Role | Key Responsibilities  |
| :--- | :--- |
| Product Owner | <ul><li>Defines and prioritizes the product backlog.</li><li>Articulates the product vision and goals.</li><li>Accepts or rejects completed work.</li><li>Ensures the team is building the right product that delivers maximum business value and meets user needs.</li></ul> |
| Scrum Master | <ul><li>Facilitates Scrum ceremonies (e.g., daily stand-ups, sprint planning).</li><li>Removes impediments (e.g., technical blockers, resource issues).</li><li>Coaches the team on agile principles.</li><li>Improves team efficiency and communication, ensuring a smooth development flow and adherence to process.</li><ul>|
| Project Manager | <ul><li>Manages the project timeline, budget, and scope.</li><li>Coordinates communication across all roles and stakeholders.</li><li>Identifies and mitigates project risks.</li><li>Ensures the project is delivered on time and within budget by managing resources and expectations.</li></ul> |
| Frontend Developers | <ul><li>Implement the UI/UX design using React and styling (e.g., property cards, detailed views).</li><li>Integrate with the backend API using Axios/Fetch.</li><li>Ensure the application is fully responsive and performs well.</li><li>Creates a smooth, fast, and visually appealing user experience, which is critical for user retention in a booking app.</li></ul> |
| Backend Developers | <ul><li>Design and build the RESTful APIs.</li><li>Manage data storage, retrieval, and security (authentication, authorization).</li><li>Implement core business logic (e.g., booking validation, price calculation).</li><li>Provides the secure and scalable foundation that enables all core functionality and reliable data management.</li></ul> |
| Designers (UI/UX) | <ul><li>Create the visual mockups and prototypes (as defined in the ""UI/UX Planning"" section).</li><li>Develop the style guide (colors, typography).</li><li>Conduct user research and testing.</li><li>Ensures the application is intuitive, aesthetically pleasing, and meets user needs from a usability standpoint.</li></ul> |
| Quality Assurance/Testers | <ul><li>Develop and execute test plans (unit, integration, end-to-end).</li><li>Identify, document, and track bugs and defects.</li><li>Verify that new features meet the acceptance criteria.</li><li>Guarantees the quality and reliability of the application, ensuring a bug-free and trustworthy booking experience.</li></ul> |
| DevOps Engineers | <ul><li>Set up and maintain CI/CD pipelines (automated testing and deployment).</li><li>Manage cloud infrastructure (hosting for frontend, backend, and database).</li><li>Monitor application performance and security post-deployment.</li><li>Enables rapid, consistent, and reliable deployment of new features to production environments.</li></ul> |

## UI Component Patterns

**Navbar:** A sticky header that appears on all pages. It includes Links to log in and sign up and search functionality. It has:
<ul>
  <li>Logo</li>
  <li>Search component</li>
  <li>Authentication links</li>
</ul>

**Property Card:** A component used to display a property summary in the listing view. It has:
<ul>
  <li>Property image</li>
  <li>Property details</li>
  <li>Review</li>
  <li>Price</li>
</ul>

**Footer:** The bottom section of the page containing:
<ul>
  <li>Links to legal pages</li>
  <li>Contact information</li>
  <li>Help links</li>
  <li>Quick links</li>
</ul>

**Search:** A dedicated section or modular form that allows users to input search criteria and apply filters. It has:
<ul>
  <li>Input for location</li>
  <li>Date pickers</li>
  <li>Input for number of guests</li>
</ul>

**Review Card:** A component used to display reviews from past customers. It has:
<ul>
  <li>User's image</li>
  <li>User and trip details</li>
  <li>Review</li>
  </ul>
