[![Build Status](https://travis-ci.org/GlobalFreightSolutions/gfs-carrier-info.svg?branch=master)](https://travis-ci.org/GlobalFreightSolutions/gfs-carrier-info)


# &lt;gfs-carrier-info&gt;

The `gfs-carrier-info` widget is used to display a carrier icon, service description and further information URL for 'click and collect' styles services offered in the main Checkout widget.

## Install

```bash
# via bower
$ bower install --save gfs-carrier-info
```

## Usage

1. Import Web Components' polyfill:

```html
<script src="bower_components/webcomponentsjs/webcomponents-lite.js"></script>
```

2. Import Custom Element:

```html
<link rel="import" href="bower_components/gfs-carrier-info/gfs-carrier-info.html">
```

3. Start using it!

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

More info and all the available properties can be found at [GFS widget portal](http://developer.justshoutgfs.com/info/documentation/gfs-checkout/the-gfs-checkout-widgets/carrier-information-widget/ "The Carrier Information Widget")


## License

[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0.html)