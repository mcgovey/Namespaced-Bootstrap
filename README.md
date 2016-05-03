## What is in this directory

This directory contains a file that can be used for implementations where traditional Bootstrap classes would clash with those rules set in other stylesheets.

**You must include the class "bootstrap_inside" to use the Bootstrap classes**

## Where to find the file in this directory

The scoped bootstrap file can be found in the "output" folder

## Examples for Qlik Sense

If you are using this to add bootstrap to your Qlik Sense Extensions you can include the code snippet below to inject the class used for scoping into your main div.

```
$bootstrapStyle.addClass( 'bootstrap_inside' );
```

There is also a file included in examples that gives you a fully working extension example.

## How was this created

This was created using node.js, npm, grunt, and bower per the instructions laid out in a blog post by Stefan Walter

[Link to Blog Post](http://qliksite.io/qlik-sense/using-bootstrap-css-qliksense-visualization-extensions/)