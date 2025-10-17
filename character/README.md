# GraphQL Character Query

## Objective
Fetch details of a specific character by ID using GraphQL.

## Endpoint
https://rickandmortyapi.com/graphql

## Query Fields
- id
- name
- status
- species
- type
- gender

## Example Query
```graphql
query {
  character(id: 1) {
    id
    name
    status
    species
    type
    gender
  }
}
