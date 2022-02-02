# npm-hello-world
An npm package that greets a user with the `name` passed as an argument.

# Installation

You need to [authenticate with Github's `npm` registry](https://docs.github.com/packages/working-with-a-github-packages-registry/working-with-the-npm-registry#authenticating-to-github-packages) before proceeding further.

In your package :

```bash 
npm i @thispsj-lab/npm-hello-world
```

Globally :

```bash
 npm i @thispsj-lab/npm-hello-world -g 
```

# Usage

In a JS File :
```javascript
const greet=require('@thispsj-lab/npm-hello-world')

greet.greet('Your name')
```

Using CLI :
```bash
greet <Your Name>
```
