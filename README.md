Ristorante Con Fusion

A responsive restaurant website originally developed as part of a Coursera web development course and later revisited and modernized as a personal learning project.

The project was originally built to practice responsive web design, Bootstrap components, navigation, forms, carousels, accordions, and basic front-end development. I later returned to the project to update its dependencies and bring the application forward to Bootstrap 5 while preserving the original visual style and much of the original implementation.

Features

Responsive navigation bar

Active navigation states for each page

Responsive restaurant header

Bootstrap carousel showcasing restaurant dishes

Restaurant promotions and featured dishes

Reservation form

About Us page

Corporate leadership accordion

Restaurant facts and figures table

Contact and feedback form

Location and contact information

Social media buttons

Responsive layout for desktop and mobile screens

Font Awesome icons

Pages
Home

The home page introduces Ristorante Con Fusion and includes:

Restaurant introduction

Featured dishes

Promotional content

Culinary specialist information

Image carousel

Reservation form

About Us

The About Us page contains:

Restaurant history

Restaurant facts

Company leadership

Bootstrap accordion for the leadership team

Facts and figures table

Restaurant quotation

Contact Us

The Contact page contains:

Location information

Contact details

Phone, Skype and email buttons

Customer feedback form

Social media links

Technologies Used

HTML5

CSS3

Bootstrap 5.3

Font Awesome

JavaScript

npm

Lite Server

Bootstrap Migration

This project originally used an older version of Bootstrap as part of the course material.

As part of revisiting the project, I upgraded the application to Bootstrap 5.3 while keeping the original design and overall structure as much as possible.

Some of the older Bootstrap dependencies and conventions were removed or replaced, including:

Bootstrap 4-era JavaScript usage

jQuery dependency for Bootstrap components

Separate Popper.js dependency

bootstrap-social

Bootstrap 4 form classes and attributes

Bootstrap 5's bundled JavaScript is now used for the application.

Running the Project
1. Clone the repository
git clone https://github.com/fezile-sudo/Bootstrap4.git

2. Open the project directory
cd Bootstrap4/conFusion

3. Install dependencies
npm install

4. Start the development server
npm start


The project uses Lite Server and should be available at:

http://localhost:3000

Project Structure
conFusion/
│
├── css/
│   └── styles-old.css
│
├── img/
│   ├── logo.png
│   ├── uthappizza.png
│   ├── alberto.png
│   └── buffet.png
│
├── node_modules/
│
├── aboutus.html
├── contactus.html
├── index.html
├── package.json
└── README.md

Learning Objectives

This project was originally created to practice the fundamentals of front-end web development, including:

Responsive layouts

Bootstrap grid system

Bootstrap components

Forms

Navigation

Carousels

Accordions

Tables

Responsive images

CSS customization

Basic JavaScript interaction

npm and front-end dependencies

Revisiting the project also provided an opportunity to practice maintaining and modernizing an older front-end project.

Project Status

The project is currently a front-end demonstration project.

It does not include a backend, database, authentication system, or real restaurant reservation system. The forms and reservation interface are primarily intended to demonstrate front-end design and interaction.

Credits

This project was originally developed while following a Coursera web development course.

The project was subsequently revisited and updated as a personal learning exercise to improve familiarity with modern Bootstrap, front-end dependency management, and maintaining an older web project.

License

This project is intended primarily for educational and portfolio purposes.
