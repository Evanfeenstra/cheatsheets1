# firebase

First time, you need to install globally:
`npm install -g firebase-tools`

`firebase login`

### deployment

`npm run build`: builds your app and puts the optimized code in the "build" folder (this is part of create-react-app). Run this each time!

`firebase init`: start a new firebase project
- Choose firebase products (at least pick "Hosting")
- Public directory?: type in "build"
- Configure as single page app?: "y"
- Overwrite build/index.html?: "n"
- if there are other options, go with the defaults

`firebase deploy`

### other things on firebase

You can find your API keys in "Project Settings"

You might need to update `.rules` files to make databases secure

[Access Rule](https://firebase.google.com/docs/firestore/solutions/role-based-access)