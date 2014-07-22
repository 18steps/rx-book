# sum

`Rx.Observable.prototype.sum([keySelector], [thisArg])`
<a href="#rxobservableprototypesumkeyselector-thisarg">#</a> [&#x24C8;](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/sum.js "View in source") 

Computes the sum of a sequence of values that are obtained by invoking an optional transform function on each element of the input sequence, else if not specified computes the sum on each item in the sequence.

#### Arguments
1. `[keySelector]` *(`Scheduler`)*:  A transform function to apply to each element.  The callback is called with the following information:
    1. the value of the element
    2. the index of the element
    3. the Observable object being subscribed

#### Returns
*(`Observable`)*: An observable sequence containing a single element with the sum of the values in the source sequence.
 
#### Example

##### Without a selector

[](http://jsbin.com/cunac/1/embed?js,console)

##### With a selector

[](http://jsbin.com/jelice/1/embed?js,console)

### Location

File:
- [/src/core/observable/sum.js](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/sum.js)

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
- [/tests/observable/sum.js](https://github.com/Reactive-Extensions/RxJS/blob/master/tests/observable/sum.js)