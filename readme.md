# This is a Microfrontend Demo - Webpack Module Federation

## Two Apps served as remote modules and One Container

### Products

Renders the list of the products

### Cart

Renders the amount of items in the cart.

### Container

This is the host app, which is to fetch the remote modules and integrate them into the "Main App"

## How can you test this out?

- Open 3 terminals, one per each project, and run `npm run install and npm run start`
- In the container app you just be able to see the integration of the apps.
