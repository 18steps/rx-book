# for

`Rx.Observable.for(sources, resultSelector)`
<a href="#rxobservableforsources-resultselector">#</a> [&#x24C8;](https://github.com/Reactive-Extensions/RxJS/blob/master/tests/observable/for.js "View in source")

Concatenates the observable sequences or Promises obtained by running the specified result selector for each element in source.
There is an alias for this method called `forIn` for browsers <IE9

![for](https://github.com/Netflix/RxJava/wiki/images/rx-operators/forIterable.png)

#### Arguments
1. `sources` *(Array)*: An array of values to turn into an observable sequence.
2. `resultSelector` *(`Function`)*: A function to apply to each item in the sources array to turn it into an observable sequence.

#### Returns
*(`Observable`)*: An observable sequence from the concatenated observable sequences or Promises.

#### Example

##### Using Observables

[](http://jsbin.com/bocec/1/embed?js,console)

##### Using Promises

[](http://jsbin.com/febuc/1/embed?js,console)

### Location

File:
- [/src/core/observable/for.js](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/for.js)

Dist:
- [`rx.all.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.all.js)
- [`rx.all.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.all.compat.js)
- [`rx.experimental.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.experimental.js)

Prerequisites:
- If using `rx.expermental.js`
  - [`rx.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.js) | [`rx.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.compat.js) | [`rx.lite.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.js) | [`rx.lite.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.compat.js)

NPM Packages:
- [`rx`](https://www.npmjs.org/package/rx)

NuGet Packages:
- [`RxJS-Complete`](http://www.nuget.org/packages/RxJS-Complete)
- [`RxJS-Experimental`](http://www.nuget.org/packages/RxJS-Experimental)

Unit Tests:
- [`/tests/observable/for.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/tests/observable/for.js)
