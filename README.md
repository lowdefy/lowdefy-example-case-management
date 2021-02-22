# A Lowdefy Case Management Example

[![Netlify Status](https://api.netlify.com/api/v1/badges/7c9c5633-4323-491d-b02d-05406f694fc2/deploy-status)](https://app.netlify.com/sites/lowdefy-example-case-management/deploys)

> [View this example.](https://example-case-management.lowdefy.com)

This example focuses on building a rich UI for a hypothetical case management app, in a customer relations setting.

It provides a interface where cases can be searched and filtered. Cases have a status that can be changed, and can be commented on, flagged, escalated, or closed. The interface has some elements, like past order count, that are generated at random, but it would be possible that this data is looked up from real customer data.

The main purpose of this example is to show what types of apps can be built with Lowdefy, how to construct rich UIs, and how the MongoDB connection can be used.

This example is deployed using [Netlify](https://docs.lowdefy.com/deployment).

## Running this example

- Clone this repository.
- Get a MongoDB URI. You can use MongoDB as follows:
  - Create a free MongoDB database cluster hosed by MongoDB Atlas at https://www.mongodb.com/cloud/atlas.
  - In the Database access section, create a database user with write access to any database (You can also specify the database as `example-case-management`).
  - In the main cluster view, click "connect", then "Connect you application". This will give a MongoDB URI connection string. Use the credentials you just created.
- Create `.env` file and set `LOWDEFY_SECRET_EXAMPLES_MDB` to your MongoDB URI.
- Run the Lowdefy CLI from the cloned repository folder `npx lowdefy@latest dev`.

## Deploying this example

This simplest solution is to deploy this example to [Netlify](https://netlify.com). See [the Netlify Deployment instructions](https://docs.lowdefy.com/deployment) for more detail on how to deploy a Lowdefy app to Netlify.

## More Lowdefy resources

- Getting started with Lowdefy - https://docs.lowdefy.com/tutorial-start
- Lowdefy docs - https://docs.lowdefy.com
- Lowdefy website - https://lowdefy.com
- Community forum - https://github.com/lowdefy/lowdefy/discussions
- Bug reports and feature requests - https://github.com/lowdefy/lowdefy/issues

## Licence

[MIT](https://github.com/lowdefy/lowdefy-example-case-management/blob/main/LICENSE)