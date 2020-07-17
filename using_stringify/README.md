# JSON Stringify

* This is a simple JSON API for read and display 
* JSON files.

## HTML
<pre id="json"></pre>

## JavaScript
var data = {
     "data": {
          "attribute1": "value1",
          "attribute2": "value2",
     },
     "attribute3": "value3"
};

document.getElementById("json").innerHTML = JSON.stringify(data, undefined, 2);
OR
$("#json").html(JSON.stringify(data, undefined, 2)); // For jQuery

``` json
{
  "data": {
    "attribute1": "value1",
    "attribute2": "value2"
  },
  "attribute3": "value3"
}
```
