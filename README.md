Managing state in React is an important piece of building an app. While React has the built in `setState()` method on components, it does not ship with a way to manage global state.

Everyone knows about redux and mobx, but state management libraries are generally pretty small and the strengths and weaknesses of them really lie in the mental models and patterns that emerge from their use. Therefore, there are lots of other state management libraries out there! Here's a list to help you compare.

## if you...
* have reasonable amounts of data changing over time
* need a single source of truth for your state
* find that keeping all your state in a top-level component is no longer sufficient

(bullets are from redux docs)

## these might help
* [controllerim](https://github.com/Niryo/controllerim/) A state management library for React
* [laco](https://github.com/deamme/laco) Ultra lightweight state management for React and Inferno
* [mobx](https://mobx.js.org/) Simple, scalable state management
* [react-contextual](https://github.com/drcmda/react-contextual) is a tiny (less than 1KB) helper around React 16s new context api
* [redux](https://github.com/reactjs/redux/) +  [react-redux](https://github.com/reactjs/react-redux) Predictable state container for JavaScript apps + Official React bindings for Redux
* [StatorGFC](https://github.com/cs01/statorgfc) the simplest possible global state library for React
* [undux](https://github.com/bcherny/undux) Dead simple state management for React
* [unstated](https://github.com/jamiebuilds/unstated) State so simple, it goes without saying

## Contributing
Create a pull request to submit a new entry.
