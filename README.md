# plotly.dart

A [Dart](http://www.dartlang.org/) interface to
[plotly.js](https://plot.ly/javascript/), plotly.dart
is a high-level, declarative charting library.

## Usage

```dart
var trace = {
  'x': [1, 2, 3, 4],
  'y': [10, 15, 13, 17],
  'mode': 'markers'
};

var layout = {
  'title': 'Scatter Plot',
  'height': 800,
  'width': 960
};

Plot.id('myDiv', [trace], layout);
```

### Update

To update the plotly distribution go to https://github.com/plotly/plotly.js/tags 
download the latest tag, extract the archive and then pick from the 
`dist` folder the `plotly.min.js` file and put it into the `/lib` folder.

