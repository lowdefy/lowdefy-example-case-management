# Lowdefy Case Management Example

> [View this example.](https://example-case-management.lowdefy.com)

This example focuses on building a rich UI for a hypothetical case management app, in a customer relations setting.

It provides a interface where cases can be searched and filtered. Cases have a status that can be changed, and can be commented on, flagged, escalated, or closed.

The main purpose of this example is to show what types of apps can be built with Lowdefy, how to construct rich UIs, and how the MongoDB connection can be used.

## Running this example

- Create a MongoDB cluster and get a URI connection string:
  - Create a free MongoDB database cluster hosted by [MongoDB Atlas](https://www.mongodb.com/try).
  - Create a new database called `example-case-management`.
  - Add a new collection to this database called `tickets`.
  - In the Database access section, create a database user with read and write access to any database (You can also specify the database as `example-case-management`).
  - In the main cluster view, click "connect", then "Connect you application". This will give a MongoDB URI connection string. Use the credentials you just created.
  - You can read more about the [Lowdefy MongoDB connector](https://docs.lowdefy.com/MongoDB).
- Clone this repository.
- Create a `.env` file in your project folder and set your MongoDB database connector URI as a variable in the `.env` file: `LOWDEFY_SECRET_EXAMPLES_MDB="{{ your_mongodb_connection_uri }}"`
- In the command console, navigate to your project folder and run the Lowdefy CLI: `pnpx lowdefy@4 dev`.

## More Lowdefy resources

- Getting started with Lowdefy - https://docs.lowdefy.com/tutorial-start
- Lowdefy docs - https://docs.lowdefy.com
- Lowdefy website - https://lowdefy.com
- Community forum - https://github.com/lowdefy/lowdefy/discussions
- Bug reports and feature requests - https://github.com/lowdefy/lowdefy/issues

## Licence

[MIT](https://github.com/lowdefy/lowdefy-example-case-management/blob/main/LICENSE)
