# React
React is a JavaScript library for building user interfaces.
* **Declarative:** React makes it painless to create interactive UIs.Design simple views for each state in your appplication, and React will efficiently update and render just the right components when your data changes. Declarative views make your code more predictable, simpler to understand, and easier to debug.
* **Component-Based:** Build encapsulated components that manage their own state, then compose them to make complex UIs. Since component logic is written in JavaScript instead of templates, you can easily pass rich data through your app and keep the state out of the DOM.
* **Learn Once, Write Anywhere:**We don't make assumptions about the rest of your technology stack, so you can develop new features in React without rewriting existing code. React can also render on the server using [Node](https://nodejs.org/en) and power mobile apps using [React Native](https://reactnative.dev/).

[Learn how to use React in your project](https://react.dev/learn)
## Installation
React has been designed for gradual adoption from the start, and you can use as little or as much React as you need:
* Use [Quick Start](https://react.dev/learn) to get a taste of React.
* [Add React to an Existing Project](https://react.dev/learn/add-react-to-an-existing-project)to use as little or as much React as you need.
* [Create a New React App](https://react.dev/learn/start-a-new-react-project)if you're looking for a powerful JavaScript toolchain.
## Documentation
You can find the React documentation [on the website](https://react.dev/).

Check out the [Getting Started](https://react.dev/learn) page for a quick overview.

The documentation is divided into several sections:
* [Quick Start](https://react.dev/learn)
* [Tutorial](https://react.dev/learn/tutorial-tic-tac-toe)
* [Thinking in React](https://react.dev/learn/thinking-in-react)
* [Installation](https://react.dev/learn/installation)
* [Describing the UI](https://react.dev/learn/describing-the-ui)
* [Adding Interactivity](https://react.dev/learn/adding-interactivity)

You can improve it by sending pull requests to [this repository](https://github.com/reactjs/react.dev).
## Examples
We have several examples [on the website](https://react.dev/). Here is the first one to get you started:

```
import { createRoot } from 'react-dom/client';
function HelloMessage({name}){return <div>Hello {name}</div>;}
const root = createRoot(document.getElementById('container'));
root.render(<HelloMessage name="Taylor" />);
```
This example will render"Hello Taylor" into a container on the page.

You'll notice that we used an HTML-like syntax; [we call it JSX](https://react.dev/learn#writing-markup-with-jsx). JSX is not required to use React, but it makes code more readable, and writing it feels like writing HTML.
## Contributing
The main purpose of thos repository os to continue evolving React core, making it faster and easier to use. Development of React happens in the open on GitHub, and wo are grateful to the communtiy for contributing bugfixes and improvements. Tead below to learn how you can take part in improving React.