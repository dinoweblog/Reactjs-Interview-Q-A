# React Interview Questions & Answers

> Click :star:if you like the project. Pull Request are highly appreciated.

### Table of Contents

|    | Questions                                                                                                                                                                                                                        |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|     | **Core React**                                                                                                                                                                                                                   |
| :star: | [What is React?](#what-is-react)                                                                                                                                                                                                 |
| :star: | [What are the major features of React?](#what-are-the-major-features-of-react)                                                                                                                                                   |
| :star: | [What is JSX?](#what-is-jsx)                                                                                                                                                                                                     |
| :star: | [What is the difference between function components and class components?](#what-is-the-difference-between-function-components-and-class-components)
| :star: | [What is the difference between Element and Component?](#what-is-the-difference-between-element-and-component)                                                                                                             |
| :star: | [When to use a Class Component over a Function Component?](#when-to-use-a-class-component-over-a-function-component)                                                                                                             |
| :star: | [What are Pure Components?](#what-are-pure-components)                                                                                                                                                                           |
| :star: | [What is state in React?](#what-is-state-in-react)                                                                                                                                                                               |
| :star: | [What are props in React?](#what-are-props-in-react)                                                                                                                                                                             |
| :star: | [What is the difference between state and props?](#what-is-the-difference-between-state-and-props)                                                                                                                               |
| :star: | [Why should we not update the state directly?](#why-should-we-not-update-the-state-directly)                                                                                                                                     |
| :star: | [What is the purpose of callback function as an argument of setState()?](#what-is-the-purpose-of-callback-function-as-an-argument-of-setstate)                                                                                   |
| :star: | [What is the difference between HTML and React event handling?](#what-is-the-difference-between-html-and-react-event-handling)                                                                                                   |                                                                                                            |
| :star: | [What are synthetic events in React?](#what-are-synthetic-events-in-react)                                                                                                                                                                                                        |
| :star: | [What is "key" prop and what is the benefit of using it in arrays of elements?](#what-is-key-prop-and-what-is-the-benefit-of-using-it-in-arrays-of-elements)                                                                     |
| :star: | [What is the use of refs?](#what-is-the-use-of-refs)                                                                                                                                                                             |
| :star: | [How to create refs?](#how-to-create-refs)                                                                                                                                                                                       |
| :star: | [What are forward refs?](#what-are-forward-refs)                                                                                                                                                       |
| :star: | [What is Virtual DOM?](#what-is-virtual-dom)                                                                                                                                                                                     |
| :star: | [How Virtual DOM works?](#how-virtual-dom-works)                                                                                                                                                                                 |
| :star: | [What is the difference between Shadow DOM and Virtual DOM?](#what-is-the-difference-between-shadow-dom-and-virtual-dom)                                                                                                         |
| :star: | [What is React Fiber?](#what-is-react-fiber)                                                                                                                                                               |
| :star: | [What are controlled components?](#what-are-controlled-components)                                                                                                                                                               |
| :star: | [What are uncontrolled components?](#what-are-uncontrolled-components)                                                                                                                          |
| :star: | [What is Lifting State Up in React?](#what-is-lifting-state-up-in-react)                                                                                                                                                         |
| :star: | [What are the different phases of component lifecycle?](#what-are-the-different-phases-of-component-lifecycle)                                                                                                                   |
| :star: | [What are the lifecycle methods of React?](#what-are-the-lifecycle-methods-of-react)                                                                                                                                             |
| :star: | [What are Higher-Order components?](#what-are-higher-order-components)                                                                                                                                        |
| :star: | [What is context?](#what-is-context)                                                                                                                                                                                             |
| :star: | [What is children prop?](#what-is-children-prop)                                                                                                                               |
| :star: | [What is reconciliation?](#what-is-reconciliation)                                                                                                                                                                                                                                                         |
| :star: | [What are fragments?](#what-are-fragments)                                                                                                                                                                                                                                                                                      |
| :star: | [What are stateless components?](#what-are-stateless-components)                                                                                                                                                                 |
| :star: | [What are stateful components?](#what-are-stateful-components)                                                                                                                                                                   |
| :star: | [How to apply validation on props in React?](#how-to-apply-validation-on-props-in-react)                                                                                                                                         |
| :star: | [What are the advantages of React?](#what-are-the-advantages-of-react)                                                                                                                                                           |
| :star: | [What are the limitations of React?](#what-are-the-limitations-of-react)                                                                                                                                                         |
| :star: | [What are error boundaries in React v16](#what-are-error-boundaries-in-react-v16)                                                                                                                                                |
| :star: | [How are error boundaries handled in React v15?](#how-are-error-boundaries-handled-in-react-v15)                                                                                                                                 |
| :star: | [What are the recommended ways for static type checking?](#what-are-the-recommended-ways-for-static-type-checking)                                                                                                               |
| :star: | [What is the use of react-dom package?](#what-is-the-use-of-react-dom-package)                                                                                                                                                   |
| :star: | [What is the purpose of render method of react-dom?](#what-is-the-purpose-of-render-method-of-react-dom)                                                                                                                         |
| :star: | [What is ReactDOMServer?](#what-is-reactdomserver)                                                                                                                                                                               |
| :star: | [How to use InnerHtml in React?](#how-to-use-innerhtml-in-react)                                                                                                                                                                 |
| :star: | [How to use styles in React?](#how-to-use-styles-in-react)                                                                                                                                                                       |
| :star: | [How events are different in React?](#how-events-are-different-in-react)                                                                                                                                                         |
| :star: | [What will happen if you use setState in constructor?](#what-will-happen-if-you-use-setstate-in-constructor)                                                                                                                     |
| :star: | [What is the impact of indexes as keys?](#what-is-the-impact-of-indexes-as-keys)                                                                                                                                                 |
| :star: | [Is it good to use setState() in componentWillMount() method?](#is-it-good-to-use-setstate-in-componentwillmount-method)                                                                                                         |
| :star: | [What will happen if you use props in initial state?](#what-will-happen-if-you-use-props-in-initial-state)                                                                                                                       |
| :star: | [How do you conditionally render components?](#how-do-you-conditionally-render-components)                                                                                                                                       |
| :star: | [Why we need to be careful when spreading props on DOM elements??](#why-we-need-to-be-careful-when-spreading-props-on-dom-elements)                                                                                              |
| :star: | [How you use decorators in React?](#how-you-use-decorators-in-react)                                                                                                                                                             |
| :star: | [How do you memoize a component?](#how-do-you-memoize-a-component)                                                                                                                                                        |
| :star: | [Do Hooks replace render props and higher order components?](#do-hooks-replace-render-props-and-higher-order-components)                                                                                                         |
| :star: | [What is the recommended way for naming components?](#what-is-the-recommended-way-for-naming-components)                                                                                                                         |
| :star: | [What is the recommended ordering of methods in component class?](#what-is-the-recommended-ordering-of-methods-in-component-class)                                                                                               |
| :star: | [What is a switching component?](#what-is-a-switching-component)                                                                                                                                                                 |
| :star: | [Why we need to pass a function to setState()?](#why-we-need-to-pass-a-function-to-setstate)                                                                                                                                     |
| :star: | [What is strict mode in React?](#what-is-strict-mode-in-react)                                                                                                                                                                                              || :star: | [Is it possible to use async/await in plain React?](#is-it-possible-to-use-asyncawait-in-plain-react)                                                                                                                                                                                        |
|     | **React Router**                                                                                                                                                                                                                 || :star: | [What is React Router?](#what-is-react-router)                                                                                              |
| :star: | [How React Router is different from history library?](#how-react-router-is-different-from-history-library)                                                                                                                       |
| :star: | [What are the \<Router> components of React Router v4?](#what-are-the-router-components-of-react-router-v4)                                                                                                                      |
| :star: | [What is the purpose of push and replace methods of history?](#what-is-the-purpose-of-push-and-replace-methods-of-history)                                                                                                       |
| :star: | [How do you programmatically navigate using React router v4?](#how-do-you-programmatically-navigate-using-react-router-v4)                                                                                                       |
| :star: | [How to get query parameters in React Router v4](#how-to-get-query-parameters-in-react-router-v4)                                                                                                                |
| :star: | [How to implement default or NotFound page?](#how-to-implement-default-or-notfound-page)                                                                                                                                                                                                                                                                                         |
|     | **React Testing**                                                                                                                                                                                                                |
| :star: | [What is Shallow Renderer in React testing?](#what-is-shallow-renderer-in-react-testing)                                                                                                                                         |
| :star: | [What is TestRenderer package in React?](#what-is-testrenderer-package-in-react)                                                                                                                                                 |
| :star: | [What is the purpose of ReactTestUtils package?](#what-is-the-purpose-of-reacttestutils-package)                                                                                                                                 |
| :star: | [What is Jest?](#what-is-jest)                                                                                                                                                                                                   |
| :star: | [What are the advantages of Jest over Jasmine?](#what-are-the-advantages-of-jest-over-jasmine)                                                                                                                                   |
| :star: | [Give a simple example of Jest test case](#give-a-simple-example-of-jest-test-case)                                                                                                                                              |
|     | **React Redux**                                                                                                                                                                                                                  |
| :star: | [What is Flux?](#what-is-flux)                                                                                                                                                                                                   |
| :star: | [What is Redux?](#what-is-redux)                                                                                                                                                                                                 |
| :star: | [What are the core principles of Redux?](#what-are-the-core-principles-of-redux)                                                                                                                                                 |
| :star: | [What are the downsides of Redux compared to Flux?](#what-are-the-downsides-of-redux-compared-to-flux)                                                                                                                           |
| :star: | [What is the difference between mapStateToProps() and mapDispatchToProps()?](#what-is-the-difference-between-mapstatetoprops-and-mapdispatchtoprops)                                                                             |
| :star: | [Can I dispatch an action in reducer?](#can-i-dispatch-an-action-in-reducer)                                                                                                                                                     |
| :star: | [How to access Redux store outside a component?](#how-to-access-redux-store-outside-a-component)                                                                                                                                 |
| :star: | [What are the drawbacks of MVW pattern](#what-are-the-drawbacks-of-mvw-pattern)                                                                                                                                                  |
| :star: | [Are there any similarities between Redux and RxJS?](#are-there-any-similarities-between-redux-and-rxjs)                                                                                                                         |
| :star: | [How to dispatch an action on load?](#how-to-dispatch-an-action-on-load)                                                                                                                                                         |
| :star: | [How to use connect from React Redux?](#how-to-use-connect-from-react-redux)                                                                                                                                                     |
| :star: | [How to reset state in Redux?](#how-to-reset-state-in-redux)                                                                                                                                                                     |
| :star: | [Whats the purpose of at symbol in the redux connect decorator?](#whats-the-purpose-of-at-symbol-in-the-redux-connect-decorator)                                                                                                 |
| :star: | [What is the difference between React context and React Redux?](#what-is-the-difference-between-react-context-and-react-redux)                                                                                                   |
| :star: | [Why are Redux state functions called reducers?](#why-are-redux-state-functions-called-reducers)                                                                                                                                 |
| :star: | [How to make AJAX request in Redux?](#how-to-make-ajax-request-in-redux)                                                                                                                                                         |
| :star: | [Should I keep all component's state in Redux store?](#should-i-keep-all-components-state-in-redux-store)                                                                                                                        |
| :star: | [What is the proper way to access Redux store?](#what-is-the-proper-way-to-access-redux-store)                                                                                                                                   |
| :star: | [What is the difference between component and container in React Redux?](#what-is-the-difference-between-component-and-container-in-react-redux)                                                                                 |
| :star: | [What is the purpose of the constants in Redux? ](#what-is-the-purpose-of-the-constants-in-redux)                                                                                                                                |
| :star: | [What are the different ways to write mapDispatchToProps()?](#what-are-the-different-ways-to-write-mapdispatchtoprops)                                                                                                           |
| :star: | [What is the use of the ownProps parameter in mapStateToProps() and mapDispatchToProps()?](#what-is-the-use-of-the-ownprops-parameter-in-mapstatetoprops-and-mapdispatchtoprops)                                                 |
| :star: | [How to structure Redux top level directories?](#how-to-structure-redux-top-level-directories)                                                                                                                                   |
| :star: | [What is redux-saga?](#what-is-redux-saga)                                                                                                                                                                                       |
| :star: | [What is the mental model of redux-saga?](#what-is-the-mental-model-of-redux-saga)                                                                                                                                               |
| :star: | [What are the differences between call and put in redux-saga](#what-are-the-differences-between-call-and-put-in-redux-saga)                                                                                                      |
| :star: | [What is Redux Thunk?](#what-is-redux-thunk)                                                                                                                                                                                     |
| :star: | [What are the differences between redux-saga and redux-thunk](#what-are-the-differences-between-redux-saga-and-redux-thunk)                                                                                                      |
| :star: | [What is Redux DevTools?](#what-is-redux-devtools)                                                                                                                                                                               |
| :star: | [What are the features of Redux DevTools?](#what-are-the-features-of-redux-devtools)                                                                                                                                             |
| :star: | [What are Redux selectors and Why to use them?](#what-are-redux-selectors-and-why-to-use-them)                                                                                                                                   |
| :star: | [What is Redux Form?](#what-is-redux-form)                                                                                                                                                                                       |
| :star: | [What are the main features of Redux Form?](#what-are-the-main-features-of-redux-form)                                                                                                                                           |
| :star: | [How to add multiple middlewares to Redux?](#how-to-add-multiple-middlewares-to-redux)                                                                                                                                           |
| :star: | [How to set initial state in Redux?](#how-to-set-initial-state-in-redux)                                                                                                                                                         |
| :star: | [How Relay is different from Redux?](#how-relay-is-different-from-redux)                                                                                                                                                         |
| :star: | [What is an action in Redux?](#what-is-an-action-in-redux)                                                                                                                                                             |

## Core React

1.  ### What is React?

    React is a popular open-source JavaScript library used for building user interfaces (UI) in web applications. It was developed by Facebook and is widely used by developers around the world. React allows developers to create complex UI components by breaking them down into smaller, reusable parts called "components".

    One of the key features of React is its virtual DOM (Document Object Model), which allows developers to write code in a more declarative style, making it easier to reason about and maintain. React also supports server-side rendering, which can improve website performance and search engine optimization (SEO).

    React is often used in combination with other technologies such as Redux, React Router, and webpack to create scalable and maintainable web applications. It has a large and active community, with many resources available for learning and development.
    

    **[⬆ Back to Top](#table-of-contents)**


2.  ### What is JSX?

    JSX (JavaScript XML) is a syntax extension for JavaScript, which allows developers to write HTML-like code in their JavaScript files. JSX is most commonly used with React, where it enables developers to write reusable, declarative components that can be used to build user interfaces for web applications.

    In the example below, the text inside `<h1>` tag is returned as JavaScript function to the render function.

    ```jsx harmony
    export default function App() {
      return (
          <h1 className="greeting">{"Hello, this is a JSX Code!"}</h1>
      );
    }
    ```
    If you don't use JSX syntax then the respective JavaScript code should be written as below,

    ```javascript
    import { createElement } from 'react';

    export default function App() {
      return createElement(
        'h1',
        { className: 'greeting' },
        'Hello, this is a JSX Code!'
      );
    }
    ```

     <!-- <details><summary><b>See Class</b></summary> </details>-->

     **[⬆ Back to Top](#table-of-contents)**

3.  ### What is the difference between Element and Component?
   
    An `Element` is a plain JavaScript object that describes a component instance or a DOM node and its properties (props) and children. An element can be either a React component, a built-in HTML element, or a custom element.

    A `component` is a reusable piece of code that represents a part of the user interface (UI) and can have its own logic and state. It can be a function component, which is a simple function that returns an element, or a class component, which is a JavaScript class that extends the React.Component class and has its own state and lifecycle methods.

     <p>

    ```jsx harmony
    
    // Element
    const element = <h1>Hello, world!</h1>;

    // Component
    function Greeting(props) {
        return <h1>Hello, {props.name}!</h1>;
    }

    ```

     </p>

     **[⬆ Back to Top](#table-of-contents)**

4. ### What is the difference between function components and class components?

    #### Function Components
    A function component is a simpler and more concise way to define a component in React. It is essentially a JavaScript function that returns a React element. Here's an example of a simple function component that displays a greeting:

    ```jsx harmony
    
    import React from 'react';

    function Greeting(props) {
        return <h1>Hello, {props.name}!</h1>;
    }

    ```

    #### Class Components
    A class component is a more powerful and flexible way to define a component in React. It is a JavaScript class that extends the React.Component class and implements a render method. Here's an example of a simple class component that displays a greeting:

    ```jsx harmony
    
    import React from 'react';

    class Greeting extends React.Component {
        render() {
            return <h1>Hello, {this.props.name}!</h1>;
        }
    }

    ```
    **[⬆ Back to Top](#table-of-contents)**

5. ### When to use a Class Component over a Function Component?

    Function components are generally preferred over class components in React for several reasons:

    `Simplicity`: Function components are simpler and easier to read and write than class components.

    `Performance`: Function components are usually faster than class components because they don't create an instance of the component class. This means less memory is used and the component can be optimized more easily.

    `Hooks`: Function components can use Hooks, a feature introduced in React 16.8, which allow you to use state and other React features without using a class component.

    **[⬆ Back to Top](#table-of-contents)**

6. ### What are Pure Components?
   
    In React, a PureComponent is a subclass of Component that provides a performance optimization when your component's props and state don't change frequently. A PureComponent is essentially the same as a regular Component, except that it implements a shouldComponentUpdate() method that performs a shallow comparison of the props and state of the component to determine whether it needs to be re-rendered.

    **[⬆ Back to Top](#table-of-contents)**

7. ### What is state in React?
   
    The state is a built-in React object that is used to contain data or information about the component. A component’s state can change over time; whenever it changes, the component `re-renders`.

    State in React is managed using the `useState` hook, which is a built-in hook provided by React. The `useState` hook allows you to define and manage state variables within a functional component. It takes an initial value as an argument and returns an array with two elements: the current state value and a function to update the state value. 

        ```jsx harmony
    
    import React, { useState } from 'react';

    const Counter = () => {
    const [count, setCount] = useState(0); // Define and initialize state

    const increment = () => {
        setCount(count + 1); // Update state
    };

    return (
        <div>
            <p>Count: {count}</p>
            <button onClick={increment}>Increment</button>
        </div>
    );
    };

    export default Counter;

    ```
    

   **[⬆ Back to Top](#table-of-contents)**


