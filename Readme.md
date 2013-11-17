
# get-user-media

  Cross browser navigator.getUserMedia with a node api.

## Example

```js
var getUserMedia = require('get-user-media');

getUserMedia({ audio: true }, function(err, stream) {
  if (err) throw err;

  // do something with the stream
});
```

## API

### getUserMedia(constraints, fn)

  Request user media based on given `constraints`, which currently can be
  
```js
{
  audio: true,
  video: true
}
```
  
  Call `fn` with the potential `Error` and the resulting input stream.

## Installation

  Install with [npm](https://npmjs.org):
  
    $ npm install get-user-media
  
  Install with [component(1)](http://component.io):
  
    $ component install juliangruber/get-user-media

## License

  MIT
