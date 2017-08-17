# color cat
[demo](https://zvakanaka.github.io/color-cat)

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="color-cat.html">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/webcomponentsjs/1.0.8/webcomponents-hi-sd-ce.js"></script>
    This: <color-cat inline>^ↀᴥↀ^</color-cat> is a color-cat.
  </template>
</custom-element-demo>
```
-->

## Usage
### Default
```html
<color-cat>Colorful cat</color-cat>
```
### Fit
```html
<color-cat fit>Colorful cat
    with line
breaks.</color-cat>
```
```html
<color-cat fit>   _____      _
  / ____|    | |
 | |     __ _| |_ ___
 | |    / _` | __/ __|
 | |___| (_| | |_\__ \
  \_____\__,_|\__|___/
</color-cat>
```
### Inline
```html
<p>Put a <color-cat inline>Colorful cat</color-cat> in a sentence.</p>
```

| Attribute | Behavior |
| :------------- | :------------- |
| inline | Looks `like this`, only colorful|
| fit | shrink to size of color-cat content |

| CSS Variables |
| :------------- |
| `--background-color` |
| `--color` |
| `--color-red` |
| `--color-orange` |
| `--color-yellow` |
| `--color-green` |
| `--color-blue` |
| `--color-magenta` |
