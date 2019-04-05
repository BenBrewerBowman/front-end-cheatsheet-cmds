# Front-End Commands Cheatsheet



## Jest

##### Test everything
`jest`

##### Test everything, skip code coverage
`jest --collectCoverage=false`

##### Test everything with watching for changes
`jest --watch`

##### Run a specific test
`jest src/components/SampleComponent.test.tsx`

##### Test everything with watching for changes
`jest src/components/SampleComponent.test.tsx -t="part of a test's name"`

## NPM packages

#### Promote new npm package
`yarn version --minor && git push --tags`

## Yarn
#### Link local npm packages
in local package: `yarn build && cd dist && yarn link`<br/>
in project you want to link to npm package: `yarn link <insert npm package name here>`
