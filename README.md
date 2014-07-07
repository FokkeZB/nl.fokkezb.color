# Alloy Color Picker Widget - Tests

This is the test branch for the [Alloy](http://appcelerator.com/alloy) [Color Picker Widget](https://github.com/FokkeZB/nl.fokkezb.color/tree/master).

* Source code: [https://github.com/FokkeZB/nl.fokkezb.color/tree/master](https://github.com/FokkeZB/nl.fokkezb.color/tree/master)
* Documentation: [http://color.fokkezb.nl](http://color.fokkezb.nl)
* Test app: [https://github.com/FokkeZB/nl.fokkezb.color/tree/test](https://github.com/FokkeZB/nl.fokkezb.color/tree/test)

## Preparing [![Built with Grunt](https://cdn.gruntjs.com/builtwith.png)](http://gruntjs.com/)

The repo has a `Gruntfile.js` for [Grunt](http://gruntjs.com/getting-started) to replace the app's `app/widgets/nl.fokkezb.color` with a copy from the `master` branch. The configuration assumes to find this branch at `../master`.

Install Grunt and the dependencies via:

	$ sudo npm i -g grunt
	$ sudo npm install

## Running
To replace the app's copy of the widget and build the app for the simulator simply execute:

	$ grunt

## License

	The MIT License (MIT)
	
	Copyright (c) 2014 Fokke Zandbergen
	
	Permission is hereby granted, free of charge, to any person obtaining a copy
	of this software and associated documentation files (the "Software"), to deal
	in the Software without restriction, including without limitation the rights
	to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
	copies of the Software, and to permit persons to whom the Software is
	furnished to do so, subject to the following conditions:
	
	The above copyright notice and this permission notice shall be included in all
	copies or substantial portions of the Software.
	
	THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
	IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
	FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
	AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
	LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
	OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
	SOFTWARE.