# React Interview Questions & Answers

> Click :star:if you like the project. Pull Request are highly appreciated.

### Table of Contents

| No. | Questions                                                                                                                                                                                                                        |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|     | **Core React**                                                                                                                                                                                                                   |
| **:star:** | [What is React?](#what-is-react)                                                                                                                                                                                                 |
| *:star:*  | [What are the major features of React?](#what-are-the-major-features-of-react)                                                                                                                                                   |
| >:star:  | [What is JSX?](#what-is-jsx)                                                                                                                                                                                                     |
| 4   | [What is the difference between Element and Component?](#what-is-the-difference-between-element-and-component)                                                                                                                   |
| 5   | [How to create components in React?](#how-to-create-components-in-react)                                                                                                                                                         |
| 6   | [When to use a Class Component over a Function Component?](#when-to-use-a-class-component-over-a-function-component)                                                                                                             |
| 7   | [What are Pure Components?](#what-are-pure-components)                                                                                                                                                                           |
| 8   | [What is state in React?](#what-is-state-in-react)                                                                                                                                                                               |
| 9   | [What are props in React?](#what-are-props-in-react)                                                                                                                                                                             |
| 10  | [What is the difference between state and props?](#what-is-the-difference-between-state-and-props)                                                                                                                               |
| 11  | [Why should we not update the state directly?](#why-should-we-not-update-the-state-directly)                                                                                                                                     |
| 12  | [What is the purpose of callback function as an argument of setState()?](#what-is-the-purpose-of-callback-function-as-an-argument-of-setstate)                                                                                   |
| 13  | [What is the difference between HTML and React event handling?](#what-is-the-difference-between-html-and-react-event-handling)                                                                                                   |                                                                                                            |
| 16  | [What are synthetic events in React?](#what-are-synthetic-events-in-react)                                                                                                                                                                                                        |
| 18  | [What is "key" prop and what is the benefit of using it in arrays of elements?](#what-is-key-prop-and-what-is-the-benefit-of-using-it-in-arrays-of-elements)                                                                     |
| 19  | [What is the use of refs?](#what-is-the-use-of-refs)                                                                                                                                                                             |
| 20  | [How to create refs?](#how-to-create-refs)                                                                                                                                                                                       |
| 21  | [What are forward refs?](#what-are-forward-refs)                                                                                                                                                       |
| 24  | [What is Virtual DOM?](#what-is-virtual-dom)                                                                                                                                                                                     |
| 25  | [How Virtual DOM works?](#how-virtual-dom-works)                                                                                                                                                                                 |
| 26  | [What is the difference between Shadow DOM and Virtual DOM?](#what-is-the-difference-between-shadow-dom-and-virtual-dom)                                                                                                         |
| 27  | [What is React Fiber?](#what-is-react-fiber)                                                                                                                                                               |
| 29  | [What are controlled components?](#what-are-controlled-components)                                                                                                                                                               |
| 30  | [What are uncontrolled components?](#what-are-uncontrolled-components)                                                                                                                          |
| 32  | [What is Lifting State Up in React?](#what-is-lifting-state-up-in-react)                                                                                                                                                         |
| 33  | [What are the different phases of component lifecycle?](#what-are-the-different-phases-of-component-lifecycle)                                                                                                                   |
| 34  | [What are the lifecycle methods of React?](#what-are-the-lifecycle-methods-of-react)                                                                                                                                             |
| 35  | [What are Higher-Order components?](#what-are-higher-order-components)                                                                                                                                        |
| 37  | [What is context?](#what-is-context)                                                                                                                                                                                             |
| 38  | [What is children prop?](#what-is-children-prop)                                                                                                                               |
| 41  | [What is reconciliation?](#what-is-reconciliation)                                                                                                                                                                                                                                                         |
| 46  | [What are fragments?](#what-are-fragments)                                                                                                                                                                                                                                                                                      |
| 49  | [What are stateless components?](#what-are-stateless-components)                                                                                                                                                                 |
| 50  | [What are stateful components?](#what-are-stateful-components)                                                                                                                                                                   |
| 51  | [How to apply validation on props in React?](#how-to-apply-validation-on-props-in-react)                                                                                                                                         |
| 52  | [What are the advantages of React?](#what-are-the-advantages-of-react)                                                                                                                                                           |
| 53  | [What are the limitations of React?](#what-are-the-limitations-of-react)                                                                                                                                                         |
| 54  | [What are error boundaries in React v16](#what-are-error-boundaries-in-react-v16)                                                                                                                                                |
| 55  | [How are error boundaries handled in React v15?](#how-are-error-boundaries-handled-in-react-v15)                                                                                                                                 |
| 56  | [What are the recommended ways for static type checking?](#what-are-the-recommended-ways-for-static-type-checking)                                                                                                               |
| 57  | [What is the use of react-dom package?](#what-is-the-use-of-react-dom-package)                                                                                                                                                   |
| 58  | [What is the purpose of render method of react-dom?](#what-is-the-purpose-of-render-method-of-react-dom)                                                                                                                         |
| 59  | [What is ReactDOMServer?](#what-is-reactdomserver)                                                                                                                                                                               |
| 60  | [How to use InnerHtml in React?](#how-to-use-innerhtml-in-react)                                                                                                                                                                 |
| 61  | [How to use styles in React?](#how-to-use-styles-in-react)                                                                                                                                                                       |
| 62  | [How events are different in React?](#how-events-are-different-in-react)                                                                                                                                                         |
| 63  | [What will happen if you use setState in constructor?](#what-will-happen-if-you-use-setstate-in-constructor)                                                                                                                     |
| 64  | [What is the impact of indexes as keys?](#what-is-the-impact-of-indexes-as-keys)                                                                                                                                                 |
| 65  | [Is it good to use setState() in componentWillMount() method?](#is-it-good-to-use-setstate-in-componentwillmount-method)                                                                                                         |
| 66  | [What will happen if you use props in initial state?](#what-will-happen-if-you-use-props-in-initial-state)                                                                                                                       |
| 67  | [How do you conditionally render components?](#how-do-you-conditionally-render-components)                                                                                                                                       |
| 68  | [Why we need to be careful when spreading props on DOM elements??](#why-we-need-to-be-careful-when-spreading-props-on-dom-elements)                                                                                              |
| 69  | [How you use decorators in React?](#how-you-use-decorators-in-react)                                                                                                                                                             |
| 70  | [How do you memoize a component?](#how-do-you-memoize-a-component)                                                                                                                                                        |
| 78  | [Do Hooks replace render props and higher order components?](#do-hooks-replace-render-props-and-higher-order-components)                                                                                                         |
| 79  | [What is the recommended way for naming components?](#what-is-the-recommended-way-for-naming-components)                                                                                                                         |
| 80  | [What is the recommended ordering of methods in component class?](#what-is-the-recommended-ordering-of-methods-in-component-class)                                                                                               |
| 81  | [What is a switching component?](#what-is-a-switching-component)                                                                                                                                                                 |
| 82  | [Why we need to pass a function to setState()?](#why-we-need-to-pass-a-function-to-setstate)                                                                                                                                     |
| 83  | [What is strict mode in React?](#what-is-strict-mode-in-react)                                                                                                                                                                                              |
| 84 | [Is it possible to use async/await in plain React?](#is-it-possible-to-use-asyncawait-in-plain-react)                                                                                                                                                                                        |
|     | **React Router**                                                                                                                                                                                                                 |
| 85 | [What is React Router?](#what-is-react-router)                                                                                              |
| 130 | [How React Router is different from history library?](#how-react-router-is-different-from-history-library)                                                                                                                       |
| 131 | [What are the \<Router> components of React Router v4?](#what-are-the-router-components-of-react-router-v4)                                                                                                                      |
| 132 | [What is the purpose of push and replace methods of history?](#what-is-the-purpose-of-push-and-replace-methods-of-history)                                                                                                       |
| 133 | [How do you programmatically navigate using React router v4?](#how-do-you-programmatically-navigate-using-react-router-v4)                                                                                                       |
| 134 | [How to get query parameters in React Router v4](#how-to-get-query-parameters-in-react-router-v4)                                                                                                                |
| 137 | [How to implement default or NotFound page?](#how-to-implement-default-or-notfound-page)                                                                                                                                                                                                                                                                                         |
|     | **React Testing**                                                                                                                                                                                                                |
| 146 | [What is Shallow Renderer in React testing?](#what-is-shallow-renderer-in-react-testing)                                                                                                                                         |
| 147 | [What is TestRenderer package in React?](#what-is-testrenderer-package-in-react)                                                                                                                                                 |
| 148 | [What is the purpose of ReactTestUtils package?](#what-is-the-purpose-of-reacttestutils-package)                                                                                                                                 |
| 149 | [What is Jest?](#what-is-jest)                                                                                                                                                                                                   |
| 150 | [What are the advantages of Jest over Jasmine?](#what-are-the-advantages-of-jest-over-jasmine)                                                                                                                                   |
| 151 | [Give a simple example of Jest test case](#give-a-simple-example-of-jest-test-case)                                                                                                                                              |
|     | **React Redux**                                                                                                                                                                                                                  |
| 152 | [What is Flux?](#what-is-flux)                                                                                                                                                                                                   |
| 153 | [What is Redux?](#what-is-redux)                                                                                                                                                                                                 |
| 154 | [What are the core principles of Redux?](#what-are-the-core-principles-of-redux)                                                                                                                                                 |
| 155 | [What are the downsides of Redux compared to Flux?](#what-are-the-downsides-of-redux-compared-to-flux)                                                                                                                           |
| 156 | [What is the difference between mapStateToProps() and mapDispatchToProps()?](#what-is-the-difference-between-mapstatetoprops-and-mapdispatchtoprops)                                                                             |
| 157 | [Can I dispatch an action in reducer?](#can-i-dispatch-an-action-in-reducer)                                                                                                                                                     |
| 158 | [How to access Redux store outside a component?](#how-to-access-redux-store-outside-a-component)                                                                                                                                 |
| 159 | [What are the drawbacks of MVW pattern](#what-are-the-drawbacks-of-mvw-pattern)                                                                                                                                                  |
| 160 | [Are there any similarities between Redux and RxJS?](#are-there-any-similarities-between-redux-and-rxjs)                                                                                                                         |
| 161 | [How to dispatch an action on load?](#how-to-dispatch-an-action-on-load)                                                                                                                                                         |
| 162 | [How to use connect from React Redux?](#how-to-use-connect-from-react-redux)                                                                                                                                                     |
| 163 | [How to reset state in Redux?](#how-to-reset-state-in-redux)                                                                                                                                                                     |
| 164 | [Whats the purpose of at symbol in the redux connect decorator?](#whats-the-purpose-of-at-symbol-in-the-redux-connect-decorator)                                                                                                 |
| 165 | [What is the difference between React context and React Redux?](#what-is-the-difference-between-react-context-and-react-redux)                                                                                                   |
| 166 | [Why are Redux state functions called reducers?](#why-are-redux-state-functions-called-reducers)                                                                                                                                 |
| 167 | [How to make AJAX request in Redux?](#how-to-make-ajax-request-in-redux)                                                                                                                                                         |
| 168 | [Should I keep all component's state in Redux store?](#should-i-keep-all-components-state-in-redux-store)                                                                                                                        |
| 169 | [What is the proper way to access Redux store?](#what-is-the-proper-way-to-access-redux-store)                                                                                                                                   |
| 170 | [What is the difference between component and container in React Redux?](#what-is-the-difference-between-component-and-container-in-react-redux)                                                                                 |
| 171 | [What is the purpose of the constants in Redux? ](#what-is-the-purpose-of-the-constants-in-redux)                                                                                                                                |
| 172 | [What are the different ways to write mapDispatchToProps()?](#what-are-the-different-ways-to-write-mapdispatchtoprops)                                                                                                           |
| 173 | [What is the use of the ownProps parameter in mapStateToProps() and mapDispatchToProps()?](#what-is-the-use-of-the-ownprops-parameter-in-mapstatetoprops-and-mapdispatchtoprops)                                                 |
| 174 | [How to structure Redux top level directories?](#how-to-structure-redux-top-level-directories)                                                                                                                                   |
| 175 | [What is redux-saga?](#what-is-redux-saga)                                                                                                                                                                                       |
| 176 | [What is the mental model of redux-saga?](#what-is-the-mental-model-of-redux-saga)                                                                                                                                               |
| 177 | [What are the differences between call and put in redux-saga](#what-are-the-differences-between-call-and-put-in-redux-saga)                                                                                                      |
| 178 | [What is Redux Thunk?](#what-is-redux-thunk)                                                                                                                                                                                     |
| 179 | [What are the differences between redux-saga and redux-thunk](#what-are-the-differences-between-redux-saga-and-redux-thunk)                                                                                                      |
| 180 | [What is Redux DevTools?](#what-is-redux-devtools)                                                                                                                                                                               |
| 181 | [What are the features of Redux DevTools?](#what-are-the-features-of-redux-devtools)                                                                                                                                             |
| 182 | [What are Redux selectors and Why to use them?](#what-are-redux-selectors-and-why-to-use-them)                                                                                                                                   |
| 183 | [What is Redux Form?](#what-is-redux-form)                                                                                                                                                                                       |
| 184 | [What are the main features of Redux Form?](#what-are-the-main-features-of-redux-form)                                                                                                                                           |
| 185 | [How to add multiple middlewares to Redux?](#how-to-add-multiple-middlewares-to-redux)                                                                                                                                           |
| 186 | [How to set initial state in Redux?](#how-to-set-initial-state-in-redux)                                                                                                                                                         |
| 187 | [How Relay is different from Redux?](#how-relay-is-different-from-redux)                                                                                                                                                         |
| 188 | [What is an action in Redux?](#what-is-an-action-in-redux)                                                                                                                                                             |

## Core React

1.  ### What is React?

    React is a popular open-source JavaScript library used for building user interfaces (UI) in web applications. It was developed by Facebook and is widely used by developers around the world. React allows developers to create complex UI components by breaking them down into smaller, reusable parts called "components".

    One of the key features of React is its virtual DOM (Document Object Model), which allows developers to write code in a more declarative style, making it easier to reason about and maintain. React also supports server-side rendering, which can improve website performance and search engine optimization (SEO).

    React is often used in combination with other technologies such as Redux, React Router, and webpack to create scalable and maintainable web applications. It has a large and active community, with many resources available for learning and development.
    

    **[⬆ Back to Top](#table-of-contents)**


2.  ### What is JSX?

    _JSX_ stands for _JavaScript XML_ and it is an XML-like syntax extension to ECMAScript. Basically it just provides the syntactic sugar for the `React.createElement(type, props, ...children)` function, giving us expressiveness of JavaScript along with HTML like template syntax.

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

     <details><summary><b>See Class</b></summary>
     <p>

    ```jsx harmony
    class App extends React.Component {
      render() {
        return (
            <h1 className="greeting">{"Hello, this is a JSX Code!"}</h1>
        );
      }
    }
    ```

     </p>
     </details>

    **Note:** JSX is stricter than HTML

    **[⬆ Back to Top](#table-of-contents)**

3. 