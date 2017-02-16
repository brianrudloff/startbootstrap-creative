[![NPM](https://nodei.co/npm/vuedeux.png?compact=true)](https://npmjs.org/package/vuedeux)

# vuedeux

![Alt Text](https://github.com/dmrx/vuedoo/raw/master/examples/TodoMVC/assets/vuedeuxsmall.png)


## Full Documentation
https://vueduex.gitbooks.io/vuedeux-documentation/content/

## Synopsis 

Vuedeux is a lightweight open-source utility layer for binding Vuex to Redux in a way that allows developers to re-use their pre-existing Redux stores.

## Motivation
Vuedeux answers our team's desire to create a simple way to re-use and share state-management code with Vue/Vuex. The decision to create the Vuedeux compatibility layer between Vuex and Redux was inspired by the idea of uniting the quickly growing Vue community and Redux's broad user-base and ecosystem.

We love Vue & Vuex. We love the elegance and the tight integration. We love Redux. We love that it is framework agnostic and has a robust ecosystem of tools, middlewares, and bindings.

We wanted to make them work together in a developer-friendly and highly customizable way to encourage interoperability and streamline reusability of code bases.

Vuedeux allows Redux developers to feel at home in Vue while providing all the conveniences and efficiencies of Vuex.


## How It Works
The Vuedeux Plugin Creator takes your Redux action types and Redux store, and then maps your Redux state and all associated actions to a Vuex module with equivalent actions and mutations, allowing you to easily reuse your existing Redux state store and dispatch to Vuex just like you would with Redux.

## Prerequisites
Redux, Vue, Vuex