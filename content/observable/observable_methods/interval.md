## [`Rx.Observable.interval(period, [scheduler])`](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/interval.js)

{% if book.isPdf %}

![interval](http://reactivex.io/documentation/operators/images/interval.png)

{% else %}



{% endif %}

Returns an observable sequence that produces a value after each period.

#### Arguments
1. `period` *(`Number`)*: Period for producing the values in the resulting sequence (specified as an integer denoting milliseconds).
2. `[scheduler]` *(Scheduler=Rx.Scheduler.timeout)*: Scheduler to run the timer on. If not specified, Rx.Scheduler.timeout is used.

#### Returns
*(`Observable`)*: An observable sequence that produces a value after each period.

#### Example

[](http://jsbin.com/lozay/1/embed?js,console)

{% if book.isPdf %}



{% else %}

### Location

File:
- [/src/core/observable/interval.js](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/interval.js)

Dist:
- [`rx.lite.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.js)
- [`rx.lite.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.compat.js)
- [rx.time.js](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.time.js)

Prerequisites:
- if rx.time.js
    - [`rx.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.js) | [`rx.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.compat.js)
- [`rx`](https://www.npmjs.org/package/rx).lite.js | rx.lite.compat.js

NPM Packages:
- [`rx`](https://www.npmjs.org/package/rx)

NuGet Packages:
- [`rx`](https://www.npmjs.org/package/rx)JS-Time
- [`RxJS-Lite`](http://www.nuget.org/packages/RxJS-Lite/)

Unit Tests:
- [/tests/observable/interval.js](https://github.com/Reactive-Extensions/RxJS/blob/master/tests/observable/interval.js)

{% endif %}
