# CSS Selectors: Direct Descendant and All Descendants

## Direct Descendant Selector

Selects only the direct `h1` element children of the parent element.

<div style="text-align:center">
<img src="127.0.0.1_5500_selectors_index.html.png" width=400px>
</div>

```css
.parent>h1 {
  color: brown;
}
```

## All Descendants Selector

Selects all the `h1` element children of the parent element.

<div style="text-align:center">
<img src="127.0.0.1_5500_selectors_index.html (1).png" width=400px>
</div>

```css
.parent h1 {
  color: brown;
}
```
