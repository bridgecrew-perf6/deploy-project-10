## CircleCI:

1.use orbs to install our needed dependencies.
2.building process.
3.deploying process.

### building scripts:

`frontend:install` => to install frontend dependencies
`backend:install` => to install backend dependencies
`frontend:build` => to clean then build the app for production ready
`frontend:test` => to check if frontend-app pass the testing process
`backend:build` =>to clean then build the app for production ready
`backend:test` => to check if backend-app pass the testing process

### deploying scripts:

`frontend:deploy` => to deploy the final frontend-app to aws using S3 bucket
`backend:deploy` => to deploy the final backend-app to aws using elastic beanstack
