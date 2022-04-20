# Installation

Run the following command in the root folder to get started with development:

```
yarn
```

```
// For starting GatsbyJs Server run
yarn gatsby-dev
```

GatsbyJs server will start at `localhost:8000`


# Tech Stack

1. Lerna (A tool for managing JavaScript projects with multiple packages https://lernajs.io)
2. Yarn Workspace
3. React
4. Gatsby
5. Styled System and Styled Components
6. Firebase Deployment
7. Vercel Deployment

# Deployment

Run the commands below to deploy your final project:

```
yarn gatsby-build

// To check the build version locally run below command
// Not necessary if you don't want to check on your local.

yarn gatsby-serve
```

If you run `yarn gatsby-serve` then the build version of the project will start at `localhost:9000` . Navigate to that URL to get your site up and running.


# Deployment Support

## vercel.com

This project has vercel deployment by default. Go to the `packages/landing-gatsby` and run this command:

```
vercel
```

> **Make sure you have `vercel-cli` installed in your system.**

## Firebase

To deploy to your site, run the following command from the `packages/landing-gatsby` directory.

```
yarn deploy
```

> **Make sure you have `firebase-tools` installed on your machine.**

## Netlify

Open an account on netlify and go to `sites` tab.

If you want to host the `gatsbyjs` project, go to your command line and run this command on `packages/landing-gatsby` directory.

```
yarn build
```

After running above command go to `landing-gatsby` folder. You will find a `public` folder
there. Drag and drop this `public` folder on netlify `sites` tab.
