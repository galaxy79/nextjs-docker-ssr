# With Docker

This sample repo shows, how to deploy a nextjs app using docker.

## How to use

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init), to bootstrap the example:

```bash
npx create-next-app --example with-docker nextjs-docker

```

## Using Docker

1. [Install Docker](https://docs.docker.com/get-docker/) on your machine.
1. Build your container: `docker build -t nextjs-docker .`.
1. Run your container: `docker run -p 3000:3000 nextjs-docker`.

You can view your images created with `docker images`.

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
