# 🚀 30-Day MERN Stack + DSA Roadmap
### Senior Engineer-Reviewed | 6 hrs/day MERN + 2 hrs/day DSA

> **Your Profile:** HTML/CSS ✅ | Basic JS ✅ | 8 hrs/day commitment ✅
> **Stack:** MongoDB · Express.js · React.js · Node.js · TailwindCSS · Git · JWT · Vercel

---

## 📋 MASTER SCHEDULE OVERVIEW

| Week | MERN Focus | DSA Focus | Weekly Project |
|------|-----------|-----------|----------------|
| Week 1 | JavaScript Deep Dive + Git + Node.js | Arrays & Strings | CLI Task Manager |
| Week 2 | Express.js + MongoDB + REST APIs | Hashing, Linked Lists, Stacks/Queues | Blog API Backend |
| Week 3 | React.js Fundamentals + Hooks | Trees, Recursion, Binary Search | React Blog Frontend |
| Week 4 | Full-Stack Integration + Auth + Deploy | Dynamic Programming, Graphs | Full-Stack MERN App |

---
---

# 🟨 WEEK 1 — JavaScript Mastery + Git + Node.js Basics

---

## DAY 1 → Advanced JavaScript — The Foundation You Were Missing

### 🎯 Topics to Learn
Modern JS features that every MERN developer uses daily: ES6+, closures, `this`, scope, hoisting, and the event loop.

### 📚 Sub-topics
- `let`, `const`, `var` — scoping rules and hoisting
- Arrow functions vs regular functions — `this` binding difference
- Template literals, destructuring (array + object), spread/rest operators
- Default parameters, optional chaining (`?.`), nullish coalescing (`??`)
- Closures — what they are, why they matter
- The call stack, event loop, and single-threaded nature of JS

### ⏱ Time Breakdown
| Time | Activity |
|------|----------|
| 0–1.5 hrs | Watch JS ES6+ video (Traversy Media) |
| 1.5–3 hrs | Watch closures + scope (Akshay Saini) |
| 3–4.5 hrs | Code along all examples in VS Code |
| 4.5–6 hrs | Practice tasks below |

