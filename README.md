# React Tiny Snippets for Atom

[![apm](https://img.shields.io/apm/v/react-tiny-snippets.svg)](https://atom.io/packages/react-tiny-snippets)

Tiny Snippets of React for [Atom](https://atom.io/) editor.

This package autocompletes..

* Life cycle method names and their declarations
* static class property names and their declarations

#### example

```javascript
// Typing `componentwillreceiveprops` leads...

/**
 * componentWillReceiveProps
 * @param  {object} nextProps React props.
 * @return {void}
 */
componentWillReceiveProps(nextProps) {
  $1
}
```

## Installation

Run the following command:

```shell
$ apm install react-tiny-snippets
```

Alternatively go to `Atom > Preferences > Packages` and search for `react-tiny-snippets`.

## Development

```shell
git clone git@github.com:kamataryo/react-tiny-snippets.git
cd react-tiny-snippets
npm install
npm run build
```

## Contribution

Issues and PRs are welcome.

## Release Note

### 0.0.9

* Add getDerivedStateFromProps, getSnapshotBeforeUpdate, UNSAFE_componentWillMount, UNSAFE_componentWillUpdate and UNSAFE_componentWillReceiveProps.

### 0.0.5

* Fix indent bug for `propTypes` and `defaultProps`
* add `componentDidCatch` snippet for React v16
