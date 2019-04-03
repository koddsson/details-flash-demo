# Dismissable flash element demo

Use `<details>` and some CSS to make a dismissable flash element.

## Usage

```html
<details open>
  <summary>
    X
  </summary>
  Dismissable message goes here
</details>
```

```css
details:not([open]) {
  display: none;
}
```
