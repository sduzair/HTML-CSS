# :has() Pseudo-class

The `:has()` pseudo-class takes a selector list as its argument, and selects an element if any of the selectors in the list are true for that element.

<div style="text-align:center">
<img src="127.0.0.1_5500_pseudo-classes_has_index.html.png" width="400px"/>
</div>

```scss
.link a {
  position: relative;
}

.link a::after {
  @include material-icon();
  content: $link-icon;
}

.section:has(.link) > .link {
  position: absolute;
  top: 0;
  margin: 0;
}
```

Only the `.link` elements that are a child of a `.section` element will have `absolute` positioning applied to it.
