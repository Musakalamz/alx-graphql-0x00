# GraphQL Query: Get a Specific Episode by ID

This directory contains GraphQL queries to fetch details of specific episodes from the **Rick and Morty GraphQL API**.

---

## 🧩 Objective

Write GraphQL queries using the `episode(id: ID!)` field to retrieve details of episodes by ID.

Each query should return the following fields:

- `id`
- `name`
- `air_date`
- `episode`

---

## ⚙️ GraphQL Endpoint

https://rickandmortyapi.com/graphql

---

## 📄 Files

| File                                                              | Description                 |
| ----------------------------------------------------------------- | --------------------------- |
| `episode-page-1.graphql`                                          | Query for episode with ID 1 |
| `episode-page-2.graphql`                                          | Query for episode with ID 2 |
| `episode-page-3.graphql`                                          | Query for episode with ID 3 |
| `episode-page-4.graphql`                                          | Query for episode with ID 4 |
| Each corresponding `*.json` file contains the API response output |

---

## 🚀 Example Query Command

You can run any query like this:

```bash
curl -X POST -H "Content-Type: application/json" \
  --data '{ "query": "{ episode(id: 1) { id name air_date episode } }" }' \
  https://rickandmortyapi.com/graphql
```
