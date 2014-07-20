# range

`Rx.Observable.range(start, count, [scheduler])`
<a href="#rxobservablerangestart-count-scheduler">#</a> [&#x24C8;](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/range.js "View in source") 

Generates an observable sequence of integral numbers within a specified range, using the specified scheduler to send out observer messages.

### Arguments
1. `start` *(`Number`)*: The value of the first integer in the sequence.
2. `count` *(`Number`)*: The number of sequential integers to generate.
3. `[scheduler=Rx.Scheduler.currentThread]` *(`Scheduler`)*: Scheduler to run the generator loop on. If not specified, defaults to Scheduler.currentThread.

#### Returns
*(`Observable`)*: An observable sequence that contains a range of sequential integral numbers. 

#### Example

[](http://jsbin.com/bapay/1/embed?js,console)

### Location

File:
- [/src/core/observable/range.js](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/range.js)

Dist:
- [`rx.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.js)
- [`rx.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.compat.js)
- [`rx.lite.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.js)
- [`rx.lite.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.compat.js)

Prerequisites:
- [`rx.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.js) | [`rx.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.compat.js) | [`rx.lite.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.js) | [`rx.lite.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.compat.js)

NPM Packages:
- [`rx`](https://www.npmjs.org/package/rx)

NuGet Packages:
- [`RxJS-Main`](http://www.nuget.org/packages/RxJS-Main/)
- [`RxJS-Lite`](http://www.nuget.org/packages/RxJS-Lite/)

Unit Tests:
- [/tests/observable/range.js](https://github.com/Reactive-Extensions/RxJS/blob/master/tests/observable/range.js)