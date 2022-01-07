ICX FE 


Intro
-----

The ICX content delivery network (CDN) enables developers to access the latest frontend features in ICX without having to do continual Nuget updates.
To run the code challenge you will need a version of node >= 15.

Getting started
---------------

## Initial setup

```bash
npm install
```

This will install all the dependencies required to run the code challenge.

## Run the local server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Updates to the library

When there are updates to the component library you should update the version in the package.json file and run the following

`yarn`

If you're not seeing changes in your component library, restart the local server, which should correct any caching issues.