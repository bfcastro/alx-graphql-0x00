# GraphQL: Get a Specific Episode by ID

## Objective
Fetch the details of a specific episode using its ID with the GraphQL `episode(id: ID!)` field.

## Endpoint
https://rickandmortyapi.com/graphql

## Query Fields
- id  
- name  
- air_date  
- episode

## Example Query
```graphql
query {
  episode(id: 1) {
    id
    name
    air_date
    episode
  }
}
