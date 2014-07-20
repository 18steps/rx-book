# all

`Rx.Observable.prototype.all(predicate, [thisArg])`
<a href="#rxobservableprototypeallpredicate-thisarg">#</a> [&#x24C8;](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/all.js "View in source") 

Determines whether all elements of an observable sequence satisfy a condition.  There is an alias for this method called `every`.

#### Arguments
1. `predicate` *(`Function`)*: A function to test each element for a condition.
2. `[thisArg]` *(`Function`)*: Object to use as this when executing callback.

#### Returns
*(`Observable`)*: An observable sequence containing a single element determining whether all elements in the source sequence pass the test in the specified predicate.

#### Example

[](http://jsbin.com/vabol/1/embed?js,console)

### Location

File:
- [/src/core/observable/all.js](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/all.js)

Dist:
- [rx.aggregates.js](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.aggregates.js)

Prerequisites:
- [`rx`](https://www.npmjs.org/package/rx).aggregates.js
- [`rx.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.js) | [`rx.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.compat.js) | [`rx.lite.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.js) | [`rx.lite.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.compat.js)

NPM Packages:
- [`rx`](https://www.npmjs.org/package/rx)

NuGet Packages:
- [`RxJS-Aggregates`](http://www.nuget.org/packages/RxJS-Aggregates/)

Unit Tests:
- [/tests/observable/all.js](https://github.com/Reactive-Extensions/RxJS/blob/master/tests/observable/all.js)