# React Components and State

## Components

Components are the building blocks of a React application. There are two types of components: functional and class components.

```jsx
// Functional Component
function Welcome(props) {
  return <h1>Hello, {props.name}</h1>;
}

// Class Component
class Welcome extends React.Component {
  render() {
    return <h1>Hello, {this.props.name}</h1>;
  }
}
```
## State
State is used to manage data in a React component.
```jsx
import React, { useState } from 'react';

function Counter() {
  const [count, setCount] = useState(0);

  return (
    <div>
      <p>You clicked {count} times</p>
      <button onClick={() => setCount(count + 1)}>Click me</button>
    </div>
  );
}

export default Counter;
```
## Conclusion
With these basics, you are ready to start building simple React applications. Keep practicing and explore more advanced topics.
