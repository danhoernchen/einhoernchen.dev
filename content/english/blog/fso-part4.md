---
title: FullStackOpen - Part 4
meta_title: ""
description: this is meta description
date: 2025-09-20T17:46:00
image: /images/fsoFirstCert.png
categories:
  - FullStackOpen
  - Code
author: Daniel
tags:
  - FullStackOpen
  - coding
draft: false
---

### 1. Intro

I finally wrapped up Part 4 of FullStackOpen, which dives into backend testing and user authentication.  
Lots of opportunities here to deepen my understanding and practice concepts I’d only touched on in other courses — but this time in a more *project-oriented* way.

I know I should write more tests, but I’m also starting to understand why testing is such a debated topic. On smaller solo projects, it’s tempting to just rely on `console.log()` debugging instead. Still, it’s something I need to work on — along with code organization and project structure in general.

Thinking about picking up a book like [Clean Code](https://books.google.de/books/about/Clean_Code.html?id=EpeDEQAAQBAJ&source=kp_book_description&redir_esc=y) or [The Pragmatic Programmer](https://en.wikipedia.org/wiki/The_Pragmatic_Programmer) next.

---

### 2. Key Learnings

#### Testing Basics

- Writing unit and integration tests
- Supertest is powerful, but test files can get messy fast — need to read more about best practices
- Realization: I’m not a fan of testing *yet*, but I should keep doing it anyway

#### Middleware & Token Auth

- Using middleware for cleaner code
- Working with `.env` files
- Hashing passwords

#### Project Structure

- Splitting routes, controllers, and services — I *really* need to get better at this
- Avoiding spaghetti code
- Writing comments (future me will thank present me)

---

### 3. Challenges

- Remembering `async/await` in every test 🤦🏻
- Tiny mistakes (like forgetting to pass `req.params.id`) can cost hours of debugging.
  → Lesson learned: step away, take breaks. Pomodoro works.

---

### 4. Closing Thought

I really like the project-based, less “hand-holding” approach of FullStackOpen so far.  
And even better: I earned my first certificate for the course 🎉

It may not seem like much, but for me, it’s a solid start.
