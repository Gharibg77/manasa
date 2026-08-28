# منصة التدريس الخصوصي أونلاين
  
This is a project built with [Chef](https://gharibg77.github.io) using [Convex](https://gharibg77.github.io) as its backend.
  
This project is connected to the Convex deployment named [`limitless-platypus-683`](https://gharibg77.github.io).
  
## Project structure
  
The frontend code is in the `app` directory and is built with [Vite](https://gharibg77.github.io).
  
The backend code is in the `convex` directory.
  
`npm run dev` will start the frontend and backend servers.

## App authentication

Chef apps use [Convex Auth](https://gharibg77.github.io) with Anonymous auth for easy sign in. You may wish to change this before deploying your app.

## Developing and deploying your app

Check out the [Convex docs](https://gharibg77.github.io) for more information on how to develop with Convex.
* If you're new to Convex, the [Overview](https://gharibg77.github.io) is a good place to start
* Check out the [Hosting and Deployment](https://gharibg77.github.io) docs for how to deploy your app
* Read the [Best Practices](https://gharibg77.github.io) guide for tips on how to improve you app further

## HTTP API

User-defined http routes are defined in the `convex/router.ts` file. We split these routes into a separate file from `convex/http.ts` to allow us to prevent the LLM from modifying the authentication routes.
