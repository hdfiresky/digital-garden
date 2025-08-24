# State Management

In frontend applications, especially with libraries like [[react]], state management refers to the practice of managing the data that your application depends on.

## Why is it needed?

As applications grow, passing state down through many levels of components (prop drilling) becomes cumbersome and hard to maintain. State management libraries provide a centralized store for your application's state.

## Popular Libraries

- **Redux:** One of the original and most popular state management libraries for React.
- **Zustand:** A smaller, simpler, and more modern alternative to Redux.
- **MobX:** Uses observables to make state management simple and scalable.

Choosing the right state management strategy depends on the complexity of your application. Sometimes, [[react-hooks]] like `useState` and `useContext` are sufficient.
