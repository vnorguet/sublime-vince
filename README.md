# sublime-react-es6

This is a fork of Facebook's original ReactJS Sublime Package.

The main changes I've made include:

- Plain JS
    + function
    + exports
- Mocha
    + describe
    + it
- React/Meteor
    + Flow route generator
    + React class
    + React container
    + React Formatted message

![alt tag](https://raw.githubusercontent.com/mboperator/sublime-react/master/docs/img/sr-rcc-out.gif)

## Installation

Install the React package via Sublime's Package Manager

You will need the Sublime [Package Manager](https://sublime.wbond.net/installation).

- Open the command palette: `⌘+shift+p` on MacOS/Linux, `ctrl+shift+p` on Windows

- type `install`, select `Package Control: Install Package`

- type `React`, select `React ES6 Snippets`

## Usage

### Syntax highlighting

*Syntax highlighting is no longer provided by this packages*. We recommend that you use ([babel-sublime](https://github.com/babel/babel-sublime)) instead.

### Snippets

It's easy! Simply activate snippets by typing a mnemonic followed by TAB.

![alt tag](https://raw.githubusercontent.com/mboperator/sublime-react/master/docs/img/sr-snippets-out.gif)

#### Documentation of available snippets (JSX):

```
  describe→  ES6 describe

  exports→  exports.myFunction = function(...)

     it→  ES6 it

```

## Contributing

### Rebuilding the docs

After making changes to snippet files, run `npm install && npm run build-docs` to automatically generate this document from source. **Do not** make changes to README.md directly.
