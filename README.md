# nuxt-example

> Bug reproduction repo

## Build Setup

``` bash
# install dependencies
$ npm install # Or yarn install

# generate static project
$ npm run generate

# run development mode
$ npm run dev

```

## Issues: 

* When generating static content the vue javascript onclick does not fire
* the router base has to be swapped to './' to reference the js files correctly when using "npm run generate" and back to '/' to when using "npm run dev" to work
