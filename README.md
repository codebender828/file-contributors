
<br />
<h1 align="center"><code>👩🏽‍💻 file-contributors 👨🏻‍💻</code></h1>

Ever wonder who's contributed to a specific file on github? `file-contributors` gives you simple way to get all contributors to a specific file on Github.

<h3>See demo 👉🏽 </h3>

### ⚡️ Installation
Install `file-contributors` from npm

```bash
npm install file-contributors --save
```
### Usage
`file-contributors` exports function that accepts 3 arguments.
- `owner` Owner of the github repository. This could be your username or organization name
  - type: `String`
- `repo` Name of the repository
  - type: `String`
- `path` Location of the file relative to the repository root.
  - type: `String`
```js
import getFileContributors from 'file-contributors'

const file = {
  owner: 'codebender828',
  repo: 'file-contributors',
  path: 'README.md'
}

const contributors = getFileContributors(file.owner, file.repo, file.path)
  .then(contributors => {
    console.log(contributors) // Logs array of contributors to file.
  })
```

## ❤️ Support this project
If you like this project, please consider supporting it by buying my a coffee!

<a target="_blank" href="https://www.buymeacoffee.com/dIlWof6x5">
  <img width="200px" src="https://res.cloudinary.com/xtellar/image/upload/v1584764609/jbakebwa.dev/sponsorships/buy-me-a-coffee.png" alt="Buy me a coffee">
</a>

<center>
  <br>
  Made with ❤️ by <a target="_blank" href="https://twitter.com/codebender828">Jonathan Bakebwa 🇺🇬</a>
</center>

