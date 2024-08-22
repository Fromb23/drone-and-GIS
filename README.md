# Drone and GIS Company Website

## Application Overview

### Purpose
The Drone and GIS Company website is designed to provide comprehensive information about the company’s services, success stories, and other offerings in the field of drone technology and GIS (Geographic Information Systems). The site serves as both a marketing tool and a functional platform where clients can interact with various services, request specific projects, and access relevant training and news updates.

### Features
- **Home Page**: Featuring the company logo, slogan, and easy navigation to key sections.
- **Definitions**: An informative section explaining key Drone and GIS terminologies.
- **Story Maps**: Interactive story maps showcasing past drone projects.
- **Success Stories**: Highlighting successful projects by industry or sector.
- **Services Menu**: A detailed list of services with interactive selection and costing tools.
- **Service Request Form**: Allows users to request specific services and calculate costs dynamically.
- **Calendar**: Integrated calendar for service scheduling.
- **Payment Integration**: Secure online payment options for service bookings.
- **Media Section**: Videos and images related to services rendered and available drones.
- **GIS Training**: Information on GIS training and online courses.
- **News Updates**: Regularly updated news section.
- **Feedback and Contact**: Private feedback form, social media links, and contact information.

## Technology Stack

### Front-End
- **HTML/CSS**: Standard markup and styling to create the layout and design of the website.
- **JavaScript**: Used for interactivity, such as form validation and dynamic content display.
- **Bootstrap** (optional): For responsive design and pre-styled components.

### Back-End
- **Django (Python)**: The primary web framework used to develop the site, handle routing, form submissions, and manage content.
  - **Django Templates**: Used to render HTML pages dynamically with data from the back-end.
  - **Django Forms**: To create and manage forms (e.g., service request forms).
- **MySQL**: The database management system used to store data such as user submissions, service requests, payment details, and feedback.

### Hosting & Deployment
- **Web Server**: The site can be hosted on services like AWS, Heroku, or DigitalOcean using Gunicorn as the WSGI server.
- **SSL Certificate**: To ensure secure data transmission, especially for handling payment information.
- **Domain Name**: The website will be accessible through a custom domain name.

## Application Structure

### Directory Layout
