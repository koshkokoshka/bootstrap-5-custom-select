# Bootstrap 5 custom select
Simple and clean select library for Bootstrap 5

Features:
- Small size
- No custom styles, only the native Bootstrap components appearance
- Supports arbitrary level of nesting
- Keyboard event handling
- Fallback to native `<select>` element

## Usage example

Just specify class `custom-select` for your `<select>` element(s)

```html
<select class="form-select custom-select">
  
    <option disabled selected>Placeholder</option>
  
    <option value="0" data-level="0">Category 1</option>
  
    <option value="1" data-level="0">Category 2</option>
    <option value="2" data-level="1">Subcategory 1</option>
    <option value="3" data-level="1">Subcategory 2</option>

</select>

<script src="/custom-select.js"></script>
```
- The `data-level` attribute specifies the nesting level
