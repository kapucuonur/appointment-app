# Appointment App

### yarn istall

### yarn start

# Kullanılan Paketler

- bootstrap and react-boostrap => https://react-bootstrap.netlify.app/
- react-icons => https://react-icons.github.io/react-icons/

# Lifting State Up

It’s a common pattern that React developers should know. It helps you avoid more complex (and often unnecessary) patterns for managing your state.

#### React Lifting State Up Nedir?

- React Lifting State Up is the process of moving state shared by multiple components to the nearest common ancestor component. This helps manage state across components in a consistent and organized manner.

#### Why is it used?

- When the same state needs to be used by more than one component
- When the state needs to be updated by more than one component
- To make components more independent and reusable

In React, the data flow is always one-way. From top to bottom. There is no data flow between sibling components. Therefore, if the same state is needed in more than one component or if the state needs to be managed by both the parent and the child components, then the Lifting State Up concept is needed.

- In such cases, the relevant state is moved to the common parent and defined there and distributed from there. By delivering the setter method to the children via props, the state is updated by the relevant children. In this way, the direction of the data flow in React actually changes. In other words, we provide data flow between siblings from bottom to top in unnatural ways.

**Of course, you need to be careful when using it. We should not forget that moving the states up will increase the rendering.**

# Crypto: randomUUID() method

This built-in method (runs in the browser environment) creates a random unique identifier. It can be used for the id value when creating local data. Thus, it eliminates the need for 3rd party libraries such as uuid.

- https://developer.mozilla.org/en-US/docs/Web/API/Crypto/randomUUID
-

# serve

- https://www.npmjs.com/package/serve
- Package for viewing the build folder.
