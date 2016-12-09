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
