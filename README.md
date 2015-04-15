# typescript-mocha

Project to check if mocha tests can be written in TypeScript

# How to

## Requirements 

- NodeJS

## Steps 

Configure `npm` to handle dependencies

    npm init

Install [TypeScript]. First, try no to install globally, just for testing

    npm install --save typescript

Check TypeScript installation

    node_modules/.bin/tsc --version

Install [TSD]

    npm install --save tsd

Check TSD installation

    node_modules/.bin/tsd --version

Install [mocha] and [chai]. I have a more detail post about [How to set up a NodeJS project with mocha, chai and sinon]

    npm install --save mocha chai

Install mocha and chai TypeScript definition files, with TSD

    node_modules/.bin/tsd query mocha --save --action install
    node_modules/.bin/tsd query chai --save --action install


