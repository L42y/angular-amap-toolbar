# [angular](https://angularjs.org)-[amap](http://developer.amap.com)-[toolbar](http://developer.amap.com/api/javascript-api/reference/plugin/#AMap.ToolBar)

## Installation

1. `bower install --save angular-amap-toolbar`

2. including `angular-amap-toolbar.js` script file provided by this component into your application

3. adding `l42y.amap.toolar` as a module dependency to your application

## Usage

```html
<div amap-map
     amap-toolbar="controller.mapToolbarOptions"
     amap-toolbars="ruler, direction, location, labels">
</div>
```

### Options (optional)

1. specify [ToolbarOptions](http://developer.amap.com/api/javascript-api/reference/plugin/#m_ToolbarOptions) with `amap-toolbar`

2. specify which toolbar component to display with `amap-toolbars`, available options are:

    1. `ruler`

    2. `labels`

    3. `location`

    4. `direction`

## License

[WTFPL](http://wtfpl.org)
