*This repository is a mirror of the [component](http://component.io) module [ianstormtaylor/redraw](http://github.com/ianstormtaylor/redraw). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/ianstormtaylor-redraw`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# redraw

  Force a redraw on an element. This can sometimes be useful to force transitions to run instead of letting the browser optimize them out. Obviously, this should be a last-ditch measure.

## Installation

    $ component install ianstormtaylor/redraw

## Example
  
```js
var redraw = require('redraw');
redraw(el);
```

## API

### redraw(el)
  Force a redraw on a given `el`.

## License

  MIT
