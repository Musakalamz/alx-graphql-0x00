# 🧠 GraphQuest: Exploring and Implementing GraphQL

**Weight:** 1  
**Project Duration:**  
📅 **Start:** October 13, 2025 — 12:00 AM  
⏰ **Deadline:** October 20, 2025 — 12:00 AM  
🧾 **Review:** Manual QA (Request when project is complete)

---

## 🚀 Project Overview — _The Rick and Morty GraphQL API Explorer_

**GraphQuest** is a multi-phase learning journey designed to help learners master GraphQL — from writing fundamental queries to integrating them into a modern React (Next.js) frontend using Apollo Client.

We’ll use the **Rick and Morty GraphQL API** as our data source, allowing for a fun and engaging exploration of characters, episodes, and more.

The project is divided into **four directories**, each representing a level of complexity:

- `alx-graphql-0x00` — GraphQL Fundamentals
- `alx-graphql-0x01` — GraphQL Integration in React
- `alx-graphql-0x02` — Querying and Displaying GraphQL Data in a Web App

Each level progressively builds your skills in **data querying, pagination, API integration, and frontend rendering**.

---

## 🎯 Learning Objectives

### 🧩 Level 0: GraphQL Fundamentals

- Write precise GraphQL queries to fetch specific data.
- Use arguments like `id` and `page` to filter or paginate results.
- Request only the necessary fields — avoiding over-fetching.
- Differentiate between fetching a single resource and a paginated list.

### ⚛️ Levels 1 & 2: Frontend Integration

- Set up a **Next.js** app with **TypeScript**, **ESLint**, and **Tailwind CSS**.
- Configure **Apollo Client** to connect React to a GraphQL endpoint.
- Use the **useQuery** hook to execute GraphQL operations in React components.
- Manage **pagination** using local state and dynamic refetching.
- Organize your React app using a clean file structure (queries, interfaces, components).

---

## 💡 Key Concepts

| Concept                    | Description                                                                                     |
| -------------------------- | ----------------------------------------------------------------------------------------------- |
| **GraphQL Query Language** | Defines how clients specify exactly what data they need.                                        |
| **Schema & Types**         | Describe the shape and structure of data (e.g., `Character`, `Episode`, `Info`).                |
| **Arguments**              | Allow precise data requests (e.g., `character(id: 1)` or `episodes(page: 2)`).                  |
| **Pagination**             | Retrieve data in manageable chunks using `info` fields (`pages`, `next`, `prev`).               |
| **Apollo Client**          | A GraphQL client for fetching and caching data efficiently.                                     |
| **React Integration**      | Using `ApolloProvider` to make the client available app-wide, and `useQuery` for data fetching. |
| **TypeScript**             | Adds static typing and interfaces for structured, bug-resistant code.                           |

---

## 🧰 Tools and Libraries

| Category            | Tool / Library                                                    | Description                                          |
| ------------------- | ----------------------------------------------------------------- | ---------------------------------------------------- |
| **Runtime**         | Node.js                                                           | Executes JavaScript outside the browser              |
| **Framework**       | Next.js                                                           | React-based framework for building modern web apps   |
| **Language**        | TypeScript                                                        | Strongly typed superset of JavaScript                |
| **GraphQL Client**  | Apollo Client                                                     | Handles data fetching, caching, and state management |
| **GraphQL Library** | graphql                                                           | Provides GraphQL core utilities                      |
| **Styling**         | Tailwind CSS                                                      | Utility-first CSS framework                          |
| **Linting**         | ESLint                                                            | Enforces coding best practices                       |
| **API Endpoint**    | [Rick and Morty GraphQL API](https://rickandmortyapi.com/graphql) | Provides data for the project                        |

---

## 🌍 Real-World Applications

This project simulates real software development workflows found in:

- 🛒 **E-commerce** — Fetching products by ID or paginated product lists.
- 📰 **Blog/News Platform** — Retrieving a single article or paginated article lists.
- 💬 **Social Media** — Paginating through posts, comments, or users.
- 📊 **Data Dashboards** — Fetching paginated analytics or metrics.

By the end, you’ll have built a mini, **production-style GraphQL + React app**, showcasing how modern frontend apps fetch and manage complex data.

---

## 🧾 Project Assessment

- ✅ Complete all required tasks before the deadline.
- 📂 Submit all necessary files (queries, JSON outputs, and app files).
- 🔗 Generate your **review link** before the due date.
- 👥 Request **manual QA review** once done.

> ⚠️ **Note:** If the deadline passes, you cannot generate your review link — submit on time!

---

## 🧠 Tasks

### 🧩 0. Write a Query to Get a Specific Character by ID

**Objective:** Fetch specific character data using the `character(id: ID!)` field.

**Instructions:**

- Use IDs: `1`, `2`, `3`, `4`
- Fields: `id`, `name`, `status`, `species`, `type`, `gender`
