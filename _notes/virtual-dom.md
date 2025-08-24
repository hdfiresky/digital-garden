# Virtual DOM

The Virtual Document Object Model (DOM) is a programming concept where a virtual representation of a UI is kept in memory and synced with the "real" DOM.

## How it works

1.  When the state of a [[react]] application changes, a new Virtual DOM tree is created.
2.  This new tree is compared ("diffed") with the previous Virtual DOM tree.
3.  React then calculates the most efficient way to update the real DOM with these changes.

This process, known as **reconciliation**, is what makes React and other modern frameworks performant. It minimizes direct manipulation of the actual DOM, which is a slow operation.
