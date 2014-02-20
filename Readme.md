*This repository is a mirror of the [component](http://component.io) module [swatinem/style-canvas](http://github.com/swatinem/style-canvas). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/swatinem-style-canvas`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# style-canvas

  Use CSS to style canvas paths

## Installation

    $ component install Swatinem/style-canvas

## Example

```css
.stroke {
  stroke: #ccc;
  stroke-width: 5;
  stroke-linejoin: round;
  stroke-linecap: round;
}
```

```js
ctx.beginPath();
[…]
styleCanvas(ctx, '.stroke');
ctx.stroke();
```

## License

  GPLv3
