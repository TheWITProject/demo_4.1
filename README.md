## Summary
You will be demoing a conceptual API design for a zoo application. This is a white boarding exercise, so please use a visual tool like [Ziteboard](ziteboard.com) or [Figma](https://www.figma.com/login).

## Instructions
You will be designing a simple API for a zoo application. [Refer back to the schema we created in last week's class](https://www.notion.so/Lecture-Materials-cecc2c8ff2694955a13c3574cd1a4bce#34bb7f7cf1484f858cb7b8fac16cf1de). Focus on: highlighting the request verbs, URI naming conventions, variable and query parameters, and the request and response bodies.

For each route planned, fill out the following:
```
# VERB /some/path/here/

# REQ BODY:
{...}

# RES BODY:
{...}
```

Some ideas for routes you can demo include:
- How can we get all animals? `GET /animals`

- How can we get a specific animal? `GET /animals/{id}`

- How can we get an animal by name? `GET /animals?name={name}` * highlight return data type here

- How can we get all animals of a specific species? `GET /animals?species={species}`

- How can we add a new animal? `POST /animals`

- How can we edit a specific animal? `PUT /animals/{id}`

- How can we delete a specific animal? `DELETE /animals{id}`

- How can we get all zoos? `GET /zoos`
