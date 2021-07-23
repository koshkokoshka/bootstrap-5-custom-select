# Bootstrap 5 custom select
Simple and clean select library for Bootstrap 5

[Example](https://oeoe.moe/bootstrap-5-custom-select)

Features:
- Small size
- No custom styles
- **Supports arbitrary level of nesting**
- Handles keyboard events
- Fallbacks to native `<select>` element

## Getting started

1. [Download custom-select.js](https://raw.githubusercontent.com/smugd/bootstrap-5-custom-select/main/custom-select.js)
2. Include it on your page `<script src="custom-select.js"></script>`
3. Add `.custom-select` class to your `<select/>` element(s) or manually call `customSelect(select)`

## Usage example

```html
<select class="form-select custom-select">
  
    <option disabled selected>Placeholder</option>
  
    <option value="0" data-level="0">Category 1</option>
  
    <option value="1" data-level="0">Category 2</option>
    <option value="2" data-level="1">Subcategory 1</option>
    <option value="3" data-level="1">Subcategory 2</option>

</select>

<script src="custom-select.js"></script>
```
- `data-level` attribute specifies the nesting level
