# fromArray

`Rx.Observable.fromArray(array, [scheduler])`
<a href="#rxobservablefromarrayarray-scheduler">#</a> [&#x24C8;](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/fromarray.js "View in source")

Converts an array to an observable sequence, using an optional scheduler to enumerate the array.

![from](https://github.com/Netflix/RxJava/wiki/images/rx-operators/from.png)

#### Arguments
1. `array` *(Array)*: An array to convert to an Observable sequence.
2. `[scheduler=Rx.Scheduler.currentThread]` *(`Scheduler`)*: Scheduler to run the enumeration of the input sequence on.

#### Returns
*(`Observable`)*: The observable sequence whose elements are pulled from the given enumerable sequence.

#### Example

[](http://jsbin.com/suqat/1/embed?js,console)

### Location

File:
- [`/src/core/observable/fromarray.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/fromarray.js)

Dist:
- [`rx.all.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.all.js)
- [`rx.all.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.all.compat.js)
- [`rx.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.js)
- [`rx.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.compat.js)
- [`rx.lite.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.js)
- [`rx.lite.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.compat.js)

Prerequisites:
- None

NPM Packages:
- [`rx`](https://www.npmjs.org/package/rx)

NuGet Packages:
- [`RxJS-Complete`](http://www.nuget.org/packages/RxJS-Complete)
- [`RxJS-Main`](http://www.nuget.org/packages/RxJS-Main/)
- [`RxJS-Lite`](http://www.nuget.org/packages/RxJS-Lite/)

Unit Tests:
- [`/tests/observable/fromarray.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/tests/observable/fromarray.js)
