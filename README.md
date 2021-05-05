# OVR Toolkit Custom Apps Helper Library

A library to simplify the usage of the OVR Toolkit custom apps API.

## Usage

First, either include the file in your html

```html
<script src="ovrt-helper.js"></script>
```

or uncomment the last few lines and include it as a common.js module:

```javascript
const { OVRT } = require("./ovrt-helper");
```

Afterwards you can instantiate an `OVRT` object and be good to go:

```javascript
const ovr = new OVRT({ function_queue: true }); // function queue allows function calls without waiting for the API ready event
```

## Reference

*TODO: finish the documentation.*