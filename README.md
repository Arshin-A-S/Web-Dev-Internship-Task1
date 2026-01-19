Task 1- Semantic HTML Personal Profile Page:
This repository contains the first task of my web development journey: building a fully functional personal profile page using Semantic HTML5. The focus of this project was to move beyond generic layout tags and use elements that provide meaning and structure to both the browser and assistive technologies.

Technical Summary: 
The project involved creating a structured document from scratch, ensuring high accessibility standards and a logical content hierarchy.

Key Implementation Details:
Manual Boilerplate Creation: The document was written manually starting with <!DOCTYPE html> to understand the core requirements of an HTML document, including the <head> metadata and the <body> content.

Semantic Architecture: 
Instead of using non-semantic <div> tags, I utilized HTML5 semantic elements to define the page structure:

<header>: Used for the introduction and branding of the profile.

<nav>: Used to wrap the primary navigation menu.

<main>: Identified the central content unique to this specific page.

<section>: Grouped related content like "Education" and "Skills."

<article>: Used within the Education section to wrap a specific degree entry.

<footer>: Used for authorship and copyright information.

Internal Navigation: I implemented an internal menu using anchor tags (<a>) and unique id attributes. This allows users to "jump" to specific sections (About, Education, Skills, or Contact) within the same page.

Content Hierarchy: Followed a strict heading hierarchy (h1 for the main title, h2 for section headers, and h3 for sub-details) to ensure screen readers can navigate the content easily.
