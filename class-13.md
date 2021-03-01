# Class-13

## Local storage for web applications

* on of the advantages that the  'native client apps' held over 'web applications' is having a persistent local storage.

* cookies invented in the early days of wep , it can held a small-sized capacity of  persistent local storage.

* cookies can slow down your web application is they are included in every HTTP request.

* cookies  are included in every HTTP request which means you send your data over the internet un-encrypted.

* HTML5 storage solved all the pervious storage problems as its natively implemented on the web browser and more secure than cookies.

```HTML5
function supports_html5_storage() {
  try {
    return 'localStorage' in window && window['localStorage'] !== null;
  } catch (e) {
    return false;
  }
}
```

> code to check HTML5 storage support on your browser;

* [Modernizr](diveinto.html5doctor.com/detect.html#modernizr) which is a JS library used to detect HTML5 and CSS3

* HTML5 based on key-value pairs, keys are strings ,value is any JS supported data type.

* HTML5 storage had pre-defined method's in JS to interact with -and use- it.

* HTML5 storage data limitation is 5 MByte,`QUOTA_EXCEEDED_ERR` will show up when you exceed the limit.

* Data is stored as strings you needed to coerce it yourself when you retrieve it.

* web SQL Database is a strong competitor to the HTML5.
