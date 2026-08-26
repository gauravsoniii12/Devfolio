Tasks
Build a responsive portfolio with the following:

Semantic structure — a single-page site using:

<header> with your name and a <nav>
<main> containing <section id="about"> and <section id="projects">
<footer id="contact"> with your contact links (email, GitHub, LinkedIn)
<title> and the viewport meta tag in <head>
A colour + type system — 2–3 colours and one or two fonts, applied consistently (CSS variables encouraged, e.g. --brand, --ink).

Layout with Flexbox and Grid —

Flexbox for at least one row (e.g. the header/nav)
CSS Grid for the projects section (a row/grid of project cards, each with a title, one-line description, and a link)
Responsiveness — at least one @media (min-width: …) breakpoint so the projects grid goes from 1 column on mobile to 2–3 columns on desktop, the nav stays usable on a phone, and img { max-width: 100%; height: auto; } keeps images from overflowing.

Real content — your actual name, a short bio, at least 2 project cards (the small projects you built in this course count), and working contact links.

A README.md — with a title, a short description, run/live instructions, and the live URL.

Deploy — publish the site on GitHub Pages so it loads at a public live URL.

Instructions
Suggested build order (work in passes, not perfection-first):

Scaffold the semantic HTML with real headings and placeholder text — get the whole page on screen, plain and unstyled. A working plain page is a milestone.
Add the colour + type system on body and via variables.
Lay out the header with Flexbox and the projects with CSS Grid.
Add your media-query breakpoint and the flexible-image rule; test with the browser device toolbar (F12 → phone icon).
Fill in real content and polish (spacing, hover states, a favicon).
Write the README, then deploy and verify the live URL.
Build checklist (this is also what the reviewer looks for):

 <header>, <main>, <footer> + <section>s for about and projects
 <title> and viewport meta tag in <head>
 Colour + type system applied consistently
 Flexbox used for at least one row
 CSS Grid used for the projects section
 At least one @media (min-width: …) breakpoint that changes the layout
 Images use max-width: 100% (nothing overflows on mobile)
 Real content: name, bio, ≥2 project cards, contact links
 README.md with a live link
 Deployed on GitHub Pages and the live URL loads
Deploy on GitHub Pages:

Push your project to a new GitHub repo (e.g. devfolio) with index.html at the repo root.
Repo → Settings → Pages → Source: Deploy from a branch → select main and / (root) → Save.
Wait ~1 minute, then open the live URL (e.g. https://your-username.github.io/devfolio/) and confirm it loads.
Submission Guidelines
Your repository must be public (so the reviewer and the live URL can access it).
Confirm your live URL opens in an incognito window (proves it's truly public).
Create a branch, push it, and open a Pull Request in your repo.
In the PR description, include both:
Repository URL: https://github.com/<your-username>/devfolio
Live URL: https://<your-username>.github.io/devfolio/
Tick the build checklist in the PR description.
Submit the GitHub PR link on the platform. The PR link is your submission.
