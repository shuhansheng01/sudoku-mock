
# Sudoku+ — HTML & CSS Mock Website

**Author:** Shuhan Sheng  
**Email:** sheng.sh@northeastern.edu  
**GitHub:** [shuhansheng01](https://github.com/shuhansheng01)  
**LinkedIn:** [https://www.linkedin.com/in/shuhan-sheng-0fifi/](https://www.linkedin.com/in/shuhan-sheng-0fifi/)

**Live site:** https://shuhansheng01.github.io/sudoku-mock/  
**Repository:** https://github.com/shuhansheng01/sudoku-mock  
**Video Walkthrough:** https://youtu.be/1IVy6I7Fix0  

> This README includes both project documentation and required writeup answers for Canvas submission.

---

## Overview
This project is a static mock website of the game Sudoku, built entirely with **HTML and CSS** (no JavaScript).  
It shows what a Sudoku game page might look like in progress and serves as a base for future interactive versions.

The design uses a **soft natural theme** with mint green and warm beige tones to create a calm and simple interface.  
I focused on clean layout, consistent spacing, and mobile responsiveness.

---

## Pages
- **Home Page:** Game title and navigation buttons.  
- **Selection Page:** List of fictional Sudoku games and authors.  
- **Hard Game (9×9):** Sudoku grid made with CSS Grid, with a fake timer.  
- **Easy Game (6×6):** Smaller grid using the same structure.  
- **Rules Page:** Basic game rules and a “Made by” section with my contact links.  
- **High Scores Page:** Mock leaderboard using an HTML table.  
- **Login / Register Pages:** Simple forms with username and password inputs.

---

## Navbar & Layout
- The navbar stays fixed when scrolling and highlights the active page.  
- Uses flexbox and grid for layout.  
- On small screens (like iPhone 12), the navbar moves to the bottom for better usability.

---

## HTML & CSS Features Used
- **HTML elements:** div, span, a, img, p, head, button, input, h1–h3, ul, ol, table  
- **CSS properties:** font-family, background, margin, padding, position, flex, grid, text-align, @media queries  
- **Pseudo-classes:** :hover, :focus  
- **Transitions:** Used for button and link hover effects  
- No frameworks or libraries were used.

---

## Design Notes
I wanted the site to feel light and friendly, so I chose rounded fonts (*Quicksand* and *M PLUS Rounded 1c*) and soft colors.  
I also made sure each page looks consistent and the Sudoku grids are centered and visually balanced.

---

## Reflection & Writeup Answers

### 1️⃣ What was the most challenging piece of this assignment?  
The most challenging part was creating the Sudoku grid purely with HTML and CSS, especially aligning the borders so that each 3×3 section looked consistent.  
It took several iterations to find a clean way to use CSS Grid without breaking the overall balance.  
It was also a bit tricky to center the grid on the page while keeping it responsive for different screen sizes.

---

### 2️⃣ What decisions did you make when you made your site mobile friendly?  
I used media queries to automatically adjust font sizes and reposition elements when the screen width became small.  
The biggest design change was moving the navigation bar from the top to the bottom of the screen on mobile, so it wouldn’t take up too much vertical space.  
I also made sure that buttons were large enough to tap easily, and that the Sudoku grid stayed centered even on narrow screens.

---

### 3️⃣ What did you take into account when you developed the design of your website? Is there anything that you’re particularly proud of?  
I wanted a calm and inviting look, so I chose a soft “natural” theme using mint green and beige tones with rounded fonts.  
I focused on keeping everything consistent — margins, spacing, and color balance across all pages.  
I’m especially proud of how the design feels both simple and polished, with a consistent mood throughout the site.

---

### 4️⃣ Given more time or resources, what additional features would you add to your site in the future?  
If I had more time, I’d like to add JavaScript so that users can actually play Sudoku on the page.  
A working timer, score counter, and input validation would make it feel like a real game.  
I’d also add a dark mode option and simple animations to make interactions smoother.

---

### 5️⃣ How many hours did you spend on this assignment?  
Overall, I spent about 10 hours on this assignment — including building the structure, refining the CSS, testing responsive behavior, and recording the video.

---

### 6️⃣ (Optional) If you made any assumptions about this assignment, what are they?  
I assumed that the main focus was on structure and design rather than logic or functionality, since JavaScript was not allowed.  
I also assumed that it was acceptable to use placeholder text and mock data, as long as each required page was visually complete.  
Finally, I assumed that typography and visual polish would contribute to the “professional design” part of the grading.

---

### 7️⃣ If you used any code or design from somewhere online, mention it here.  
I didn’t use any prewritten code, libraries, or templates.  
For fonts, I imported **Quicksand** and **M PLUS Rounded 1c** from Google Fonts to match the natural theme.  
All CSS and HTML were written manually by me.

---

**© 2025 Shuhan Sheng — Sudoku+ Mock Website**
