## Design Plan – Personal Website (Intro to AI)

### Page Structure

The website is a single static page composed of clearly labeled sections:

- **Header (browser “shell” bar)**: Shows the window-style bar with traffic-light dots and the heading “Emilia Kozeracki · Intro to AI”. This establishes identity and the course context immediately when the page loads.
- **Top Navigation**: A simple text navigation row with anchors linking to the three main sections: **About**, **Projects**, and **Learning**. This allows users to jump directly to each section within the single page.
- **About Section**: Contains the main heading with the student’s name and a short subtitle “Intro to AI”, followed by the self-introduction paragraph describing major, school (CUA), minor, and interest in coding and AI.
- **Projects Section**: Lists placeholder entries for “Project 1” and “Project 2: Java Script Game” and includes a link to the GitHub profile where future project code will live.
- **Learning Section**: The right-hand column titled “Learning” (a snapshot card layout) that highlights current topics of focus such as Intro to AI, ethics, and Python practice.
- **Footer**: A small footer bar that notes the site is a work in progress and that it is hosted with GitHub Pages.

### Layout Choices

- The overall layout uses a **centered card/shell** on top of a dark gradient background, creating a clear visual boundary for the content while keeping the page modern and easy to read.
- Inside the shell, the main body is a **two-column grid** on larger screens: the left column holds the About and Projects sections, while the right column holds the Learning snapshot. On smaller screens, the layout collapses to a single column so the content is still readable on phones and tablets.
- Section headings (**About**, **Projects**, **Learning**) are styled as small uppercase headings with increased letter-spacing to visually separate sections and make the page structure obvious.
- The design uses **consistent typography** (system fonts) and a limited color palette (dark background with blue accents) to keep the focus on the text content instead of decoration.
- All styling is implemented with **CSS only** (no JavaScript or external frameworks), in order to meet the requirement that the site remain a static HTML/CSS page suitable for GitHub Pages and the course assignment.

### Design Rationale

The content is organized to first introduce the student, then highlight projects, and finally show what is being learned right now. Placing the **About** section at the top of the main content column ensures that visitors immediately see who the site belongs to and why it exists, which is important for a personal public website. The **Projects** section follows naturally, since it is the primary evidence of skills and progress and will grow over time as more assignments and experiments are completed. The **Learning** snapshot in the right column reinforces the course context (Intro to AI and data analytics) and gives a quick overview of current topics without overwhelming the main narrative. The combination of clear headings, internal navigation links, and a two-column layout makes the page easy to scan and keeps related information grouped logically for both classmates and instructors reviewing the site and its SDLC artifacts.

