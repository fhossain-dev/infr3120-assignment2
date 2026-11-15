
# Personal Portfolio Website - INFR3120 Assignment 2

**Student:** Farhan Hossain  
**Course:** INFR3120U - Web & Script Programming  
**Institution:** Ontario Tech University

## Project Overview

This project is a responsive personal portfolio website developed using Node.js, Express.js, and Embedded JavaScript (EJS) templates.

The website demonstrates server-side routing, reusable EJS partials, Bootstrap-based responsive layouts, and Font Awesome icons.

It includes four pages: Home, About Me, Projects, and Contact Me.

## Live Website

**Deployed Website:**  
https://infr3120-assignment2-4ly0.onrender.com

**GitHub Repository:**  
https://github.com/fhossain-dev/infr3120-assignment2

## Technologies Used

- Node.js
- Express.js 4
- EJS templating engine
- HTML5
- CSS3
- Bootstrap 5
- Font Awesome 7
- Git and GitHub
- Render (cloud deployment)

## Website Pages

### 1. Home (`/`)

Introduces the portfolio owner and provides navigation to the other sections of the website.

### 2. About Me (`/about`)

Provides information about my education, technical interests, skills, and background in Information Technology.

### 3. Projects (`/projects`)

Highlights technical projects and practical work, including:

- Personal Portfolio Website
- Smart Parking Gate System
- MongoDB Database Exercises

### 4. Contact Me (`/contact`)

Provides links to professional profiles and a contact form.

The contact form uses a `mailto:` link to open the visitor's default email application with a prepared message. The visitor must confirm and send the email from their email application.

## Features

- Four functional Express routes
- Server-side rendering using EJS
- Reusable header, navigation, and footer partials
- Responsive design using Bootstrap
- Font Awesome icons
- Mobile-friendly navigation menu
- Project cards and technology badges
- Contact form with email application integration
- GitHub and LinkedIn profile links
- Public deployment through Render

## Project Structure

```text
portfolio-site/
├── bin/
│   └── www
├── public/
│   ├── images/
│   ├── javascripts/
│   └── stylesheets/
│       └── style.css
├── routes/
│   ├── index.js
│   └── users.js
├── views/
│   ├── partials/
│   │   ├── header.ejs
│   │   ├── main_nav.ejs
│   │   └── footer.ejs
│   ├── index.ejs
│   ├── about.ejs
│   ├── projects.ejs
│   ├── contact.ejs
│   └── error.ejs
├── app.js
├── package.json
├── package-lock.json
└── README.md
```

## Running the Project Locally

### Prerequisites

- Node.js
- npm

### Installation

1. Clone the repository:

```bash
git clone https://github.com/fhossain-dev/infr3120-assignment2.git
```

2. Open the project directory:

```bash
cd infr3120-assignment2
```

3. Install dependencies:

```bash
npm install
```

4. Start the Express application:

```bash
npm start
```

5. Open a browser and visit:

```text
http://localhost:3000
```

## Deployment

The application is deployed using Render as a Node.js web service.

**Deployment configuration:**

- Runtime: Node.js
- Branch: `main`
- Build command: `npm install`
- Start command: `npm run start`

The deployed website is publicly accessible through its Render URL.

**Note:** The free Render instance may take additional time to respond after periods of inactivity.

## Security and Testing

The application was tested locally and after deployment.

Testing included:

- Verifying all four website routes
- Checking responsive layouts at mobile screen widths
- Testing navigation and professional profile links
- Testing the contact form's email application integration
- Checking installed dependencies using `npm audit`

The final dependency audit reported **0 known vulnerabilities** at the time of testing.

## Assistance and External Resources

AI was only used as a supporting resource during this project for planning,
understanding Express.js and EJS concepts from course materials,
troubleshooting errors, reviewing implementation decisions, and organizing project
documentations. 

I worked through the project setup, code creation, reviewed and tested implementations,
made configuration decisions, managed the GitHub repository, and deployed the completed
website using Render.

Additional resources used include:

- Express.js and Express Generator documentation
- EJS documentation
- Bootstrap documentation
- Font Awesome documentation
- Node.js documentation

AI assistance was used as a learning resource throughout the project.

## Author

**Farhan Hossain**

Bachelor of Information Technology (Honours) - Networking & IT Security  
Ontario Tech University

- GitHub: https://github.com/fhossain-dev
- LinkedIn: https://www.linkedin.com/in/farhan-h-38bb24306
