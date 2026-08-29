# Cursor Computers Academy

A comprehensive educational platform for learning **Python**, **MySQL**, and **Core Java** — built with pure HTML, CSS, and JavaScript. No frameworks, no dependencies, no build tools.

**Live Site:** [https://gauravkv.github.io/notes/](https://gauravkv.github.io/notes/)

---

## What's Inside

The academy covers three programming languages, each with **Theory**, **Programs**, and **Quiz** sections.

### Python Programming

| Section | File | Details |
|---------|------|---------|
| Theory | `python_theory.html` | 21 topics with interactive sidebar navigation |
| Programs | `python_programs.html` | 100+ programs in accordion-style layout |
| Quiz | `python_quiz.html` | 25 MCQs with 30-second timer per question |

**Topics covered:**
Introduction, Variables, Data Types, Operators, Conditional Statements, Loops, Functions, Types of Functions, Lists, Tuples, Dictionary, Set, Strings, Modules & Packages, Import Statement, Exception Handling, File Handling, Class and Object, Inheritance, Operator Overloading, Python with MySQL

---

### MySQL Database

| Section | File | Details |
|---------|------|---------|
| Theory | `mysql_theory.html` | 30 topics with interactive sidebar navigation |
| Programs | `mysql_programs.html` | 100+ programs in accordion-style layout |
| Quiz | `mysql_quiz.html` | 25 MCQs with 30-second timer per question |

**Topics covered:**
Introduction to MySQL, Installing MySQL, Databases, Tables, INSERT, SELECT, WHERE Clause, UPDATE, DELETE, ORDER BY, LIMIT & OFFSET, Aggregate Functions, GROUP BY, HAVING Clause, Joins, Subqueries, UNION, String Functions, Numeric Functions, Date Functions, ALTER TABLE, Constraints, Indexes, Views, Stored Procedures, User-Defined Functions, Triggers, Transactions, User Management, Import & Export

---

### Core Java

| Section | File | Details |
|---------|------|---------|
| Theory | `corejava_theory.html` | 30 topics with interactive sidebar navigation |
| Programs | `corejava_programs.html` | 100+ programs in accordion-style layout |
| Quiz | `corejava_quiz.html` | 25 MCQs with 30-second timer per question |

**Topics covered:**
Introduction, Installing Java (JDK), Hello World Program, Data Types, Variables, Operators, Strings, User Input (Scanner), Type Casting, If...Else, Switch Statement, While Loop, For Loop, Break and Continue, Arrays, Multi-Dimensional Arrays, Methods, Method Overloading, OOP Concepts, Classes and Objects, Constructors, Encapsulation, Inheritance, Polymorphism, Abstraction, Interfaces, Exception Handling, Collections Framework, File Handling, Packages

---

## Features

### Theory Pages
- **Sidebar navigation** with clickable topic buttons
- **Code examples** with syntax highlighting and one-click **Copy** button
- **Output sections** showing expected results
- **Info boxes** with tips and key points
- **Mobile-responsive** — sidebar converts to a slide-out menu on small screens

### Programs Pages
- **100+ programs** per language
- **Accordion layout** — click to expand/collapse each program
- Code with **copy functionality**

### Quiz Pages
- **25 multiple-choice questions** per language
- **30-second timer** per question — auto-advances on timeout
- **Answer locking** — one click, no changing answers
- **Green/red feedback** — instant visual response on answer selection
- **Score tracking** throughout the quiz
- **Review screen** at the end with A/B/C/D labels and tick/cross marks for each question

### Navigation
- **Sticky navbar** with dropdown menus for Python, MySQL, and Java
- **Mobile hamburger menu** for screens under 600px
- Consistent navigation across all pages

---

## Project Structure

```
notes/
├── index.html                  # Home page — links to all three subjects
├── index_python.html           # Python sub-page (Theory / Programs / Quiz)
├── index_mysql.html            # MySQL sub-page (Theory / Programs / Quiz)
├── index_java.html             # Java sub-page (Theory / Programs / Quiz)
│
├── python_theory.html          # Python theory — 21 topics
├── python_programs.html        # Python programs — 100+ examples
├── python_quiz.html            # Python quiz — 25 MCQs
│
├── mysql_theory.html           # MySQL theory — 30 topics
├── mysql_programs.html         # MySQL programs — 100+ examples
├── mysql_quiz.html             # MySQL quiz — 25 MCQs
│
├── corejava_theory.html        # Core Java theory — 30 topics
├── corejava_programs.html      # Core Java programs — 100+ examples
├── corejava_quiz.html          # Core Java quiz — 25 MCQs
│
├── .github/
│   └── workflows/
│       └── static.yml          # GitHub Pages deployment workflow
│
└── README.md
```

---

## Tech Stack

- **HTML5** — semantic markup
- **CSS3** — responsive design with flexbox, media queries at 600px breakpoint
- **JavaScript** — vanilla JS, no libraries or frameworks
- **GitHub Pages** — automatic deployment on push to `main`

Every page is **fully self-contained** — all CSS and JS are inline. No external CDNs, no build step, no dependencies.

---

## Deployment

The site is automatically deployed to GitHub Pages via GitHub Actions. Every push to the `main` branch triggers a deployment.

**Workflow:** `.github/workflows/static.yml`

---

## How to Run Locally

```bash
# Clone the repository
git clone https://github.com/gauravkv/notes.git
cd notes

# Start a local server
python3 -m http.server 8080

# Open in browser
# http://localhost:8080
```

Or simply open any `.html` file directly in your browser — no server required.

---

## Contributing

1. Fork the repository
2. Create your branch (`git checkout -b feature/new-topic`)
3. Add your changes
4. Commit (`git commit -m "Add new topic"`)
5. Push (`git push origin feature/new-topic`)
6. Open a Pull Request

---

## License

This project is maintained by **Cursor Computers Academy**.

&copy; 2026 Cursor Computers Academy
