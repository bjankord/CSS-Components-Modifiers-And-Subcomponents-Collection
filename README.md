CSS Components, Modifiers, and Subcomponents Collection
=======================================================

A collection of common CSS component, modifier, and subcomponent class names from around the web.

## What are CSS components, modifiers, and subcomponents?

Recently I've been researching [SMACSS](http://smacss.com) by [Johnathan Snook](https://twitter.com/snookca)  and the [BEM Methodology](http://bem.info/) by Yandex as well as examing my own 
style of crafting CSS. I've started adopting an approach based on SMACSS that uses the **Base, Layout, Module, State** 
approach for structuring my CSS, though I'ved expanded on the concept of modules based on my research
into the BEM methodolgy. I've started using a pattern which I refer to it as **Component, Modifier, and Subcomponent**.

### Components

The concept of components is the same concept of modules described in SMACSS. So if your fimiliar with SMACSS, you already know what a component is.
A few examples of componentss that come to mind are things like:

`.nav, .alert, .btn, .modal`


### Modifiers

Again, if you are familiar with SMACSS, you already know what modifiers are. Snook refers to them submodules, though after reading over the BEM methodolgy, I prefer to call these modifiers.
The concept is simple, we use modifiers to modify instances of a component or sub-component. Some examples of modifiers are things like

`--breadcrumbs, --success, --submit`

Modifiers are added onto components or subcomponents to expand their basic functionality for specific cases.

Examples of the above modifiers in use would look like:

`.nav--breadcrumbs, .alert--success, .btn--submit`

### Subcomponents

Subcomponents are the inside parts of a component, if it has any. They make up the component. For example, with a .modal module you might have the following components:

`.modal-header, .modal-body, .modal-footer`

Another example would be a `.post` component. With it, you have to following subcomponents:

`.post-title, .post-date, .post-author, .post-thumb, .post-entry, etc.`

## What is this repo?
This repo is simply a collection of common component, modifier, and subcomponent names from around the web. I believe naming things is one of the hardest parts of coding. How you style the elements is up to you, though I thought it would be nice to come up with a collection of common/popular HTML class names for components, modifiers, and subcomponents to help create more standardization in my projects.

## More thoughts on HTML Class naming conventions.
I've jotted down some thoughts on [HTML Class naming conventions](http://www.brettjankord.com/2013/03/06/more-thoughts-on-html-class-naming-conventions/) on my blog. Have a certain way you name your modules, subcomponents, and modifiers? Let me know.

## Credit

- [Johnathan Snook](https://twitter.com/snookca) - [SMACSS](http://smacss.com)
- Yandex - [BEM Methodology](http://bem.info/)
- [Harry Roberts](https://twitter.com/csswizardry) - [inuit.css](http://inuitcss.com/)
- [Jacob Thornton](https://twitter.com/fat) and anyone who has contributed to [Twitter Bootstrap](http://twitter.github.com/bootstrap/)
- Any developer interested in creating modular, reusable, CSS
