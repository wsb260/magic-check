# Magic-check
Beautify Radio and Checkbox with pure CSS.

### Demo

[Demo](http://forsigner.com/magic-check)

### Install

``` bash
# bower
bower install --save magic-check

# npm
npm install --save magic-check
```

### Usage

```html
<link rel="stylesheet" href="bower_components/magic-check/css/magic-check.css">
```

**Checkbox**

```html
<div>
  <input class="magic-checkbox" type="checkbox" name="layout"> Normal
</div>

<div>
  <input class="magic-checkbox" type="checkbox" name="layout" id="hello" checked="checked">
  <label for="hello">Checked</label>
</div>

<div>
  <input class="magic-checkbox" type="checkbox" name="layout" disabled="disabled"> Disabled
</div>

<div>
  <input class="magic-checkbox" type="checkbox" name="layout"checked disabled="disabled" >
   Checked && Disabled
</div>
```

**Radio**

```html
<div>
  <input class="magic-radio" type="radio" name="radio"> Normal
</div>

<div>
  <input class="magic-radio" type="radio" name="radio" checked> Checked
</div>

<div>
  <input class="magic-radio" type="radio" id="world" disabled="disabled">
  <label for="33">Disabled</label>
</div>

<div>
  <input class="magic-radio" type="radio" disabled="disabled" checked>
  <label>Checked && Disabled</label>
</div>
```

### Browser compatibility

Chrome
Firefox
Safari
Opera
IE9 && IE9+


### License

  [MIT](LICENSE)
