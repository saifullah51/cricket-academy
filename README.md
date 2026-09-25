🏏 Apex Cricket Academy

A modern, responsive cricket academy website designed around a premium high-performance sports experience. The site presents academy programs, cricket departments, coaching staff, facilities, player performance telemetry, achievements, gallery content, trial enrollment, and contact information.

✨ Features

🏟️ Cinematic hero section with academy branding and performance statistics

📖 Academy overview and legacy section

🏏 Cricket programs for different player development stages

🎯 Interactive cricket department tabs:

Batting

Bowling

Fielding

Wicketkeeping

👨‍🏫 International master coaches section

🏟️ Facilities and high-performance infrastructure showcase

📊 Interactive player performance / telemetry dashboard

🏆 Achievements and player pathway information

🖼️ Gallery with category filtering

📝 Trial / enrollment form with client-side success message

📍 Contact and academy location section

📱 Responsive layout for desktop, tablet, and mobile screens

🎨 Premium dark cricket-stadium visual design

⚡ Lightweight client-side JavaScript interactions

🛠️ Technologies Used

HTML5 – Page structure and semantic content

CSS3 / Tailwind CSS CDN – Styling and responsive layouts

Vanilla JavaScript – Interactive components and form handling

Google Fonts

Oswald

Inter

Material Symbols – Icons

No backend or database is required for the current demo.

📂 Project Structure

Apex-Cricket-Academy/
│
├── code.html       # Main website page
├── screen.png      # Website preview/screenshot
├── DESIGN.md       # Visual design system and UI specifications
└── README.md       # Project documentation

🚀 How to Run

Option 1: Open directly

Download or extract the project.

Open code.html in a modern web browser.

The website will load directly.

Option 2: Use VS Code Live Server

Open the project folder in Visual Studio Code.

Install the Live Server extension.

Right-click code.html.

Select Open with Live Server.

The website will open in your browser.

🎮 Interactive Components

Department Tabs

The website allows visitors to switch between:

Batting → Bowling → Fielding → Wicketkeeping

This is handled using the switchDept() JavaScript function.

Performance Telemetry

The Performance Lab includes a toggle between:

Batting Metrics ↔ Bowling Metrics

The dashboard updates player information and performance values dynamically using the toggleTelemetry() function.

Gallery Filters

Gallery items can be filtered by category using the filterGallery() function.

Enrollment Form

The enrollment form uses client-side JavaScript to:

Prevent the default form submission.

Display a registration success message.

Reset the form.

Note: The current form does not send data to a real server or database.

🎨 Design System

The project uses a premium dark-mode cricket aesthetic inspired by:

Floodlit cricket stadiums

Professional scoreboards

Cricket pitch geometry

High-performance sports laboratories

Architectural pavilion design

Main Colors

Purpose

Color

Deep background

#07100D

Dark surface

#0C1512

Cricket green

#0A4D39

Active green

#115E43

Trophy gold

#D4AF37

Primary text

#DAE5DF

Secondary text

#BFC9C2

Typography

Oswald – Headings, statistics, labels

Inter – Body text and supporting information

The complete design specification is available in DESIGN.md.

📱 Responsive Design

The layout adapts to different screen sizes:

Mobile: Single-column layouts and compact navigation

Tablet: Multi-column responsive sections

Desktop: Full 12-column architectural layout

Recommended browsers:

Google Chrome

Microsoft Edge

Mozilla Firefox

Safari

🔗 External Resources

The website currently loads some resources from external CDNs and hosted image URLs, including:

Tailwind CSS CDN

Google Fonts

Google Material Symbols

Hosted academy/photography assets

An internet connection may therefore be required for all visual assets and fonts to appear correctly.

🔧 Customization

You can customize the project by editing code.html.

Change Academy Name

Search for:

APEX CRICKET ACADEMY

and replace it with your preferred academy name.

Change Contact Details

Update:

Academy address

Phone number

Email address

WhatsApp link

Operating hours

Change Images

Replace the existing image URLs in code.html with your own academy images.

Change Colors

The Tailwind configuration near the top of code.html contains the project's custom design tokens. Update those values to create a different visual theme.

⚠️ Current Limitations

This is currently a front-end demonstration website.

The following features are not connected to a backend:

Enrollment form submission

Newsletter subscription

User login/profile

Database storage

Real performance telemetry

Online payments

Real-time academy schedules

CMS/admin dashboard

These can be added later using technologies such as:

Frontend
HTML + CSS + JavaScript

Backend
Node.js + Express.js

Database
MongoDB / MySQL / PostgreSQL

Authentication
JWT / Firebase Authentication

Deployment
Vercel / Netlify / Render / GitHub Pages

🌱 Future Improvements

Add a real backend API

Store enrollment applications in a database

Add student and coach login

Add an admin dashboard

Add real player performance data

Add online trial booking

Add payment integration

Add academy event/calendar management

Add real social media links

Optimize images and assets locally

Add SEO metadata and Open Graph tags

Add accessibility improvements

Deploy the website publicly

📄 License

This project is intended for educational, portfolio, and demonstration purposes.

You may customize the design and content for your own cricket academy or academic project.

👨‍💻 Author

Salman

Student | Software Developer | Aspiring Data Analyst

Built as a modern cricket academy web-platform concept using HTML, Tailwind CSS, and Vanilla JavaScript.
