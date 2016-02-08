# Leuk-Slider

Slider for the LeukaemiaCare Homepage

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install


## Testing the element

    npm install -g polyserve

And you can run it via:

    polyserve
    or
    polyserve -H 192.168.1.51

Once running, you can preview your element at
`http://localhost:8080/components/leuk-slider/`


## Testing Your Element

Simply navigate to the `/test` directory of your element to run its tests. If
you are using Polyserve: `http://localhost:8080/components/leuk-slider/test/`

### web-component-tester

The tests are compatible with [web-component-tester](https://github.com/Polymer/web-component-tester).
Install it via:

    npm install -g web-component-tester

Then, you can run your tests on _all_ of your local browsers via:

    wct

#### WCT Tips

`wct -l chrome` will only run tests in chrome.

`wct -p` will keep the browsers alive after test runs (refresh to re-run).

`wct test/some-file.html` will test only the files you specify.


## gh-pages

To publish to GH-Pages,

	yo polymer:gh 

[`generator-polymer`](https://github.com/yeoman/generator-polymer).
