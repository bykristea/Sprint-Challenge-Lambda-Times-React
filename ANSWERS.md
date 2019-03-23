- [ ] What are PropTypes used for? Please describe why it's important to type check our data in JavaScript.
Answer: 
PropTypes are a way to catch bugs before they become a problem. If data is laid out in a specific way and passed around to components via other components, you can think of PropTypes as a way to ensure the type of data being passed around.

- [ ] Describe a life-cycle event in React?
Answer:  Lifecycle methods are special methods each component can have that allow us to add phases when specific conditions happen (i.e. when the component first renders or when the component gets updated with new data, etc).

- [ ] Explain the details of a Higher Order Component?
Answer: A higher-order component in React is a pattern used to share common functionality between components without repeating code, used as a function.A HOC function takes a component as an argument and returns a component. It transforms a component into another component and adds additional data or functionality.

- [ ] What are three different ways to style components in React? Explain some of the benefits of each.
Answer:
CSS Stylesheets: 
Pros - All styling code is within one global css file or a few css files contained within a common file directory as the elements they are styling which makes it easier to locate where the styling is located and keep all styling in one location. Developer has full control on all styling. No new syntax to learn or dependies/installs. No additional nested elements as all coded elements are styled through class names.
Cons - Must style every element. Hard to find styling of specific elements quickly; developer would have to look through many lines of a global stylesheet.

CSS Libraries/Frameworks:
Pros - Do not have to style every element as many elements and components are pre-styled. Less actually css code lines required which cuts back on CSS stylesheets. 
Cons - Harder to add personal styling to a Libraries pre styled component. Does require dependencies/installs. Have to learn the libraries/framworks syntax and code library. 

Styled-Components:
Pros: All styled elements are coded in the js Component file. Elements styles can easily be found based on the location of the component. Can pass in css props through js.
Cons: Dependencies/installs required.  Can create a very deep nested element system with random assigned class names making it difficult to find elements and or reference elements.