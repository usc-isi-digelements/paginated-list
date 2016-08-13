# paginated-list

A polymer web component that shows a paginated list of items.

Example:
```html
        <paginated-list
          items="[[items]]"
          total-items="[[total]]"
          shown-items="{{shown}}"
          loading="[[loading]]"
          page="{{page}}">
        </paginated-list>
```

Custom mixins:
```html
        --paginated-list-max-height
```

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install
