# 🎮 Sudoku+ — Part 1 Mock Website
**Author:** Shuhan Sheng  
**Email:** [sheng.sh@northeastern.edu](mailto:sheng.sh@northeastern.edu)  
**GitHub:** [shuhansheng01](https://github.com/shuhansheng01)  
**LinkedIn:** [Shuhan Sheng](https://www.linkedin.com/in/shuhan-sheng-0fifi/)  

**Live site:** [https://shuhansheng01.github.io/sudoku-mock/](https://shuhansheng01.github.io/sudoku-mock/)  
**Repository:** [https://github.com/shuhansheng01/sudoku-mock](https://github.com/shuhansheng01/sudoku-mock)

---

## 🧩 Overview
This project implements a **static HTML + CSS mock** of the classic Sudoku puzzle.  
It demonstrates a complete site layout, page navigation, responsive design, and professional styling—without any JavaScript.  
Future assignments will extend this mock with logic and interactivity.

The theme “**Sudoku +**” uses a **natural, calming aesthetic** inspired by mint, white, and sunshine-yellow tones, paired with rounded typography (*Quicksand* + *M PLUS Rounded 1c*).

---

## 📂 Project Structure
```
sudoku-mock/
│
├── index.html                # Home
├── selection/index.html      # Game selection
├── game-hard/index.html      # 9×9 puzzle
├── game-easy/index.html      # 6×6 puzzle
├── rules/index.html          # Rules & credits
├── high-scores/index.html    # Mock leaderboard
├── login/index.html          # Login form
├── register/index.html       # Register form
│
└── assets/css/
    ├── common.css            # Shared layout & navbar styles
    ├── home.css              # Home/landing visuals
    ├── game.css              # Sudoku grid layout
    └── forms.css             # Login/Register form styling
```

All code is organized per assignment guidelines: each page resides in its own folder, common CSS lives under `assets/css/`, and every route uses `index.html`.

---

## 🧭 Pages Implemented
| Page | Description |
|:--|:--|
| **Home** | Title, tagline, and “Start Game / Read Rules” buttons.|
| **Selection** | List of fictional Sudoku titles + authors → links to Hard Game page.|
| **Hard Game (9×9)** | Fully rendered 9×9 grid with sub-grid borders, number inputs (1-9), and a mock timer.|
| **Easy Game (6×6)** | Simplified 6×6 version with inputs 1-6.|
| **Rules** | List of Sudoku rules + “Made by” credits linking to email, GitHub, LinkedIn.|
| **High Scores** | Table of mock usernames and number completed.|
| **Login** | Username + password form (uses type="password").|
| **Register** | Username, password, verify password fields + buttons.|

---

## 🧭 Navbar
- Fixed position; remains visible while scrolling.  
- Highlights the current page via `aria-current="page"`.  
- Includes links to all pages and a rounded brand logo.  
- On mobile screens (< 420 px) it moves to the bottom for better space usage.

---

## 📱 Mobile Friendly Design
- Responsive layout using CSS Grid + Flexbox.  
- Text and images scale fluidly.  
- Media queries adjust navbar placement and padding for iPhone 12 viewport.  
- All content remains readable and accessible without zoom.

---

## 🧱 HTML Elements Used
`div`, `span`, `a`, `img`, `p`, `head`, `button`, `input`, `body`, `h1–h3`, `ul`, `ol`, `table`.

---

## 🎨 CSS Features Used
| Feature | Where Used |
|:--|:--|
| `font-family` | Imported Google Fonts (*Quicksand*, *M PLUS Rounded 1c*) |
| `background` / `background-color` | Natural gradient and leafy patterns |
| `margin` / `padding` | Page spacing and card layouts |
| `position` | Sticky navbar and responsive footer |
| `flex` / `grid` | Hero section and Sudoku board alignment |
| `align-items` / `text-align` | Centered content |
| `@media queries` | Responsive breakpoints |
| `:hover`, `:focus`, `:active` | Interactive button and link animations |
| `transition` / `transform` | Smooth hover effects |

No `!important` was used.

---

## 🌿 Design Philosophy
- **Theme:** Soft mint green and warm cream for a relaxing “nature” feel.  
- **Typography:** Rounded typefaces to match the cute minimal aesthetic.  
- **Layout:** Balanced white space and card-like containers for clarity.  
- **Accessibility:** Large tap areas, contrast-safe colors, semantic HTML.

---

## 🧠 Writeup (Assignment Questions)

### 1️⃣ Most Challenging Part
The most difficult aspect was constructing the Sudoku grids purely with HTML and CSS while maintaining visual alignment for sub-grids (3×3 and 2×3).  
Learning to use CSS Grid and borders to simulate thicker lines took experimentation.  
Overall, the project helped me gain a deeper understanding of CSS structure and layout systems.

### 2️⃣ Mobile Friendly Decisions
I added media queries to detect small screens and moved the navbar to the bottom to maximize vertical space.  
Font sizes use `clamp()` for fluid scaling, and the Sudoku grid uses `aspect-ratio` so it remains square on any device.  
Padding and margins were adjusted to avoid scrolling overlap.

### 3️⃣ Design Considerations / Proud Areas
I focused on a calming color palette and rounded UI to make the game visually inviting.  
The fixed navbar and consistent spacing create a professional look, while CSS transitions add polish.  
I’m especially proud of how the grid feels balanced and centered without any JavaScript.

### 4️⃣ Future Improvements
Given more time, I would add JavaScript logic for real Sudoku validation, difficulty selection, and a working timer.  
I’d also include dark mode and data storage for user scores.

### 5️⃣ Hours Spent
Approximately 10 hours in total including design research, CSS experimentation, and testing mobile views.

### 6️⃣ Assumptions (Optional)
Assumed that the assignment focused on static presentation and no back-end logic was required.  
Used fictional data for usernames and puzzle titles.

### 7️⃣ Credits / Sources
- Google Fonts (*Quicksand*, *M PLUS Rounded 1c*)  
- Icons & backgrounds built purely with CSS gradients and shapes.  
- No external CSS frameworks (Bootstrap, Material, etc.) were used.  
- Code authored by **Shuhan Sheng** for CS HTML/CSS Mock Assignment.

---

## 🎥 Video Walkthrough
A ≤ 5-minute recording demonstrates:
- Navigation across all pages  
- Sudoku grids (9×9 and 6×6)  
- Navbar behavior and responsive layout  

📹 **Video link:** [https://youtu.be/1IVy6I7Fix0](https://youtu.be/1IVy6I7Fix0)

---

## 🏁 Submission Checklist
✅ Working GitHub URL  
✅ Active GitHub Pages link  
✅ All pages implemented and styled  
✅ Navbar consistent on every page  
✅ Mobile friendly design  
✅ Required HTML tags and CSS features used  
✅ README and video included  

---

**© 2025 Shuhan Sheng — Sudoku + Mock Website**
