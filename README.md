# CaliforniaApproves.org

React Based Website for CaliforniaApproves.org.

# Development

## Run with Docker + VS Code Dev Container
* Install Docker
* Install Dev Container Extension
* Choose "Open Folder In Dev Container"
* In VSCode Terminal run `npx vite --host 127.0.0.1`

## Run directly with NPM
Install Node
npm install
npm run dev

available on localhost:3000

# Deployment

The app is hosted using Cloudflare pages. 

Deploy to prod by pushing to `main`.

Pushing to any other branch will automatically push to
`{branch}.californiaapproves.pages.dev`. For example, pushing branch
`alan/something` will deploy to `alan-something.californiaapproves.pages.dev`.
