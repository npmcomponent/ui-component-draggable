*This repository is a mirror of the [component](http://component.io) module [ui-component/draggable](http://github.com/ui-component/draggable). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/ui-component-draggable`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# draggable

  make any element draggable.

## Installation

    $ component install ui-component/draggable

## Example

```js
var el = document.querySelector('#el');
var draggable = require('draggable')(el);
draggable.build();
```

## API

### draggable(el[, opts])

  Create a new `Draggable` with `el` and optional `opts` object.

### draggable.build()

  bind all events.

### draggable.destroy()

  unbind all events.

## License

  MIT
