# things-stamp

## This is a component that prints the information about creation and modification of Things Stamp resource.


## Example:


```js
    this.resource = {
    "creator" : {
      "name" : "남종호",
      "email" : "shortstop@hatiolab.com"
    },
    "updater" : {
      "name" : "남종호",
      "email" : "shortstop@hatiolab.com"
    },
    "created_at" : "2016-12-07 02:28:17",
    "updated_at" : "2016-12-07 02:28:17"
    }
```
code:
```html
    <things-stamp
      resource="[[response]]">
    </things-stamp>
```

*****
</br></br>


## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

## Playing With Your Element

If you wish to work on your element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polymer-cli

And you can run it via:

    polymer serve

Once running, you can preview your element at
`http://localhost:8080/components/things-stamp/`, where `things-stamp` is the name of the directory containing it.
