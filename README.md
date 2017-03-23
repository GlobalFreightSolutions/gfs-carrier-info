[![Build Status](https://travis-ci.org/GlobalFreightSolutions/gfs-carrier-info.svg?branch=master)](https://travis-ci.org/GlobalFreightSolutions/gfs-carrier-info)


# &lt;gfs-carrier-info&gt;

[Live Demo](http://codepen.io/globalfreight/pen/76c2bc927269938684d22ffbe81703e1)

The `gfs-carrier-info` widget is used to display a carrier icon, service description and further information URL for 'click and collect' styles services offered in the main Checkout widget.


## Install

```bash
# via bower
$ bower install gfs-carrier-info
```

## Usage
```html
<link rel="import" href="path_to_bower_components/gfs-carrier-info/gfs-carrier-info.html" />
```

<!---
```
<custom-element-demo>
    <template>
        <script src="../webcomponentsjs/webcomponents-lite.js"></script>
        <link rel="import" href="gfs-carrier-info.html">
        <next-code-block></next-code-block>
    </template>
</custom-element-demo>
```
-->

```html
<gfs-carrier-info
    visible="true"
    provider-name="DPD"
    country-code="GB">
</gfs-carrier-info>
```

More info and all the available properties can be found at [GFS widget portal](http://gfsdeveloperportal.azurewebsites.net/info/documentation/gfs-checkout/the-gfs-checkout-widgets/carrier-information-widget/ "The Carrier Information Widget")


### License

Apache License 2.0