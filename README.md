# uobtheatre-web

## About
This repository is the frontend for uobtheatre.com, the Shows and Events platform operated by Bristol STA for use by Bristol SU socieities.

## Project Structure and Form
This project utilises the following:
- Vue CLI - Handles the compiliation and chores in the repository
- Vue JS - A progressive JavaScript framework for reactive content
- Tailwindcss - A utility-first CSS framework

Here are the important areas to take a look at:
- `/public/` This folder contains the base HTML file that is compiled and used as the entry point for the application. Other files in here are copied like-for-like over into the dist folder during the build process
- `/src/` This folder contains all the JS and CSS for the application
    - `/src/views/` This folder contains all the pages for the application. These are later referenced by the router
    - `/src/router/` This folder contains the configuration for the router, which decides what to show to a user depending on their URI
    - `/src/components/` This folder contains the Vue components utilised in the views


## Geting started
1. Run `yarn install`
2. Run `yarn serve`
3. Visit the URL output in the command line

You can now edit the project files, and the browser will reload the page automatically.

You can run `yarn lint` to lint and fix files.

## To build and deploy
1. Run `yarn build`
2. Deploy the files from `/dist`

## Testing

### Unit Tests
```
yarn test:unit
```

### End-to-end tests
```
yarn test:e2e --headless
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
