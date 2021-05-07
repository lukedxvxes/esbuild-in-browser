# ESBUILD-IN-BROWSER

A web app for documentation, the user will be able to add rich text snippets and code snippets. The code snippets will compile in the browser, like codepen.

features to do:

- cached imports
- user can save their documentation
- create folders to organise documentation
- search snippets
- auth ?

# Current State

Uses esbuild-wasm to bundle user inputted code in the browser, so far it supports:

- es6 eg`import react from 'React'`
- commonJs eg`const moment = require('moment')`
- css eg`import 'bulma/css/bulma.css'`
