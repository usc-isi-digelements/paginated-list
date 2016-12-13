# paginated-list

A Polymer Element showing a paginated list of items.

### Example
```html
<paginated-list
  items="[[items]]"
  total-items="[[total]]"
  shown-items="{{shown}}"
  loading="[[loading]]"
  page="{{page}}">
</paginated-list>
```

### Styling

`<paginated-list>` provides the following custom properties and mixins for styling:

Custom property               | Description                | Default
------------------------------|----------------------------|--------
`--paginated-list-max-height` | Maximum height of the list | none

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

