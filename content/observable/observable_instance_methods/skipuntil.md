## [`Rx.Observable.prototype.skipUntil(other)`](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/skipuntil.js)

{% if book.isPdf %}

![skipUntil](http://reactivex.io/documentation/operators/images/skipUntil.png)

{% else %}

<rx-marbles key="skipUntil"></rx-marbles>

{% endif %}

Returns the values from the source observable sequence only after the other observable sequence produces a value.

#### Arguments
1. `other` *(`Observable` | `Promise`)*: The observable sequence or Promise that triggers propagation of elements of the source sequence.

#### Returns
*(`Observable`)*: An observable sequence containing the elements of the source sequence starting from the point the other sequence triggered propagation.    

#### Example

[](http://jsbin.com/senon/1/embed?js,console)

{% if book.isPdf %}



{% else %}

### Location

File:
- [`/src/core/observable/skipuntil.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/skipuntil.js)

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
- [`/tests/observable/skipuntil.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/tests/observable/skipuntil.js)

{% endif %}