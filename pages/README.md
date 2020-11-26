# Pages

Pages are defined in two files:
* the xml definition of the data in config/templates/pages/
* the twig template to render the data in templates/pages/

The connection between both files is defined in the xml, i.g. like this:
```xml
<view>pages/homepage</view>
```

There is no file extension, because may have more than one template. In this example maybe
* templates/pages/homepage.html.twig for HTML output
* templates/pages/homepage.json.twig for JSON output
* ...

