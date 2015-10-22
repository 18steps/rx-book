## [`Rx.Observable.prototype.mergeAll()`,
`Rx.Observable.prototype.mergeObservable()`
](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/mergeall.js)

{% if book.isPdf %}

![mergeAll](http://reactivex.io/documentation/operators/images/mergeAll.png)

{% else %}



{% endif %}

Merges an observable sequence of observable sequences into an observable sequence.

#### Returns
*(`Observable`)*: The observable sequence that merges the elements of the inner sequences. 
 
#### Example

[](http://jsbin.com/zatet/1/embed?js,console)

{% if book.isPdf %}



{% else %}

### Location

File:
- [`/src/core/observable/mergeobservable.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/mergeobservable.js)

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
- [`/tests/observable/mergeobservable.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/tests/observable/mergeobservable.js)

{% endif %}