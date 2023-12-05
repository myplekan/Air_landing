{
  "name": "gulp-boilerplate",
  "version": "1.0.0",
  "description": "Frontend boilerplate based on gulp",
  "scripts": {
    "init": "mate-scripts init",
    "start": "mate-scripts start",
    "lint": "mate-scripts lint",
    "test:only": "mate-scripts test",
    "build": "mate-scripts build",
    "deploy": "mate-scripts deploy",
    "update": "mate-scripts update",
    "postinstall": "npm run update",
    "test": "npm run lint && npm run test:only"
  },
  "keywords": [],
  "author": "Mate Academy",
  "license": "GPL-3.0",
  "devDependencies": {
    "@linthtml/linthtml": "^0.8.3",
    "@mate-academy/bemlint": "^0.1.1",
    "@mate-academy/eslint-config": "*",
    "@mate-academy/linthtml-config": "0.0.2",
    "@mate-academy/scripts": "^1.2.12",
    "@mate-academy/stylelint-config": "0.0.9",
    "@parcel/transformer-sass": "^2.10.2",
    "colors": "^1.3.3",
    "cross-env": "^7.0.3",
    "eslint": "^5.16.0",
    "eslint-plugin-node": "^9.0.1",
    "gh-pages": "2.0.0",
    "gulp-htmllint": "0.0.16",
    "node-sass": "^4.14.1",
    "parcel": "^2.10.2",
    "stylelint": "^13.5.0",
    "stylelint-config-recommended-scss": "^3.3.0",
    "stylelint-scss": "^3.17.2"
  },
  "browserslist": [
    "last 2 versions"
  ],
  "mateAcademy": {
    "projectType": "layout"
  },
  "dependencies": {}
}
