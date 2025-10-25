# 🧠 GraphQuest: Exploring and Implementing GraphQL

- **Weight:** 1
- **Project Duration:** October 13, 2025 – October 20, 2025
- **Manual QA Review:** Must be requested after project completion

---

## 🚀 Project Overview & Summary: _The Rick and Morty GraphQL API Explorer_

This project is a **multi-phase learning journey** designed to build proficiency in **GraphQL**, from writing basic queries to integrating them into a modern, full-stack **React (Next.js)** application.  
It leverages the popular [Rick and Morty GraphQL API](https://rickandmortyapi.com/graphql), making the learning experience both engaging and practical.

The work is divided into four distinct directories — **`alx-graphql-0x00`** to **`alx-graphql-0x02`** — each representing a progressive level of complexity and integration.

---

## 🎯 Learning Objectives

### 🧩 Level 0 — GraphQL Fundamentals

Learners will:

- Construct precise GraphQL queries to request specific data.
- Use arguments such as `id` and `page` to filter and paginate results.
- Structure queries to include only the necessary fields (avoiding over-fetching).
- Differentiate between querying a single item and fetching a paginated list.

### ⚛️ Levels 1 & 2 — Frontend Integration

Learners will:

- Set up a **Next.js** project with **TypeScript**, **Apollo Client**, and **Tailwind CSS**.
- Configure **Apollo Client** to connect React to a GraphQL endpoint.
- Use the **`useQuery`** hook to execute GraphQL operations within React components.
- Manage local component state (e.g., for pagination) and trigger refetching when state changes.
- Structure a React app with clear separation of concerns (queries, components, interfaces).

---

## 💡 Key Concepts

- **GraphQL Query Language:** A flexible way to define exactly what data you need — replacing multiple REST endpoints with a single, efficient query.
- **Schema and Types:** The Rick and Morty API defines types like `Character`, `Episode`, and `Info`, which determine the structure of the data.
- **Arguments:** Used to refine queries (e.g., `character(id: 1)` or `episodes(page: 2)`).
- **Pagination:** Implemented through the `Info` type, containing fields like `pages`, `next`, and `prev`.
- **Apollo Client:** Handles data fetching, caching, and state management for GraphQL APIs.
- **React Integration:** Uses `ApolloProvider` to make the client available throughout the app and `useQuery` for fetching data.
- **TypeScript:** Adds static typing and ensures type safety for data structures retrieved from GraphQL.

---

## 🧰 Tools and Libraries

| Category                 | Tool / Library                                                         | Purpose                                   |
| ------------------------ | ---------------------------------------------------------------------- | ----------------------------------------- |
| **Runtime**              | Node.js                                                                | JavaScript runtime environment            |
| **Framework**            | Next.js                                                                | React framework for SSR and routing       |
| **Language**             | TypeScript                                                             | Superset of JavaScript with static typing |
| **GraphQL Client**       | Apollo Client                                                          | Manages GraphQL queries and caching       |
| **GraphQL Core Library** | `graphql`                                                              | Provides GraphQL syntax and utilities     |
| **Styling**              | Tailwind CSS                                                           | Utility-first CSS framework               |
| **Linting**              | ESLint                                                                 | Identifies and fixes code problems        |
| **API**                  | [Rick and Morty GraphQL Endpoint](https://rickandmortyapi.com/graphql) | Data source for the project               |

---

## 🌍 Real-World Applications

This project models the architecture of **real-world web applications**, including:

- 🛒 **E-commerce Product Catalog:** Query products by ID or load paginated product lists.
- 📰 **Blog Platform:** Fetch single articles or paginated lists of posts (similar to `Episode` queries).
- 💬 **Social Media Feed:** Load paginated posts or user profiles.
- 📊 **Data Dashboard:** Display paginated or filtered datasets dynamically.

The skills acquired — **query writing, API integration, and state management** — are foundational for building scalable and performant web apps.

---

## 📝 Project Assessment (Hybrid)

Your project will be evaluated through **manual reviews** and **auto-checks** that ensure required files exist.

### ✅ Requirements:

- Complete all project tasks before the deadline.
- Submit all required files.
- Generate and share your **review link**.
- Request **manual QA review** for final grading.

> ⚠️ **Note:** If the deadline passes, you will not be able to generate a review link — submit on time!

---

## 🧠 Quiz

**Great job!** You’ve completed the quiz successfully. Keep going! 🚀

---

## 📚 Tasks

---

### **3. Application of GraphQL in React** (Mandatory)

**Objective:**  
Kickstart the development of your **Rick and Morty** app using **Next.js**, **TypeScript**, **ESLint**, and **Tailwind CSS**.

#### 🧾 Instructions

1. **Create a project** named `alx-rick-and-morty-app` inside the `alx-graphql-0x01` directory.
2. **Change directory** into the project:
   ```bash
   cd alx-graphql-0x01/alx-rick-and-morty-app
   ```
