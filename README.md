# QuicklyMD

To start development, from root folder...

`npm i`
`npm start`

---

To generated dist package...

`npm run dist`

---

# stores

We use mobx for our stores.  It's like an easier version of redux.
<https://github.com/mobxjs/mobx-react>. The stores go in the /stores folder.

# file structure
Components go into containing folders and their associated scss file is then added at the bottom of
styles/app.scss. All things page related will be setup up through the router via app/index.js. We may want
to refactor this into a root component if things get hella complicated.

# es6
["es2015", { "modules": false }],
"transform-decorators-legacy",


#