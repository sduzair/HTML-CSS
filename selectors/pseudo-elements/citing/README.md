# Using the `::after` pseudo-selector for citation symbol

The `::after` pseudo-selector can be used to add a citation symbol to a link.

<div style="text-align:center">
<img src="127.0.0.1_5500_pseudo-selectors_citing_index.html.png" alt="Screenshot of the example page" width="300"/>
</div>

```css
h1 {
  position: relative;
}

h1::after {
  content: '[1]';
  font-size: 0.5em;
  position: absolute;
}
```
