# React Cheat Sheet

## Create React App

```sh
npx create-react-app my-app
cd my-app
npm start
```
## Components
```jsx
// Functional Component
function ComponentName(props) {
  return <div>{props.children}</div>;
}

// Class Component
class ComponentName extends React.Component {
  render() {
    return <div>{this.props.children}</div>;
  }
}
```
## State
```jsx
import React, { useState } from 'react';

function ComponentName() {
  const [state, setState] = useState(initialState);
  return <div>{state}</div>;
}
```
