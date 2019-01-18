# Charts
Description on charts and implementation using Recharts react libary

 The D3 in D3.js stands for data-driven documents. **D3.js** is a low-level library that provides the building blocks necessary to create interactive visualizations. 
 
 It uses web standards such as SVG, HTML, canvas, and CSS to assemble a front-end toolbox.
 
**D3.js** loads data and attaches it to the **DOM**. Then, it binds that data to DOM elements and transforms those elements, transitioning among states if necessary.

On the other side, **React  library** that helps us build user interfaces by composing components. These components keep track of their **state and pass in properties** to  re-render themselves effectively , optimizing the performance of the application.

The virtual DOM, which is a representation of the DOM’s current state, is the technology that enables React’s re-rendering optimizations. 

The library uses a complex **diff algorithm** to understand which parts of the application need to re-render when the conditions change. This diff algorithm is called the **“ reconciliation algorithm ”**

When rendering components that contain a list of items, developers need to use a  **unique “key”** property attached to the child  components. This value helps the diff algorithm to figure out if the item needs to be re-rendered when new data — or state, as it is called in the React world — is passed to the component. 

The  **reconciliation algorithm** checks the values of the keys  to see whether the item needs to be added or removed.

**Combining react and D3:**

Both React and D3 share the goal of helping us deal with the DOM and its complexity in a highly optimized way. They also share a preference for pure functions — code that, **for a given input, always returns the same output without incurring side effects**— and stateless components.
 
 However,  the **shared concern** about the DOM makes these two opinionated libraries clash when determining  which is to **render and animate the user interface elements** .
 
We could establish a hard rule, though: They should never share DOM control. That would be a **recipe for trouble**.

So it’s better not to allow two opinionated libraries like D3.js and React.js.

Coming to React Js libraries I had gone through different open source libraries and considered two depending on the charts they support.

**recharts and Formidable** are good enough opensource uses D3 library internally.

**ReactJs Highcharts  and  Fusion Charts**  provide little bit more chart types but it's chargable.
