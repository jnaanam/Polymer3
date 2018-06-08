# Exploring Polymer 3
[Polymer 3.0 is here](https://www.polymer-project.org/). 

The announcement at IO16 came with three "next-gen" product updates that are worth exploring if starting a new project. These are:

 * [**LitElement**](https://github.com/Polymer/lit-element/blob/master/README.md) - is a base class for rendering custom elements using [lit-html](https://github.com/Polymer/lit-html), a package that enables you to write [HTML Templates](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/template) with JavaScript [template literals](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals). (_See [Glitch](https://glitch.com/edit/#!/hello-lit-element) Demo_)

 * [**Material Web Components**](https://github.com/material-components/material-components-web-components/blob/master/README.md) builds on [Material Components for the web](https://github.com/material-components/material-components-web) and LitElement, to craft vanilla custom elements that adhere to the latest [Material Design](https://www.material.io/) guidelines.

 * [**PWA Starter Kit**](https://github.com/Polymer/pwa-starter-kit/blob/master/README.md) which scaffolds out a [Progressive Web App]() using [Web Components](https://www.webcomponents.org/introduction) and [lit-html](https://github.com/Polymer/lit-element) for templating. It aims to provide an offline-first experience, simple routing, PRPL-pattern compliance, Redux-based state managemnt, responsive layouts and support for application theming.

All three are works in progress but on fast-track to a 1.0 release. The goal of this repo is to explore current support with an eye on migrating Polymer 2 apps to this release in short order.
