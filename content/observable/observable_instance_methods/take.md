## [`Rx.Observable.prototype.take(count, [scheduler])`](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/take.js)

{% if book.isPdf %}

![take](http://reactivex.io/documentation/operators/images/take.png)

{% else %}

<rx-marbles key="take"></rx-marbles>

{% endif %}

Returns a specified number of contiguous elements from the start of an observable sequence, using the specified scheduler for the edge case of `take(0)`.
  
#### Arguments
1. `count` *(`Number`)*: The number of elements to return.
2. `[schduler]` *(`Scheduler`)*: Scheduler used to produce an onCompleted message in case `count` is set to 0.

#### Returns
*(`Observable`)*: An observable sequence that contains the elements that occur after the specified index in the input sequence.   

#### Example

[](http://jsbin.com/ticoya/1/embed?js,console)

{% if book.isPdf %}



{% else %}

### Location

File:
- [`/src/core/observable/take.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/take.js)

Dist:
- [`rx.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.js)
- [`rx.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.compat.js)
- [`rx.lite.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.js)
- [`rx.lite.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.compat.js)

Prerequisites:
- None

NPM Packages:
- [`rx`](https://www.npmjs.org/package/rx)

NuGet Packages:
- [`RxJS-Main`](http://www.nuget.org/packages/RxJS-Main/)
- [`RxJS-Lite`](http://www.nuget.org/packages/RxJS-Lite/)

Unit Tests:
- [`/tests/observable/take.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/tests/observable/take.js)

{% endif %}