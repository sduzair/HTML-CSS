# CSS Grid auto-fit property

The grid template columns property can be used to define the number of columns in a grid layout. The `auto-fit` keyword can be used to automatically fit columns into the available space. The columns will be automatically created or removed to fill the available space.

<div style="text-align:center">
  <img src="Animation.gif" alt="Alt Text" width="300">
</div>

```css
.box {
  --col: 6;
  --row: 6;
  --gap: 2px;
  --box-side: 20px;
  background: transparent;
  background-color: tomato;
  display: grid;
  width: calc(var(--col)*var(--box-side) + (var(--col) - 1)*var(--gap));
  grid-template-columns: repeat(auto-fit, var(--box-side));
  grid-template-rows: repeat(var(--row), var(--box-side));
  gap: var(--gap);
}
```
