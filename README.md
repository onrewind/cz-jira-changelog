# cz-jira-changelog

## Description

This is an adapter for commitizen including both conventional-changelog and Jira's smart commits specifications.

## How to install

- Install commitizen on your project :
```
npm install --save-dev commitizen
```
- Initialize the adapter :
```
./node_modules/.bin/commitizen init cz-jira-changelog --save-dev --save-exact
```
- Add a script tag to your package.json
```json
...
  "scripts": {
    "commit": "git-cz"
  }
```

## How to use

When you are ready to commit your files, run the following command and start answering to the questions :
```
npm run commit
```

## Links

- [commitizen](http://commitizen.github.io/cz-cli/)
- [conventional changelog](https://github.com/conventional-changelog/conventional-changelog)
- [semantic release](https://github.com/semantic-release/semantic-release)