# backstage-demo

This is a starter ExpressJs project, you can run it as a standalone
app using `npm run server` in the root of the project.
The server will be listening to request on port `3000`,
so you can test the server in a browser accessing `http://localhost:3000` or via `cURL`.

Before running the command `npm run server` you need to run `npm install` to
install the dependencies
# Deploying to Tanzu Application Service

Deploy the app on TAS using the cf CLI:

```bash
cf push -f manifest.yaml
```

## Accessing the App Pushed to Tanzu Application Service

Determine the URL to use to access the app by running:

```
cf app backstage-demo
```

To access the deployed app, open the URL shown in your browser.
