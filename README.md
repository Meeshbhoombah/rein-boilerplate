# pern-boilerplate

## Getting Started
### Prerequisites
- [Homebrew](https://brew.sh/) (Mac OS) or [Chocolatey](https://docs.chocolatey.org/en-us/) (Windows)
- [Node.js](https://nodejs.org/en/)
- [npm](https://www.npmjs.com/)

### Windows
First, download Chocolatey. Follow the instructions [here](https://docs.chocolatey.org/en-us/choco/setup#installing-chocolatey).

Then, install the Node.js package.
```
cinst nodejs.install
```

### Mac OS
#### Homebrew
First, download Homebrew via the Terminal.
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Then, check your system to ensure that Homebrew has installed without problems.
```
brew doctor
```
If not, be sure to follow the fixes that `brew doctor` suggests.

After that, run a fetch for the latest version of Homebrew (just in case).
```
brew update
```

#### Node.js
With Homebrew we can install Node.js. First, install the formula.
```
brew install node
```

Then, run a fetch for the latest version of Node.js (just in case).
```
brew update node
```

#### NPM
Confirm that `npm` was installed.
```
npm --version
```
Your output should look something like:
```
7.5.0    
```

### Installing
```
npm install
```

## Deployment
## Built With
## Authors
## License
## Acknowledgements

