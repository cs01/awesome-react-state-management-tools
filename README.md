## if you...
* have reasonable amounts of data changing over time
* need a single source of truth for your state
* find that keeping all your state in a top-level component is no longer sufficient

(bullets are from redux docs)

## these might help
* [controllerim](https://github.com/Niryo/controllerim/) A state management library for React
* [laco](https://github.com/deamme/laco) Ultra lightweight state management for React and Inferno
* [MobX](https://mobx.js.org/) Simple, scalable state management
* [react-contextual](https://github.com/drcmda/react-contextual) is a tiny (less than 1KB) helper around React 16s new context api
* [react-easy-state](https://github.com/solkimicreb/react-easy-state) minimal React state management with the power of ES6 Proxies
* [redux](https://github.com/reactjs/redux/) +  [react-redux](https://github.com/reactjs/react-redux) Predictable state container for JavaScript apps + Official React bindings for Redux
* [StatorGFC](https://github.com/cs01/statorgfc) the simplest possible global state library for React
* [undux](https://github.com/bcherny/undux) Dead simple state management for React
* [unstated](https://github.com/jamiebuilds/unstated) State so simple, it goes without saying

Note that you probably only want to choose *one* of these. They aren't meant to work together.

Managing state in React is an important piece of building an app. While React has the built in `setState()` method on components (which you should thoroughly understand before adopting one of these tools), it does not ship with a way to manage global state.

Everyone knows about redux and MobX, but there are lots more libraries out there. The strengths and weaknesses of state management lie in the mental models and patterns that emerge from their use. So try a few to find one that suits you, your team, and your project.

## Contributing
Create a pull request to submit a new entry.
