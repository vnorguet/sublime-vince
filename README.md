# sublime-react-es6

This is a fork of Facebook's original ReactJS Sublime Package.

The main changes I've made include:

- Converting function declarations to the new ES6 shorthand.

- Static class variables (defaultProps, propTypes) are declared using ES7 property intializers.

- ES6 style exports and imports for component creating snippets.

- Added `rrc` for Redux connected components.

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

