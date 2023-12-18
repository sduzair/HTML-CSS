# Psuedo classes

For keeping pseudo classes, that represent states of elements, in a single place. This promotes modularity and reusability.

```css
button {
  margin-top: calc(var( -- spacing-step) * 2);
  background-color: var( -- color-accent-secondary);
  border: var( -- color-accent-secondary-darker) 1px solid;
  color: var( -- color-text);
  font-weight: bold;
  cursor: pointer;

  &:hover {
    opacity: 0.8;
  }

  &:active {
    background-color: var( -- color-accent-secondary-darker);
    border: var( -- color-accent-secondary) 1px solid;
  }

  &. reset-button {
    background-color: transparent;
    border: var( -- color-primary) 1px solid;
  }
}
```