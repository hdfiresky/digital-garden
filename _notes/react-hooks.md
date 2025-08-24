# React Hooks

Hooks are functions that let you "hook into" [[react]] state and lifecycle features from function components. They were introduced in React 16.8.

## Basic Hooks

- **`useState`:** Lets you add state to a functional component.
- **`useEffect`:** Lets you perform side effects in functional components. This can be for data fetching, subscriptions, or manually changing the DOM.
- **`useContext`:** Accepts a context object and returns the current context value.

## Additional Hooks

- **`useReducer`:** An alternative to `useState`. Often preferred for complex state logic.
- **`useCallback`:** Returns a memoized callback.
- **`useMemo`:** Returns a memoized value.

Hooks allow you to reuse stateful logic without changing your component hierarchy, which is a major advantage over class components.
