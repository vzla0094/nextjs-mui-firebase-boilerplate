# Next.js with material UI and firebase hosting example

This is based off of the work at https://github.com/jthegedus/firebase-gcp-examples/tree/master/functions-nextjs , I integrated it with the material-ui using next.js example at https://github.com/mui-org/material-ui/tree/master/examples/nextjs

## How to use

### Setup

- fork and download this project
- install Firebase Tools: `npm i -g firebase-tools`
- create a project through the [firebase web console](https://console.firebase.google.com/)
- grab the projects ID from the web consoles URL: `https://console.firebase.google.com/project/<projectId>`
- update the `.firebaserc` default project ID to the newly created project
- login to the Firebase CLI tool with `firebase login`
- run `npm install`

### Development

#### Run Next.js development:

```bash
npm run dev
```

#### Run Firebase locally for testing:

```
npm run serve
```

#### Deploy it to the cloud with Firebase:

```bash
npm run deploy
```
