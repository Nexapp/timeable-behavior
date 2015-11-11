# timeable-behavior

An element providing timing capabilities

## How to use it

### In bower.json
	"dependencies": {
		"timeable-behavior": "nexapp/timeable-behavior"
	}

### In command line
	bower install --save nexapp/timeable-behavior

## Contribution
	
### Install dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install


### Playing With The Element

If you wish to work on the element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep the element's
bower dependencies in line. You can install it via:

    npm install -g polyserve

And you can run it via:

    polyserve

Once running, you can preview the element at
`http://localhost:8080/components/timeable-behavior/`


### Testing The Element

Simply navigate to the `/test` directory of your element to run its tests. If
you are using Polyserve: `http://localhost:8080/components/timeable-behavior/test/`

#### web-component-tester 

The tests are compatible with [web-component-tester](https://github.com/Polymer/web-component-tester).
Install it via:

    npm install -g web-component-tester

Then, you can run your tests on _all_ of your local browsers via:

    wct

##### WCT Tips

`wct -l chrome` will only run tests in chrome.

`wct -p` will keep the browsers alive after test runs (refresh to re-run).

`wct test/some-file.html` will test only the files you specify.
