# PolyK.

This library was written by [Ivan Kuckir](http://www.ivank.net). This repository serves to provide [Bower support](http://bower.io/search/?q=polyk).

## What is PolyK?

PolyK is JavaScript tool for working with polygons. It uses several basic principles to be super simple and super universal:

* **No classes.** PolyK does not have any classes or special data structures. PolyK consists of static functions only.
* **What is polygon?** For PolyK, polygon is an array of numbers. Each two of them are X and Y coordinate of polygon vertex.
* **Simplicity and speed.** Since PolyK does not make you use any special data structures, it is very easy to implement into your project. Since all JS engines are optimised for work with arrays, PolyK runs very fast.

PolyK was used in the game [Tiny Monsters](http://tinymonsters.ivank.net/). Do you like the project? [Make a donation](https://www.paypal.com/au/cgi-bin/webscr?cmd=_flow&SESSION=lVWmm5XwRF3D6AwScgjgqh6znJQXHcjKbhJQlW5pIizCZK6Pc8EtJVNwR_a&dispatch=50a222a57771920b6a3d7b606239e4d529b525e0b7e69bf0224adecfb0124e9b61f737ba21b081984719ecfa9a8ffe80733a1a700ced90ae)!

## Installation.

It depends on how you are using PolyK. You can download and handle manually, use Bower or NPM.

You can download the file from the [downloads page](http://polyk.ivank.net/?p=download).

For use with as Bower package:

    $ bower install polyk

To install as NPM package with either node, browserify, or webpack:

    $ npm install -S polyk

## Resources.

* [Homepage](http://polyk.ivank.net/).
* [Demos](http://polyk.ivank.net/?p=demos).
	* [Point Intersection](http://polyk.ivank.net/?p=demos&d=intersect).
	* [Triangulation](http://polyk.ivank.net/?p=demos&d=triangulate).
	* [Slicing](http://polyk.ivank.net/?p=demos&d=slice).
	* [Ray Casting](http://polyk.ivank.net/?p=demos&d=raycast).
	* [Closest Edge](http://polyk.ivank.net/?p=demos&d=closestedge).
* [Documentation](http://polyk.ivank.net/?p=documentation).
* [Discussion](http://polyk.ivank.net/?p=discussion).