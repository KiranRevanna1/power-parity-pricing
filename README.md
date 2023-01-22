---
name: Power Parity Pricing
slug: power-parity-pricing
description: Implement power parity pricing using information from the request geolocation object in Edge Functions.
framework: Next.js
useCase: Edge Functions
css: Tailwind
deployUrl: https://vercel.com/new/clone?repository-url=https://github.com/vercel/examples/tree/main/edge-functions/power-parity-pricing&project-name=power-parity-pricing&repository-name=power-parity-pricing
demoUrl: https://edge-functions-power-parity-pricing.vercel.app
---

# Power Parity Pricing

This example shows how to implement PPP using information from the request geolocation object on edge middleware to determine a user's location.

## Demo

https://edge-functions-power-parity-pricing.vercel.app

## How to Use

You can choose from one of the following two methods to use this repository:

### One-Click Deploy

Deploy the example using [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=vercel-examples):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/vercel/examples/tree/main/edge-functions/power-parity-pricing&project-name=power-parity-pricing&repository-name=power-parity-pricing)

### Clone and Deploy

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init) or [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/) to bootstrap the example:

```bash
npx create-next-app --example https://github.com/vercel/examples/tree/main/edge-functions/power-parity-pricing power-parity-pricing
# or
yarn create next-app --example https://github.com/vercel/examples/tree/main/edge-functions/power-parity-pricing power-parity-pricing
```

Next, run Next.js in development mode:

```bash
npm install
npm run dev

# or

yarn
yarn dev
```

Deploy it to the cloud with [Vercel](https://vercel.com/new?utm_source=github&utm_medium=readme&utm_campaign=edge-middleware-eap) ([Documentation](https://nextjs.org/docs/deployment)).
