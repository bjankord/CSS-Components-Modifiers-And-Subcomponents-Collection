CSS Modules, Components, and Modifiers Collection
=================================================

A collection of common CSS module, component, and modifier class names from around the web.

## What are CSS modules, components, and modifiers?

Recently I've been researching [SMACSS](http://smacss.com) by [Johnathan Snook](https://twitter.com/snookca)  and the [BEM Methodology](http://bem.info/) by Yandex as well as examing my own 
style of crafting CSS. I've started adopting an approach based on SMACSS that uses the Base, Layout, Module, State 
approach for structuring my CSS, though I'ved expanded on the concept of modules based on my research
into the BEM methodolgy. I've started using a pattern which I refer to it as Module, Component, Modifier.

### Modules

The concept of modules is the same concept of modules described in SMACSS. So if your fimiliar with SMACSS, you already know what modules are.
A few examples of modules that come to mind are things like:

`.nav, .alert, .btn, .modal`

### Components

Components are the inside parts of a module, if it has any. They make up the module. For example, with a .modal module you might have the following components:

`.modal-header, .modal-body, .modal-footer`

Another example would be a `.post` module. With it, you have to following components:

`.post-title, .post-date, .post-author, .post-thumb, .post-entry, etc.`

### Modifiers

Again, if you are familiar with SMACSS, you already know what modifiers are. Snook refers to them sub-modules, though after reading over the BEM methodolgy, I prefer to call these modifiers.
The concept is simple, we use modifiers to modify instances of a module. Some examples of modifiers are things like

`--bread-crumbs, --success, --submit`

Modifiers are added onto modules to expand their basic functionality for specific cases.

Examples of the above modifiers in use would look like:

`.nav--breadcrumbs, .alert--success, .btn--submit`

## What is this repo?
This repo is simply a collection of common module names, component names, and modifier names from around the web. I believe naming things is one of the hardest parts of coding. How you style the elements is up to you, though I thought it would be nice to come up with a collection of common/popular HTML class names for modules, components, and modifiers to help create more standardization in my projects.

## Credit

- [Johnathan Snook](https://twitter.com/snookca) - [SMACSS](http://smacss.com)
- Yandex - [BEM Methodology](http://bem.info/)
- [Harry Roberts](https://twitter.com/csswizardry) - [inuit.css](http://inuitcss.com/)
- [Jacob Thornton](https://twitter.com/fat) and anyone who has contributed to [Twitter Bootstrap](http://twitter.github.com/bootstrap/)
- Any developer interested in creating modular, reusable, CSS
