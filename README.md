Documentation – Personal Website Portfolio
File Name: Personal Website Portfolio.html
Purpose: A responsive personal portfolio webpage to showcase skills, projects, and contact information for Edwin Kariuki.

1. File Overview
This is a single HTML file containing:

HTML5 structure for content layout.

Embedded CSS styles for appearance.

No external JavaScript or images required.

Designed to be self-contained (easy to host anywhere).

2. Page Structure
HTML Document Setup
html
Copy
Edit
<!DOCTYPE html>
<html lang="en">
<head>
  ...
  <title>Edwin Kariuki | Portfolio</title>
  <style> ... </style>
</head>
<body> ... </body>
</html>
Declares HTML5 document type.

Sets page language to English.

Uses meta tags for:

UTF-8 character encoding.

Compatibility with Internet Explorer.

Responsive mobile-friendly design.

Title: Edwin Kariuki | Portfolio.

Main Sections
1. Navigation Bar (<header>)
Class: .navbar

Displays site logo (name) on the left and navigation links on the right.

Links point to sections within the same page:

#about, #skills, #projects, #contact.

2. Hero Section (#home)
Large welcoming text:

Heading: "Hi, I'm Edwin Kariuki"

Subheading: "Software Developer passionate about web development & machine learning."

Background: White, centered text.

3. About Section (#about)
Introduction paragraph about education and passion.

Interests listed as bullet points.

4. Skills Section (#skills)
Skill tags in rounded pill-style boxes.

Skills listed: Python, HTML, CSS, Java, NodeJS, React.

5. Projects Section (#projects)
Grid layout with responsive cards.

Each card contains:

Project name.

Short description.

GitHub link (target="_blank" to open in a new tab).

6. Contact Section (#contact)
Contact Form:

Fields: Name, Email, Message.

Submit button labeled "Send Message".

Note: The form is static and does not process submissions unless connected to a backend.

Contact Information:

Email, phone, LinkedIn profile link.

7. Footer
Dark background with copyright:

css
Copy
Edit
© 2025 Edwin Kariuki. All rights reserved.
3. CSS Styling Overview
Reset & Base:
Removes default margin/padding, sets box-sizing: border-box, defines body font & colors.

Navbar:

Flexbox layout for spacing.

Dark background with white text.

Links change color on hover.

Hero Section:

Centered content with padding.

Larger font for heading.

Container Sections:

Max width: 900px.

Centered with rounded corners.

White background for contrast.

Skills:

Flex wrap layout for skill tags.

Rounded pill-shaped backgrounds.

Projects Grid:

Responsive grid using grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));

Cards with border, padding, and hover effect for links.

Contact Form:

Grid layout for spacing between inputs.

Styled buttons with hover effect.

Footer:

Dark background.

White centered text.

4. Key Features
Responsive Design: Layout adapts to screen size.

Self-contained: All CSS inside <style> block, no dependencies.

Accessible Links: Navigation scrolls to sections.

Semantic HTML: Clear use of headings, sections, and lists.

5. How to Use
Save the file as index.html.

Host it using:

GitHub Pages.

Netlify.

Vercel.

Optional:

Connect the contact form to an email API or Google Forms.

Replace placeholder text with your latest projects and skills.


7. License
This is your personal portfolio. You hold all rights to the content, images, and design unless otherwise shared.
