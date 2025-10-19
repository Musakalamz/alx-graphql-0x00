# GraphQL Query: Get a List of All Characters

This directory contains GraphQL queries to fetch paginated lists of characters from the **Rick and Morty GraphQL API**.

---

## 🧩 Objective

Write GraphQL queries using the `characters(page: Int)` field to retrieve lists of characters from pages **1**, **2**, **3**, and **4**.

Each query should return the following fields:

- `id`
- `name`
- `status`
- `image`

---

## ⚙️ GraphQL Endpoint

---

## 📄 Files

| File                                                                           | Description                    |
| ------------------------------------------------------------------------------ | ------------------------------ |
| `characters-page-1.graphql`                                                    | Query for page 1 of characters |
| `characters-page-2.graphql`                                                    | Query for page 2 of characters |
| `characters-page-3.graphql`                                                    | Query for page 3 of characters |
| `characters-page-4.graphql`                                                    | Query for page 4 of characters |
| Each corresponding `*.json` file contains the output from the GraphQL endpoint |

---

## 🚀 Example Command

To run any of these queries manually using `curl`:

```bash
curl -X POST -H "Content-Type: application/json" \
  --data '{ "query": "{ characters(page: 1) { results { id name status image } } }" }' \
  https://rickandmortyapi.com/graphql
```