### 🔗 Professional Resources
- 📺 **[JavaScript ES6 Tutorial – Traversy Media](https://www.youtube.com/watch?v=WZQc7RUAg18)**
- 📺 **[Namaste JavaScript (Episode 1–7) – Akshay Saini](https://www.youtube.com/playlist?list=PLlasXeu85E9cQ32gLCvAvr9vNaUccPVNP)** ← Highly recommended by Indian MERN engineers
- 📺 **[JavaScript Full Course – CodeWithHarry](https://www.youtube.com/watch?v=ER9SspLe4Hg)**
- 🌐 **[MDN Web Docs – JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)**
- 🌐 **[javascript.info](https://javascript.info/)** ← Best written JS resource online

### 💻 Coding Practice
```javascript
// Task 1: Rewrite this using arrow functions + destructuring
function getUser(user) {
  return user.name + " is " + user.age;
}

// Task 2: Create a closure counter
// (makeCounter function that returns increment/decrement/reset)

// Task 3: Explain output of this code (event loop quiz)
console.log("1");
setTimeout(() => console.log("2"), 0);
console.log("3");
```
- Write 5 functions using each ES6 feature
- Solve: [JS Closures Quiz on javascript.info](https://javascript.info/closure#tasks)

### 📝 Notes & Tips
> 💡 Akshay Saini's "Namaste JavaScript" is the single most recommended JS series by Indian developers on LinkedIn and Twitter. Treat it like a course, not background noise.

---

## DAY 2 → Asynchronous JavaScript — Callbacks, Promises, Async/Await

### 🎯 Topics to Learn
Almost everything in Node.js and the MERN stack is async. This is non-negotiable knowledge.

### 📚 Sub-topics
- Synchronous vs Asynchronous execution
- Callbacks and callback hell (pyramid of doom)
- Promises — `.then()`, `.catch()`, `.finally()`
- `Promise.all`, `Promise.race`, `Promise.allSettled`
- `async/await` — cleaner syntax for promises
- `try/catch` with async functions
- Fetch API (browser) vs Axios

### ⏱ Time Breakdown
| Time | Activity |
|------|----------|
| 0–2 hrs | Namaste JavaScript Ep 8–13 (Akshay Saini) |
| 2–3.5 hrs | Async/await + Promises tutorial |
| 3.5–5 hrs | Code along: build a fake API caller |
| 5–6 hrs | Practice tasks |

### 🔗 Professional Resources
- 📺 **[Namaste JavaScript Season 1 Ep. 8–13 – Akshay Saini](https://www.youtube.com/playlist?list=PLlasXeu85E9cQ32gLCvAvr9vNaUccPVNP)**
- 📺 **[Async JavaScript – The Net Ninja](https://www.youtube.com/playlist?list=PL4cUxeGkcC9jx2TTZk3IGWKSbtugYdrlu)**
- 📺 **[JavaScript Promises – Traversy Media](https://www.youtube.com/watch?v=PoRJizFvM7s)**
- 🌐 **[javascript.info – Promises, Async/Await](https://javascript.info/async)**

### 💻 Coding Practice
```javascript
// Task 1: Convert this callback hell to async/await
getUser(id, function(user) {
  getPosts(user.id, function(posts) {
    getComments(posts[0].id, function(comments) {
      console.log(comments);
    });
  });
});

// Task 2: Fetch 3 APIs simultaneously using Promise.all
// Use: https://jsonplaceholder.typicode.com/

// Task 3: Build a function that retries a failed fetch 3 times
```

### 📝 Notes & Tips
> 💡 `async/await` is syntactic sugar over Promises. Understanding Promises first makes `async/await` trivially easy. Don't skip the Promises section.

---

## DAY 3 → JavaScript — Arrays, Objects, Functional Programming

### 🎯 Topics to Learn
The methods you'll use in every React component and every Node route handler.

### 📚 Sub-topics
- Array methods: `map`, `filter`, `reduce`, `find`, `findIndex`, `some`, `every`, `flat`, `flatMap`
- Object methods: `Object.keys()`, `Object.values()`, `Object.entries()`, `Object.assign()`, spread
- Immutability concept (critical for React state)
- Chaining array methods
- `JSON.parse()` and `JSON.stringify()`
- Deep copy vs shallow copy

### ⏱ Time Breakdown
| Time | Activity |
|------|----------|
| 0–2 hrs | Array/object methods video + docs |
| 2–4 hrs | Code all 15+ methods from scratch |
| 4–5 hrs | Functional programming exercises |
| 5–6 hrs | LeetCode easy problems using these methods |

### 🔗 Professional Resources
- 📺 **[JavaScript Array Methods – Traversy Media](https://www.youtube.com/watch?v=rRgD1yVwIvE)**
- 📺 **[Functional Programming – Fun Fun Function](https://www.youtube.com/playlist?list=PL0zVEGEvSaeEd9hlmqxi0kl6n8u7D3pFL)**
- 🌐 **[MDN Array Reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)**
- 🌐 **[javascript.info – Array Methods](https://javascript.info/array-methods)**

### 💻 Coding Practice
```javascript
// Given this dataset, solve all 5 tasks using array methods only (no for loops)
const products = [
  { name: "Laptop", price: 50000, category: "electronics", inStock: true },
  { name: "Shirt", price: 800, category: "clothing", inStock: false },
  { name: "Phone", price: 30000, category: "electronics", inStock: true },
  { name: "Book", price: 400, category: "education", inStock: true },
];

// 1. Get names of all in-stock products
// 2. Get total price of all electronics
// 3. Get products sorted by price descending
// 4. Check if any product is out of stock
// 5. Transform into { name: price } object using reduce
```

---

## DAY 4 → Git & GitHub — Professional Version Control

### 🎯 Topics to Learn
Every company uses Git. You must know this before writing a single line of Node.js.

### 📚 Sub-topics
- Installing Git, VS Code setup (GitLens extension)
- `git init`, `git add`, `git commit`, `git status`, `git log`
- Branching: `git branch`, `git checkout`, `git switch`, `git merge`
- Remote repos: `git remote`, `git push`, `git pull`, `git clone`
- `.gitignore` — what to ignore (node_modules, .env)
- Pull Requests (PR) workflow on GitHub
- Resolving merge conflicts
- GitHub README best practices

### ⏱ Time Breakdown
| Time | Activity |
|------|----------|
| 0–2 hrs | Git crash course video |
| 2–3 hrs | GitHub workflow video |
| 3–4.5 hrs | Create your GitHub profile, push Day 1–3 code |
| 4.5–6 hrs | Practice branching workflow |

### 🔗 Professional Resources
- 📺 **[Git & GitHub Crash Course – Traversy Media](https://www.youtube.com/watch?v=SWYqp7iY_Tc)**
- 📺 **[Git Tutorial for Beginners – CodeWithHarry](https://www.youtube.com/watch?v=gwWKnnCMQ5c)**
- 📺 **[GitHub for Beginners – freeCodeCamp](https://www.youtube.com/watch?v=RGOj5yH7evk)**
- 🌐 **[Official Git Documentation](https://git-scm.com/doc)**
- 🌐 **[GitHub Docs](https://docs.github.com/en)**
- 🌐 **[Learn Git Branching (Interactive)](https://learngitbranching.js.org/)** ← Best interactive Git tool

### 💻 Coding Practice
- Create a GitHub repo "mern-30-days"
- Create branches: `feature/day1-js`, `feature/day2-async` and merge to main
- Write a proper README with your roadmap progress
- Simulate a merge conflict and resolve it

### 📝 Notes & Tips
> 💡 Commit message convention: `feat: add user authentication` or `fix: resolve login bug`. Companies use Conventional Commits. Start now.

---

## DAY 5 → Node.js — JavaScript on the Server

### 🎯 Topics to Learn
Node.js lets JavaScript run outside the browser. This is the "N" in MERN.

### 📚 Sub-topics
- What is Node.js? Event-driven, non-blocking I/O model
- Node REPL, running `.js` files with `node`
- Global objects: `__dirname`, `__filename`, `process`, `global`
- Core modules: `fs` (file system), `path`, `os`, `events`, `http`
- Creating your first HTTP server with `http` module
- npm (Node Package Manager) — `npm init`, `package.json`, `package-lock.json`
- Installing packages: local vs global, `devDependencies`
- `nodemon` for auto-restart

### ⏱ Time Breakdown
| Time | Activity |
|------|----------|
| 0–2 hrs | Node.js crash course |
| 2–3.5 hrs | Core modules practice |
| 3.5–5 hrs | Build basic HTTP server |
| 5–6 hrs | npm practice + nodemon setup |

### 🔗 Professional Resources
- 📺 **[Node.js Crash Course – Traversy Media](https://www.youtube.com/watch?v=fBNz5xF-Kx4)**
- 📺 **[Node.js Full Course – CodeWithHarry](https://www.youtube.com/watch?v=oh1F1mPBnKE)**
- 📺 **[Node.js Tutorial – The Net Ninja](https://www.youtube.com/playlist?list=PL4cUxeGkcC9jszmQoCs0VGnjgOZKMMnvL)**
- 🌐 **[Node.js Official Docs](https://nodejs.org/en/docs/)**
- 🌐 **[Node.js Best Practices – GitHub](https://github.com/goldbergyoni/nodebestpractices)** ← 98k stars

### 💻 Coding Practice
```javascript
// Task 1: Build a CLI file reader
// node app.js read myfile.txt → prints contents
// node app.js write myfile.txt "Hello World" → writes to file

// Task 2: Create an HTTP server that:
// GET /  → returns "Welcome"
// GET /about → returns "About Page"
// Any other → returns 404

// Task 3: Read a JSON file and calculate total price of products
```

---

## DAY 6 → Node.js — Modules, Events, Streams + VS Code Setup

### 🎯 Topics to Learn
Deep dive into Node's module system and how to organize code like a pro.

### 📚 Sub-topics
- CommonJS modules: `require()`, `module.exports`, `exports`
- ES Modules: `import/export` in Node (with `"type": "module"`)
- Event Emitter pattern — `on`, `emit`, `once`, `removeListener`
- Streams — readable, writable, why they matter for large files
- Buffer basics
- VS Code extensions for MERN: ESLint, Prettier, GitLens, Thunder Client, REST Client, Auto Import
- Debugging in VS Code (breakpoints, watch variables)

### ⏱ Time Breakdown
| Time | Activity |
|------|----------|
| 0–1.5 hrs | Module system deep dive |
| 1.5–3 hrs | Event emitter + streams |
| 3–4.5 hrs | VS Code complete setup |
| 4.5–6 hrs | Build a custom event-driven logger |

### 🔗 Professional Resources
- 📺 **[Node.js Modules – The Net Ninja](https://www.youtube.com/watch?v=xHLd36QoS4k)**
- 📺 **[VS Code Setup for Web Dev – Traversy Media](https://www.youtube.com/watch?v=fnPhJHN0jTE)**
- 🌐 **[Node.js Events Docs](https://nodejs.org/api/events.html)**
- 🌐 **[ESLint Setup](https://eslint.org/docs/user-guide/getting-started)**

### 💻 Coding Practice
- Build a custom EventEmitter-based pub/sub system
- Create a module that exports: `add`, `subtract`, `multiply`, `divide`
- Set up ESLint + Prettier in your project with Airbnb config

---

## DAY 7 → WEEK 1 PROJECT — CLI Task Manager

### 🎯 Project: Command Line Task Manager with File Persistence

This is a real project you can put on your resume.

### 📚 Features to Build
- Add tasks: `node tasks.js add "Complete roadmap"`
- List all tasks: `node tasks.js list`
- Mark complete: `node tasks.js done 1`
- Delete task: `node tasks.js delete 1`
- Filter: `node tasks.js list --pending` or `--completed`
- Tasks stored in `tasks.json` (persist between sessions)

### 📁 Project Structure
```
cli-task-manager/
├── tasks.js          (CLI entry point)
├── taskManager.js    (core logic module)
├── fileHandler.js    (read/write JSON)
├── tasks.json        (auto-generated)
├── package.json
└── README.md
```

### 💻 Concepts Applied
- Node.js `fs` module (async file read/write)
- `process.argv` for CLI arguments
- CommonJS modules
- JSON data persistence
- Error handling

### 📤 Submission
- Push to GitHub with a proper README
- Include a demo GIF using [ScreenToGif](https://www.screentogif.com/)

---
---

# 🟦 WEEK 2 — Express.js + MongoDB + REST API Design

---

## DAY 8 → Express.js — The Web Framework

### 🎯 Topics to Learn
Express is the most popular Node.js framework. It powers the "E" in MERN.

### 📚 Sub-topics
- What Express adds over raw Node `http` module
- Installing: `npm install express`
- `app.get()`, `app.post()`, `app.put()`, `app.delete()`, `app.patch()`
- Route parameters: `/users/:id`
- Query strings: `/search?q=mern&page=1`
- `req` object: `req.params`, `req.query`, `req.body`, `req.headers`
- `res` object: `res.json()`, `res.send()`, `res.status()`, `res.redirect()`
- Middleware concept: functions with `(req, res, next)`
- `express.json()` middleware for parsing request body

### ⏱ Time Breakdown
| Time | Activity |
|------|----------|
| 0–2 hrs | Express crash course |
| 2–3.5 hrs | Build routes for a products API |
| 3.5–5 hrs | Middleware practice |
| 5–6 hrs | Test with Thunder Client / Postman |

### 🔗 Professional Resources
- 📺 **[Express JS Crash Course – Traversy Media](https://www.youtube.com/watch?v=L72fhGm1tfE)**
- 📺 **[Node & Express – freeCodeCamp](https://www.youtube.com/watch?v=Oe421EPjeBE)**
- 📺 **[Express Tutorial – The Net Ninja](https://www.youtube.com/playlist?list=PL4cUxeGkcC9jszmQoCs0VGnjgOZKMMnvL)**
- 🌐 **[Express.js Official Docs](https://expressjs.com/)**
- 🌐 **[Postman Docs](https://learning.postman.com/docs/getting-started/introduction/)**

### 💻 Coding Practice
```javascript
// Build a complete products REST API (in-memory array, no DB yet):
// GET    /api/products        → all products
// GET    /api/products/:id    → single product
// POST   /api/products        → create product
// PUT    /api/products/:id    → update product
// DELETE /api/products/:id    → delete product

// Add middleware: request logger (log method, url, timestamp for every request)
```

### 📝 Notes & Tips
> 💡 Test every route in Postman or Thunder Client as you build it. Don't wait until the end. This habit will save you hours of debugging.

---

## DAY 9 → Express.js — Middleware, Router, Error Handling

### 🎯 Topics to Learn
Production-grade Express architecture that companies actually use.

### 📚 Sub-topics
- Built-in middleware: `express.json()`, `express.urlencoded()`, `express.static()`
- Third-party middleware: `cors`, `helmet`, `morgan`, `dotenv`
- Custom middleware: authentication guards, loggers, validators
- `express.Router()` — modular routing
- Centralized error handling middleware (`err, req, res, next`)
- 404 handler
- Environment variables with `dotenv`
- `process.env.NODE_ENV`

### ⏱ Time Breakdown
| Time | Activity |
|------|----------|
| 0–1.5 hrs | Middleware deep dive |
| 1.5–3 hrs | Router modularization |
| 3–4.5 hrs | Error handling + dotenv |
| 4.5–6 hrs | Refactor Day 8 API |

### 🔗 Professional Resources
- 📺 **[Express Middleware – The Net Ninja](https://www.youtube.com/watch?v=UEaWvsCOObU)**
- 🌐 **[dotenv npm package](https://www.npmjs.com/package/dotenv)**
- 🌐 **[cors npm package](https://www.npmjs.com/package/cors)**
- 🌐 **[helmet npm package](https://helmetjs.github.io/)**

### 💻 Coding Practice
```javascript
// Refactor your Day 8 API with:
// 1. Separate router files: routes/products.js, routes/users.js
// 2. Middleware folder: middleware/logger.js, middleware/errorHandler.js
// 3. .env file with PORT=5000
// 4. cors + helmet + morgan middleware
// 5. Global error handler that returns { success: false, message: "..." }

// Folder structure:
// server/
// ├── routes/
// ├── middleware/
// ├── controllers/
// ├── .env
// ├── .gitignore   (include .env!)
// └── server.js
```

---

## DAY 10 → MongoDB — The Database

### 🎯 Topics to Learn
MongoDB is the "M" in MERN. It's a NoSQL document database.

### 📚 Sub-topics
- SQL vs NoSQL — when to use what
- MongoDB concepts: documents, collections, databases
- Installing MongoDB + MongoDB Compass (GUI)
- MongoDB Atlas (cloud) setup — free tier
- Basic CRUD in MongoDB shell: `insertOne`, `find`, `updateOne`, `deleteOne`
- Filters, projections, sorting, limiting
- Data modeling in MongoDB — embedding vs referencing
- Indexes — why they matter for performance

### ⏱ Time Breakdown
| Time | Activity |
|------|----------|
| 0–1.5 hrs | MongoDB concepts + setup |
| 1.5–3 hrs | CRUD operations in Compass |
| 3–4.5 hrs | MongoDB Atlas cloud setup |
| 4.5–6 hrs | Data modeling practice |

### 🔗 Professional Resources
- 📺 **[MongoDB Crash Course – Traversy Media](https://www.youtube.com/watch?v=-56x56UppqQ)**
- 📺 **[MongoDB Full Course – freeCodeCamp](https://www.youtube.com/watch?v=ExcRbA7fy_A)**
- 📺 **[MongoDB Tutorial – CodeWithHarry](https://www.youtube.com/watch?v=oSIv-E60NiU)**
- 🌐 **[MongoDB Official Docs](https://www.mongodb.com/docs/)**
- 🌐 **[MongoDB Atlas](https://www.mongodb.com/cloud/atlas)**
- 🌐 **[MongoDB University (Free Courses)](https://university.mongodb.com/)**

### 💻 Coding Practice
- Create an Atlas cluster and connect via Compass
- Design a blog database schema: users, posts, comments
- Write 10 queries: find by field, sort, limit, filter by date range
- Practice: What's the difference between embedding comments in posts vs separate collection?

---

## DAY 11 → Mongoose — MongoDB + Node.js Integration

### 🎯 Topics to Learn
Mongoose is the ORM/ODM that makes MongoDB feel elegant in Node.js.

### 📚 Sub-topics
- What is an ODM? Mongoose vs native MongoDB driver
- `mongoose.connect()` with Atlas URI
- Defining Schemas — types, required, default, enum, min/max
- Creating Models from schemas
- CRUD with Mongoose: `Model.create()`, `Model.find()`, `Model.findById()`, `Model.findByIdAndUpdate()`, `Model.findByIdAndDelete()`
- Schema validation — built-in + custom validators
- Virtuals and instance methods
- Population — `ref` and `.populate()`
- Mongoose middleware (pre/post hooks)

### ⏱ Time Breakdown
| Time | Activity |
|------|----------|
| 0–2 hrs | Mongoose crash course |
| 2–3.5 hrs | Build User + Post models |
| 3.5–5 hrs | CRUD with Mongoose |
| 5–6 hrs | Populate + validation |

### 🔗 Professional Resources
- 📺 **[Mongoose Crash Course – Traversy Media](https://www.youtube.com/watch?v=DZBGEVgL2eE)**
- 📺 **[Mongoose + MongoDB – The Net Ninja](https://www.youtube.com/playlist?list=PL4cUxeGkcC9h77dJ-QJlwGlZlTd4ecZOA)**
- 🌐 **[Mongoose Official Docs](https://mongoosejs.com/docs/)**

### 💻 Coding Practice
```javascript
// Build User + Post Schema with:
// User: name (required), email (unique, required), password, role (enum: user/admin), createdAt
// Post: title, body, author (ref: User), tags ([String]), likes (Number), published (Boolean)

// Then write:
// 1. Create a user
// 2. Create 3 posts for that user
// 3. Find all published posts with author's name populated
// 4. Update post's likes count
// 5. Delete a post
```

---

## DAY 12 → REST API Design + Full CRUD API with MongoDB

### 🎯 Topics to Learn
Combine Express + Mongoose to build a production-quality REST API.

### 📚 Sub-topics
- REST API principles: stateless, uniform interface, resource-based URLs
- HTTP status codes: 200, 201, 400, 401, 403, 404, 409, 500
- API response structure best practices: `{ success, data, message }`
- Controller pattern — separating route handlers from route definitions
- MVC architecture in Express (Model-View-Controller)
- Input validation with `express-validator` or `joi`
- Async error handling with `express-async-errors` package

### ⏱ Time Breakdown
| Time | Activity |
|------|----------|
| 0–1.5 hrs | REST API design principles |
| 1.5–3.5 hrs | Build full API with controllers |
| 3.5–5 hrs | Input validation |
| 5–6 hrs | Test entire API in Postman |

### 🔗 Professional Resources
- 📺 **[REST API Design – Traversy Media](https://www.youtube.com/watch?v=Q-BpqyOT3a8)**
- 🌐 **[REST API Best Practices – GitHub](https://github.com/atinux/express-api-best-practices)**
- 🌐 **[HTTP Status Codes Reference](https://httpstatuses.io/)**
- 🌐 **[joi validation docs](https://joi.dev/api/)**
- 🌐 **[Postman Learning Center](https://learning.postman.com/)**

### 💻 Coding Practice
```
Build a Posts API with MVC structure:
📁 models/Post.js
📁 controllers/postController.js
📁 routes/postRoutes.js
📁 middleware/validatePost.js

Endpoints:
GET    /api/posts?page=1&limit=10&sort=newest
GET    /api/posts/:id
POST   /api/posts  (validate: title required, body min 50 chars)
PUT    /api/posts/:id
DELETE /api/posts/:id
GET    /api/posts?category=tech (filtering)
```

---

## DAY 13 → Authentication — JWT + bcrypt + Cookies

### 🎯 Topics to Learn
Authentication is in every production app. JWT is the standard in MERN.

### 📚 Sub-topics
- Password hashing with `bcryptjs` — `hash()`, `compare()`
- What is JWT? Header.Payload.Signature structure
- `jsonwebtoken` — `sign()`, `verify()`
- Access tokens vs Refresh tokens
- Sending JWT in response body vs HTTP-only cookies
- Auth middleware — protecting routes
- User registration + login endpoints
- `req.user` pattern

### ⏱ Time Breakdown
| Time | Activity |
|------|----------|
| 0–1.5 hrs | JWT + bcrypt concepts |
| 1.5–3.5 hrs | Build register/login endpoints |
| 3.5–5 hrs | Protect routes with auth middleware |
| 5–6 hrs | Test auth flow in Postman |

### 🔗 Professional Resources
- 📺 **[JWT Authentication – Traversy Media](https://www.youtube.com/watch?v=mbsmsi7l3r4)**
- 📺 **[Node.js Auth with JWT – The Net Ninja](https://www.youtube.com/playlist?list=PL4cUxeGkcC9iqqESP8335DA5cRFp8loyp)**
- 🌐 **[bcryptjs npm](https://www.npmjs.com/package/bcryptjs)**
- 🌐 **[jsonwebtoken npm](https://www.npmjs.com/package/jsonwebtoken)**
- 🌐 **[JWT.io — Decode & Debug JWTs](https://jwt.io/)**

### 💻 Coding Practice
```javascript
// Build complete auth system:
// POST /api/auth/register → hash password, save user, return JWT
// POST /api/auth/login    → compare password, return JWT
// GET  /api/auth/me       → protected route (requires valid JWT)

// Middleware: authMiddleware.js
// - Extract Bearer token from Authorization header
// - Verify JWT
// - Attach decoded user to req.user
// - Call next() or return 401

// Test: Register → Login → Get JWT → Access protected route
```

---

## DAY 14 → WEEK 2 PROJECT — Full Blog REST API

### 🎯 Project: Production-Ready Blog API with Auth

### 📚 Features
- User registration + login (JWT auth)
- Create, read, update, delete blog posts (author only)
- Public posts list with pagination + filtering by category
- Comments on posts (nested data)
- Like/unlike posts
- Protected routes — only authenticated users can create/update/delete

### 📁 Project Structure
```
blog-api/
├── models/
│   ├── User.js
│   ├── Post.js
│   └── Comment.js
├── routes/
│   ├── authRoutes.js
│   ├── postRoutes.js
│   └── commentRoutes.js
├── controllers/
├── middleware/
│   ├── authMiddleware.js
│   └── errorHandler.js
├── config/
│   └── db.js
├── .env
└── server.js
```

### 📤 Submission
- Push to GitHub with full README documenting all endpoints
- Export Postman collection and include in repo
- Deploy to Render (free tier) — link in README

---
---

# 🟩 WEEK 3 — React.js Fundamentals + Hooks + TailwindCSS

---

## DAY 15 → React.js — Why React? JSX + Components

### 🎯 Topics to Learn
React is the "R" in MERN. It's the most popular frontend library used by companies worldwide.

### 📚 Sub-topics
- Why React? Virtual DOM, component reusability, unidirectional data flow
- Create React App (CRA) vs Vite — use Vite (faster, industry standard now)
- JSX — JavaScript + HTML syntax rules
- Functional components
- Props — passing data to components, prop types
- Default props
- Component composition — building complex UI from small pieces
- Conditional rendering: `&&`, ternary, early return
- Rendering lists with `.map()` + `key` prop (why it matters)

### ⏱ Time Breakdown
| Time | Activity |
|------|----------|
| 0–2 hrs | React fundamentals (Traversy or The Net Ninja) |
| 2–3.5 hrs | Build 10 small components |
| 3.5–5 hrs | TailwindCSS setup + basic styling |
| 5–6 hrs | Practice tasks |

### 🔗 Professional Resources
- 📺 **[React JS Crash Course – Traversy Media](https://www.youtube.com/watch?v=w7ejDZ8SWv8)**
- 📺 **[React Tutorial – The Net Ninja](https://www.youtube.com/playlist?list=PL4cUxeGkcC9gZD-Tvwfod2gaISzfRiP9d)**
- 📺 **[React 2024 – Hitesh Choudhary](https://www.youtube.com/watch?v=SqcY0GlETPk)**
- 🌐 **[React Official Docs (react.dev)](https://react.dev/)** ← Redesigned, modern, excellent
- 🌐 **[Vite Official Docs](https://vitejs.dev/guide/)**
- 🌐 **[TailwindCSS Docs](https://tailwindcss.com/docs)**

### 💻 Coding Practice
```bash
# Setup: npm create vite@latest my-app -- --template react
# Install Tailwind: follow tailwindcss.com/docs/guides/vite

# Build these components:
# 1. Navbar with responsive menu items
# 2. Hero section with CTA button
# 3. Card component accepting title, description, image props
# 4. Footer with links
# 5. Product list (map over array of 5 products → Card components)
```

---

## DAY 16 → React Hooks — useState + useEffect

### 🎯 Topics to Learn
Hooks are what make functional components powerful. `useState` and `useEffect` are used in nearly every React app.

### 📚 Sub-topics
- `useState` — declaring state, setter function, re-render cycle
- State is immutable — never mutate directly
- Managing arrays/objects in state (spread operator pattern)
- `useEffect` — side effects in React
- Dependency array: `[]` (on mount), `[dep]` (on change), no array (every render)
- Cleanup functions in useEffect (clearing timeouts, unsubscribing)
- Fetching data with useEffect + async/await
- Loading/error states pattern

### ⏱ Time Breakdown
| Time | Activity |
|------|----------|
| 0–2 hrs | useState + useEffect deep dive |
| 2–4 hrs | Build 3 practical examples |
| 4–5.5 hrs | Data fetching with useEffect |
| 5.5–6 hrs | Code review + refactor |

### 🔗 Professional Resources
- 📺 **[React Hooks – The Net Ninja](https://www.youtube.com/playlist?list=PL4cUxeGkcC9hNokByJilPg5g9m2APUePI)**
- 📺 **[useState & useEffect – Codevolution](https://www.youtube.com/playlist?list=PLC3y8-rFHvwgg3vaYJgHGnModB54rxOk3)**
- 🌐 **[react.dev – useState](https://react.dev/reference/react/useState)**
- 🌐 **[react.dev – useEffect](https://react.dev/reference/react/useEffect)**

### 💻 Coding Practice
```jsx
// Build 1: Todo App with useState
// - Add todo, mark complete, delete todo, filter (all/active/completed)
// - Count of remaining todos

// Build 2: Weather Fetcher with useEffect
// - Input: city name
// - Fetch from: https://wttr.in/{city}?format=j1
// - Show temp, condition, loading spinner, error state

// Build 3: Auto-saving form
// - useEffect watches form changes → save to localStorage after 2s
// - Show "Saved ✓" indicator
```

---

## DAY 17 → React Hooks — useRef, useMemo, useCallback + Context API

### 🎯 Topics to Learn
These hooks prevent performance issues and are asked in React interviews.

### 📚 Sub-topics
- `useRef` — accessing DOM elements, persisting values without re-render
- `useMemo` — memoizing expensive calculations
- `useCallback` — memoizing functions (prevent child re-renders)
- `React.memo` — memoizing components
- When NOT to memoize (premature optimization)
- Context API — creating context, Provider, `useContext`
- When to use Context vs prop drilling vs state management

### ⏱ Time Breakdown
| Time | Activity |
|------|----------|
| 0–1.5 hrs | useRef + useMemo + useCallback |
| 1.5–3 hrs | Context API deep dive |
| 3–4.5 hrs | Build theme switcher with Context |
| 4.5–6 hrs | Performance optimization practice |

### 🔗 Professional Resources
- 📺 **[React Performance Hooks – Codevolution](https://www.youtube.com/playlist?list=PLC3y8-rFHvwgg3vaYJgHGnModB54rxOk3)**
- 📺 **[Context API – The Net Ninja](https://www.youtube.com/watch?v=5LrDIWkK_Bc)**
- 🌐 **[react.dev – useContext](https://react.dev/reference/react/useContext)**

### 💻 Coding Practice
```jsx
// Task 1: Build a Theme Context
// - ThemeContext with dark/light mode
// - Toggle button in Navbar
// - All components read from context (not props)

// Task 2: useRef stopwatch
// - Start/Stop/Reset buttons
// - Interval stored in ref (not state) to avoid stale closure bug

// Task 3: useMemo performance
// - List of 10,000 numbers, filter by search term
// - Show render count — prove useMemo reduces renders
```

---

## DAY 18 → React Router v6 — Client-Side Routing

### 🎯 Topics to Learn
Multi-page React apps require React Router. This is essential for every MERN project.

### 📚 Sub-topics
- `react-router-dom` v6 — installation, `BrowserRouter`
- `<Routes>` + `<Route>` — defining pages
- `<Link>` vs `<NavLink>` — active styling with NavLink
- `useNavigate` — programmatic navigation
- `useParams` — reading URL parameters
- `useSearchParams` — reading query strings
- Nested routes + `<Outlet>`
- Protected routes — redirect if not logged in
- `<Navigate>` component
- 404 Not Found route

### ⏱ Time Breakdown
| Time | Activity |
|------|----------|
| 0–2 hrs | React Router v6 full tutorial |
| 2–3.5 hrs | Build multi-page app |
| 3.5–5 hrs | Nested routes + protected routes |
| 5–6 hrs | Refactor blog frontend with routing |

### 🔗 Professional Resources
- 📺 **[React Router v6 – The Net Ninja](https://www.youtube.com/playlist?list=PL4cUxeGkcC9jERK9ZpJaKQShBjCgtkZ4w)**
- 📺 **[React Router Tutorial – Traversy Media](https://www.youtube.com/watch?v=Law7wfdg_ls)**
- 🌐 **[React Router v6 Official Docs](https://reactrouter.com/)**

### 💻 Coding Practice
```jsx
// Build a blog frontend with routes:
// /            → Home (list of posts)
// /post/:id    → Single post page
// /create      → Create post (protected)
// /login       → Login page
// /profile     → Profile (protected)
// *            → 404 page

// ProtectedRoute component:
// - If no token in localStorage → redirect to /login
// - Otherwise → render children
```

---

## DAY 19 → TailwindCSS — Professional UI Design

### 🎯 Topics to Learn
Tailwind is the most popular CSS framework in the MERN ecosystem.

### 📚 Sub-topics
- Utility-first CSS philosophy
- Responsive breakpoints: `sm:`, `md:`, `lg:`, `xl:`
- Flexbox utilities: `flex`, `justify-*`, `items-*`, `gap-*`
- Grid utilities: `grid`, `grid-cols-*`
- Spacing: `p-`, `m-`, `px-`, `py-`, `mx-auto`
- Typography: `text-*`, `font-*`, `leading-*`
- Colors, backgrounds, borders, shadows
- Hover/focus/active states: `hover:`, `focus:`
- Dark mode with `dark:` prefix
- Custom config with `tailwind.config.js`
- Component patterns: cards, buttons, forms, navbars, modals

### ⏱ Time Breakdown
| Time | Activity |
|------|----------|
| 0–2 hrs | Tailwind crash course |
| 2–4 hrs | Build 5 UI components with Tailwind |
| 4–6 hrs | Style your blog frontend from Day 18 |

### 🔗 Professional Resources
- 📺 **[Tailwind CSS Crash Course – Traversy Media](https://www.youtube.com/watch?v=dFgzHOX84xQ)**
- 📺 **[Tailwind Full Course – Dave Gray](https://www.youtube.com/watch?v=lCxcTsOHrjo)**
- 🌐 **[TailwindCSS Official Docs](https://tailwindcss.com/docs)**
- 🌐 **[Tailwind UI Components (free)](https://tailwindui.com/components#free-components)**
- 🌐 **[Flowbite – Free Tailwind Components](https://flowbite.com/docs/getting-started/introduction/)**
- 🌐 **[shadcn/ui – Best component library for React + Tailwind](https://ui.shadcn.com/)**

### 💻 Coding Practice
- Build: Responsive Navbar (hamburger menu on mobile)
- Build: Blog post card with image, author, date, tags
- Build: Contact form with validation styles (error states)
- Build: Dark mode toggle using Tailwind `dark:` classes

---

## DAY 20 → React — Forms, Axios, Custom Hooks

### 🎯 Topics to Learn
Controlled forms and HTTP requests are in every React app.

### 📚 Sub-topics
- Controlled components — `value` + `onChange`
- Uncontrolled components + `useRef`
- Form validation — manual vs library (React Hook Form)
- `react-hook-form` — the standard for forms in 2024
- Axios — `axios.get()`, `axios.post()`, `axios.put()`, `axios.delete()`
- Axios interceptors — add JWT header to every request automatically
- Setting up Axios base URL with `axios.create()`
- Custom hooks — extracting reusable logic
- `useFetch` custom hook example

### ⏱ Time Breakdown
| Time | Activity |
|------|----------|
| 0–1.5 hrs | Controlled forms + react-hook-form |
| 1.5–3 hrs | Axios setup + interceptors |
| 3–4.5 hrs | Custom hooks |
| 4.5–6 hrs | Connect blog frontend to blog API |

### 🔗 Professional Resources
- 📺 **[React Hook Form Tutorial – ByteGrad](https://www.youtube.com/watch?v=RkXv4AXXC_4)**
- 📺 **[Axios Tutorial – The Net Ninja](https://www.youtube.com/watch?v=qM4G1Ai2ZpE)**
- 🌐 **[React Hook Form Docs](https://react-hook-form.com/)**
- 🌐 **[Axios Docs](https://axios-http.com/docs/intro)**

### 💻 Coding Practice
```jsx
// Build: Register/Login forms using react-hook-form
// - Email validation (regex)
// - Password min 6 characters
// - Confirm password must match
// - Loading state during API call
// - Show error messages from API

// Build: useFetch custom hook
// const { data, loading, error } = useFetch(url);

// Build: useLocalStorage custom hook
// const [value, setValue] = useLocalStorage('key', defaultValue);
```

---

## DAY 21 → WEEK 3 PROJECT — React Blog Frontend

### 🎯 Project: Full React Frontend for your Blog API

### 📚 Features
- Home page — list all posts (paginated)
- Single post page — full post with comments
- Register + Login pages (JWT auth)
- Create/Edit post (protected, author only)
- User profile page
- Dark mode toggle
- Search + filter by category
- Loading skeletons (better UX than spinner)
- 404 page

### 📁 Project Structure
```
blog-frontend/
├── src/
│   ├── components/
│   │   ├── Navbar.jsx
│   │   ├── PostCard.jsx
│   │   ├── CommentSection.jsx
│   │   └── ProtectedRoute.jsx
│   ├── pages/
│   │   ├── Home.jsx
│   │   ├── Post.jsx
│   │   ├── Login.jsx
│   │   ├── Register.jsx
│   │   └── CreatePost.jsx
│   ├── hooks/
│   │   ├── useFetch.js
│   │   └── useAuth.js
│   ├── context/
│   │   └── AuthContext.jsx
│   ├── api/
│   │   └── axios.js    (configured Axios instance)
│   └── App.jsx
├── tailwind.config.js
└── vite.config.js
```

---
---

# 🟥 WEEK 4 — Full-Stack Integration + Deployment + Advanced Topics

---

## DAY 22 → Connecting Frontend + Backend (CORS, Proxy, Environment Variables)

### 🎯 Topics to Learn
The most common stumbling block when first building full-stack MERN apps.

### 📚 Sub-topics
- CORS — why it happens, how to fix it in Express
- Proxy setup in Vite for development (`vite.config.js`)
- Environment variables in React (`VITE_API_URL`)
- `.env` files: `.env.local`, `.env.production`
- Serving React build from Express (for deployment)
- API URL management — dev vs production
- State management overview: Context API vs Redux vs Zustand
- Zustand — lightweight state management (industry favorite in 2024)

### ⏱ Time Breakdown
| Time | Activity |
|------|----------|
| 0–1.5 hrs | CORS + proxy setup |
| 1.5–3 hrs | Environment variables |
| 3–4.5 hrs | Zustand state management |
| 4.5–6 hrs | Integrate frontend + backend |

### 🔗 Professional Resources
- 📺 **[Zustand Tutorial – Jack Herrington](https://www.youtube.com/watch?v=_ngCLZ5Iz-0)**
- 🌐 **[Zustand Docs](https://zustand-demo.pmnd.rs/)**
- 🌐 **[Vite Proxy Config](https://vitejs.dev/config/server-options.html#server-proxy)**

### 💻 Coding Practice
- Move your blog's auth state to Zustand
- Fix all CORS errors between frontend (port 5173) and backend (port 5000)
- Set up proxy in vite.config.js: `/api` → `http://localhost:5000`

---

## DAY 23 → Advanced Auth — Refresh Tokens + Role-Based Access + Cookies

### 🎯 Topics to Learn
Production-grade authentication that companies actually implement.

### 📚 Sub-topics
- Access token (short-lived, 15 min) vs Refresh token (long-lived, 7 days)
- Storing tokens securely: HTTP-only cookies vs localStorage (security comparison)
- `cookie-parser` middleware in Express
- Refresh token endpoint — issue new access token
- Role-based access control (RBAC): `user`, `moderator`, `admin` roles
- `authorize(roles)` middleware — restrict routes by role
- Password reset flow (conceptual + implementation)
- Rate limiting with `express-rate-limit`

### ⏱ Time Breakdown
| Time | Activity |
|------|----------|
| 0–2 hrs | Refresh token + cookie auth |
| 2–3.5 hrs | RBAC implementation |
| 3.5–5 hrs | Rate limiting + security headers |
| 5–6 hrs | Test complete auth flow |

### 🔗 Professional Resources
- 📺 **[Refresh Tokens + HTTP Cookies – Dave Gray](https://www.youtube.com/watch?v=favjC6EKFgw)**
- 🌐 **[express-rate-limit npm](https://www.npmjs.com/package/express-rate-limit)**
- 🌐 **[OWASP Auth Cheatsheet](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html)**

---

## DAY 24 → Image Upload — Cloudinary + Multer

### 🎯 Topics to Learn
Almost every real app needs image upload. This is Cloudinary + Multer — the standard MERN combination.

### 📚 Sub-topics
- `multer` — middleware for handling `multipart/form-data`
- Storing files in memory vs disk
- Cloudinary — cloud image storage, free tier, transformation URLs
- `cloudinary` npm package — upload from Node.js
- Deleting images from Cloudinary
- Frontend: `<input type="file">` + FormData API
- Image preview before upload with `URL.createObjectURL()`
- Storing Cloudinary URL in MongoDB

### ⏱ Time Breakdown
| Time | Activity |
|------|----------|
| 0–1.5 hrs | Multer setup |
| 1.5–3 hrs | Cloudinary integration |
| 3–4.5 hrs | Frontend file upload |
| 4.5–6 hrs | Add avatar upload to your blog |

### 🔗 Professional Resources
- 📺 **[File Upload with Multer + Cloudinary – Traversy Media](https://www.youtube.com/watch?v=GML5jUkYJrY)**
- 🌐 **[Cloudinary Docs](https://cloudinary.com/documentation)**
- 🌐 **[multer npm](https://www.npmjs.com/package/multer)**

---

## DAY 25 → Deployment — Vercel + Render + MongoDB Atlas

### 🎯 Topics to Learn
A project that isn't deployed doesn't exist. Deployment is a must-have skill.

### 📚 Sub-topics
- Deploying React frontend to **Vercel** (zero-config for Vite)
- Deploying Express backend to **Render** (free tier)
- Deploying Express backend to **Railway** (alternative)
- MongoDB Atlas — whitelist all IPs for production (`0.0.0.0/0`)
- Environment variables on Vercel and Render dashboards
- Build scripts — `npm run build` for React
- CORS configuration for production domains
- Custom domain setup (Vercel)
- `vercel.json` for SPA routing fix

### ⏱ Time Breakdown
| Time | Activity |
|------|----------|
| 0–1.5 hrs | Render backend deployment |
| 1.5–3 hrs | Vercel frontend deployment |
| 3–4.5 hrs | Environment variables + CORS fix |
| 4.5–6 hrs | Deploy your blog project end-to-end |

### 🔗 Professional Resources
- 📺 **[Deploy MERN to Render & Vercel – Traversy Media](https://www.youtube.com/watch?v=l134cBAJCuc)**
- 📺 **[Vercel Deployment – Web Dev Simplified](https://www.youtube.com/watch?v=UrBUFcBbW30)**
- 🌐 **[Vercel Docs](https://vercel.com/docs)**
- 🌐 **[Render Docs](https://render.com/docs)**

### 💻 Coding Practice
- Deploy backend API → `https://your-api.onrender.com`
- Deploy frontend → `https://your-blog.vercel.app`
- Update frontend `.env.production` with production API URL
- Verify all features work on production

---

## DAY 26 → Advanced React — Performance + Testing Basics + React Query

### 🎯 Topics to Learn
What separates junior React developers from mid-level.

### 📚 Sub-topics
- React Query (TanStack Query) — server state management
  - `useQuery`, `useMutation`, automatic caching + refetching
- Code splitting with `React.lazy` + `Suspense`
- Error boundaries
- React DevTools — profiling performance
- `React.memo` best practices
- Infinite scrolling with `useInfiniteQuery`
- Testing basics: `jest`, `@testing-library/react`
  - Rendering components, firing events, asserting output

### ⏱ Time Breakdown
| Time | Activity |
|------|----------|
| 0–2 hrs | React Query fundamentals |
| 2–3.5 hrs | Code splitting + Suspense |
| 3.5–5 hrs | Basic testing setup |
| 5–6 hrs | Refactor blog to use React Query |

### 🔗 Professional Resources
- 📺 **[React Query – Codevolution](https://www.youtube.com/playlist?list=PLC3y8-rFHvwjTELCrPrcZlo6blLBUspd2)**
- 🌐 **[TanStack Query Docs](https://tanstack.com/query/v5)**
- 🌐 **[Testing Library Docs](https://testing-library.com/docs/react-testing-library/intro/)**

---

## DAY 27 → System Design Basics + API Documentation + Postman Collections

### 🎯 Topics to Learn
Technical interviews and senior roles require system design knowledge.

### 📚 Sub-topics
- System design fundamentals: scalability, load balancing (conceptual)
- Client-server model, CDN, caching strategies
- Database indexing — how MongoDB indexes work
- API versioning: `/api/v1/`, `/api/v2/`
- API documentation with Swagger / OpenAPI
- `swagger-ui-express` + `swagger-jsdoc` for Express
- Postman collections — sharing and documenting APIs
- Rate limiting strategies
- Horizontal vs vertical scaling (conceptual)

### ⏱ Time Breakdown
| Time | Activity |
|------|----------|
| 0–1.5 hrs | System design basics |
| 1.5–3 hrs | Add Swagger docs to your blog API |
| 3–4.5 hrs | Create Postman collection |
| 4.5–6 hrs | MongoDB indexes for your schemas |

### 🔗 Professional Resources
- 📺 **[System Design for Beginners – Neetcode](https://www.youtube.com/watch?v=i53Gi_K3o7I)**
- 📺 **[System Design Primer – Gaurav Sen](https://www.youtube.com/c/GauravSensei)**
- 🌐 **[swagger-ui-express npm](https://www.npmjs.com/package/swagger-ui-express)**

---

## DAY 28–29 → FINAL PROJECT — Full-Stack MERN App (2 days)

### 🎯 Project: DevConnect — A Developer Portfolio + Social Network

This is your capstone project for your GitHub portfolio.

### 📚 Core Features
**Auth:** Register, Login (JWT + HTTP-only cookies), Logout, Profile avatar upload (Cloudinary)

**Developer Profiles:** Create/Edit profile (bio, skills, social links, GitHub URL), Public profile page at `/profile/:username`

**Posts/Feed:** Create posts with image, Like/unlike, Comment, Delete own posts, Paginated feed

**Dashboard:** Private dashboard showing your profile completeness, your posts, activity

**Admin Panel:** View all users, deactivate accounts (RBAC)

### 📁 Final Architecture
```
devconnect/
├── backend/
│   ├── models/        (User, Post, Comment)
│   ├── routes/        (auth, users, posts, admin)
│   ├── controllers/
│   ├── middleware/    (auth, rbac, upload, errorHandler)
│   ├── config/        (db.js, cloudinary.js)
│   ├── utils/         (generateToken.js, sendEmail.js)
│   └── server.js
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── store/     (Zustand stores)
│   │   ├── hooks/
│   │   ├── api/       (Axios instances)
│   │   └── App.jsx
│   └── tailwind.config.js
└── README.md          (Full documentation with live demo link)
```

### 🛠 Tech Stack Used
MongoDB Atlas · Express.js · React.js (Vite) · Node.js · TailwindCSS · JWT + Refresh Tokens · Cloudinary · Vercel (frontend) · Render (backend) · React Query · Zustand · React Router v6 · react-hook-form

---

## DAY 30 → Deployment + Portfolio Polish + What's Next

### 🎯 Day 30 Tasks

**Morning (3 hrs) — Final Deployment**
- Deploy backend to Render with all environment variables
- Deploy frontend to Vercel connected to production API
- Test all features on production URL
- Fix production-only bugs (CORS, env vars, Atlas IP whitelist)

**Afternoon (3 hrs) — Portfolio Polish**
- Write a comprehensive README with: screenshots, live demo link, features list, local setup guide, API documentation link
- Record a 2-3 minute demo video (use Loom — free)
- Pin the project on GitHub profile
- Update LinkedIn with the live project link
- Write a LinkedIn post about your 30-day journey (this gets recruiter attention)

### 📚 What to Learn Next (Week 5+)
- **TypeScript** — add types to your MERN apps
- **Redux Toolkit** — for complex state
- **Next.js** — SSR/SSG, used in most React companies
- **GraphQL + Apollo** — alternative to REST
- **Docker + CI/CD** — DevOps basics
- **WebSockets / Socket.io** — real-time features
- **Redis** — caching and session management

### 🔗 Resources
- 📺 **[Next.js – JavaScript Mastery](https://www.youtube.com/watch?v=wm5gMKuwSYk)**
- 📺 **[TypeScript for React – Jack Herrington](https://www.youtube.com/watch?v=ydkQlJhodio)**
- 🌐 **[Roadmap.sh – Full Stack](https://roadmap.sh/full-stack)**

---

---

# 🛠️ TOOLING & SUPPORTING TECH GUIDE

## Git & GitHub
- 📺 [Git Crash Course – Traversy Media](https://www.youtube.com/watch?v=SWYqp7iY_Tc)
- 🌐 [Learn Git Branching (Interactive)](https://learngitbranching.js.org/)
- 🌐 [Conventional Commits](https://www.conventionalcommits.org/)
- 🌐 [GitHub Docs](https://docs.github.com/en)

## VS Code Setup
- **Extensions:** ESLint, Prettier, GitLens, Thunder Client, Auto Import, Tailwind CSS IntelliSense, REST Client, Path IntelliSense
- **Settings:** Format on save, tab size 2
- 📺 [VS Code Setup – Traversy Media](https://www.youtube.com/watch?v=fnPhJHN0jfte)

## Postman / Thunder Client
- 🌐 [Postman Learning Center](https://learning.postman.com/)
- **Thunder Client** — VS Code extension, use for quick API testing without leaving VS Code

## TailwindCSS
- 🌐 [Official Docs](https://tailwindcss.com/docs)
- 🌐 [shadcn/ui Components](https://ui.shadcn.com/)
- 🌐 [Tailwind Components (community)](https://www.creative-tim.com/twcomponents/)

## REST API Design
- Use nouns for resources: `/users`, `/posts`, not `/getUsers`
- Use HTTP methods correctly: GET (read), POST (create), PUT (replace), PATCH (partial update), DELETE
- Consistent response format: `{ success: true, data: {...}, message: "..." }`
- Versioning: `/api/v1/`

## JWT + bcrypt
- 🌐 [JWT.io](https://jwt.io/) — Debug your tokens
- 🌐 [bcryptjs npm](https://www.npmjs.com/package/bcryptjs)

## Vercel & Render
- 🌐 [Vercel](https://vercel.com/) — Frontend (React/Vite)
- 🌐 [Render](https://render.com/) — Backend (Node/Express)
- 🌐 [Railway](https://railway.app/) — Full-stack alternative

## Dotenv
```bash
# Install: npm install dotenv
# .env file (never commit this!):
PORT=5000
MONGO_URI=mongodb+srv://...
JWT_SECRET=your_super_secret_key
CLOUDINARY_CLOUD_NAME=...

# In server.js (top of file):
require('dotenv').config()
```

## Environment Variables on Vercel
- Dashboard → Project → Settings → Environment Variables
- Add `VITE_API_URL=https://your-api.onrender.com`

---
---

# 📊 FINAL SUMMARY TABLE

| Day | MERN Topic | DSA Topic |
|-----|-----------|-----------|
| 1 | ES6+ JavaScript | Arrays + Two Pointers |
| 2 | Async JS (Promises, Async/Await) | Sorting + Kadane's |
| 3 | Arrays, Objects, Functional JS | Strings |
| 4 | Git & GitHub | Sliding Window |
| 5 | Node.js Basics | HashMap |
| 6 | Node.js Modules + Events | Linked List Basics |
| 7 | **Project: CLI Task Manager** | Linked List Advanced |
| 8 | Express.js Basics | Stack |
| 9 | Express Middleware + Router | Queue + Deque |
| 10 | MongoDB Basics | Binary Search |
| 11 | Mongoose ODM | Recursion + Backtracking |
| 12 | REST API Design | Binary Trees |
| 13 | JWT Auth + bcrypt | Binary Trees Advanced |
| 14 | **Project: Blog REST API** | BST |
| 15 | React.js + JSX + Components | Heap/Priority Queue |
| 16 | useState + useEffect | Graphs BFS/DFS |
| 17 | useRef, useMemo, Context API | Graphs Shortest Path |
| 18 | React Router v6 | DP Introduction |
| 19 | TailwindCSS | DP 2D Grid |
| 20 | Forms + Axios + Custom Hooks | DP Knapsack |
| 21 | **Project: React Blog Frontend** | DP LCS |
| 22 | Full-Stack Integration + Zustand | Mixed Practice |
| 23 | Advanced Auth + RBAC | Mixed Practice |
| 24 | Image Upload (Cloudinary) | Mixed Practice |
| 25 | Deployment (Vercel + Render) | Mixed Practice |
| 26 | React Query + Performance | DSA Revision: Arrays |
| 27 | System Design + Swagger | DSA Revision: Trees |
| 28 | **Final Project: DevConnect (Day 1)** | DSA Revision: Graphs + DP |
| 29 | **Final Project: DevConnect (Day 2)** | Mock Interview |
| 30 | Deployment + Portfolio Polish | Final Revision |

---

## 🚀 FINAL PROJECT DEPLOYMENT CHECKLIST

```
Backend (Render):
☐ All env vars set on Render dashboard
☐ MongoDB Atlas IP whitelist: 0.0.0.0/0
☐ CORS origin set to production frontend URL
☐ Health check endpoint: GET /api/health → { status: "ok" }

Frontend (Vercel):
☐ VITE_API_URL set to production backend URL
☐ vercel.json for SPA routing:
   { "rewrites": [{ "source": "/(.*)", "destination": "/" }] }
☐ All console.logs removed from production code

GitHub:
☐ .env in .gitignore (check both repos!)
☐ Professional README with:
   - Live demo link
   - Screenshots/GIF
   - Local setup instructions
   - Tech stack badges
   - API documentation

LinkedIn:
☐ Post with project link + what you learned
☐ Add project to LinkedIn profile
☐ Update "Skills" section: MongoDB, Express, React, Node.js
```

---

*Built for serious learners. Commit to all 30 days — consistency beats intensity. 💪*
*"The best time to start was yesterday. The second best time is now."*
