vim-react-es6-snippets
==================

A set of snippets for Vim to work with Facebook's [React](http://facebook.github.io/react/) library.

A direct port of the awesome snippets from 
[justinj/vim-react-snippets](https://github.com/justinj/vim-react-snippets).

Requires [vim-snipmate](https://github.com/garbas/vim-snipmate).

Installation
============

Use your preferred Vim plugin installation method.  Vundle or Pathogen should be fine (I use Pathogen).

Usage
=====

Within any Javascript or JSX file, you should be able to do the following:

(in insert mode)
```
gdp<Tab>
```

expanding to

```
getDefaultProps() {
    return {

    };
},
```

And a bunch of others!
Check `snippets/javascript.snippets` to see the full list.
