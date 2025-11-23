# Student Portal

A responsive student management and profile portal application built with HTML, CSS, and vanilla web technologies.

## Overview

Student Portal is a web-based application designed to help institutions manage student information and provide students with an easy way to view their profiles and connect with peers. It features a clean, modern interface with navigation between key sections.

## Features

- **Home Page** - Welcome page with quick access links to main features
- **Students Directory** - Browse through a list of all students with their details and profiles
- **Student Profiles** - Detailed view of individual student information including:
  - Personal information (ID, email, phone)
  - Academic details (major, year, GPA)
  - Bio and interests
- **Responsive Design** - Works seamlessly on desktop and mobile devices
- **Navigation System** - Intuitive header navigation to switch between pages

## Project Structure

```
myproject/
├── index.html           # Home page with hero section and quick links
├── students.html        # Students directory with card grid layout
├── profile.html         # Individual student profile page
├── css/
│   └── styles.css      # Centralized styling with CSS variables
└── README.md           # This file
```

## Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling with CSS custom properties (variables)
- **Vanilla JavaScript** - (Optional for future interactivity)

## Pages

### index.html
The landing page featuring:
- Navigation header with logo
- Hero section with welcome message
- Quick access cards linking to Students and Profile pages

### students.html
Directory page displaying:
- List of students in a responsive grid layout
- Student cards showing name, major, year, ID, and bio
- Links to individual student profiles

### profile.html
Profile page with:
- Profile header with avatar and basic info
- Personal information section (ID, email, phone)
- Academic information section
- Additional sections for achievements and more

## Styling Approach

The app uses **CSS custom properties** for consistent theming:
- `--primary-color: #4a6fa5` (Main blue)
- `--secondary-color: #166088` (Darker blue)
- `--accent-color: #4fc3f7` (Light cyan)
- Responsive grid layout for student cards
- Shadow and spacing utilities

## Getting Started

1. Clone or download the repository
2. Open `index.html` in a web browser
3. Navigate through pages using the header menu

No build process or server required - run directly from the file system.

## Future Enhancements

- Add JavaScript interactivity for filtering/searching students
- Backend API integration for dynamic student data
- Student authentication and login system
- Form submission for profile updates
- Database integration for data persistence

## License

This project is open source and available on GitHub at `https://github.com/krushnashelke016/student-app`
