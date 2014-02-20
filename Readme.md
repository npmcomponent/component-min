*This repository is a mirror of the [component](http://component.io) module [component/min](http://github.com/component/min). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-min`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# min

  Min value utility

## Installation

    $ component install component/min

## API

### min(array)

  Return the min value in `array`:

```js
min([1,5,6,1,2,0])
```

### min(array, fn)

  Min value in `array` with callback `fn(val, i)`:

```js
var age = min(users, function(u){ return u.age })
```

### min(array, string)

  Min value in `array` with the given property `string`:

```js
var age = min(users, 'age')
```

# License

  MIT
