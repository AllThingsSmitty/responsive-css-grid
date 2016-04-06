# Responsive CSS Grid

A straightforward 8-column fluid layout based on `box-sizing`.


## Classes

These CSS classes for column sizes are specific to the total width of `<div class="container">`:

| class | column width |
|---|---|
| `.col-1-2` | half |
| `.col-2-3` | two-thirds |
| `.col-1-3` | one-third |
| `.col-1-4` | one-fourth |
| `.col-1-8` | one-eighth |


## Example

```html
<div class="container">
  <div class="row clearfix">
    <div class="col-2-3"> <!-- column is 2/3 the total width -->
      Your content
    </div>
    <div class="col-1-3"> <!-- column is 1/3 the total width -->
      Your content
    </div>
  </div>
  ...
```