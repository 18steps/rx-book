# generateWithAbsoluteTime

`Rx.Observable.generateWithAbsoluteTime(initialState, condition, iterate, resultSelector, timeSelector, [scheduler])`
<a href="#rxobservablegeneratewithabsolutetimeinitialstate-condition-iterate-resultselector-timeselector-schedule">#</a> [&#x24C8;](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/generatewithabsolutetime.js "View in source") 

Generates an observable sequence by iterating a state from an initial state until the condition fails.

#### Arguments
1. `initialState` *(`Any`)*: Initial state.
2. `condition` *(`Function`)*: Condition to terminate generation (upon returning false).
3. `iterate` *(`Function`)*: Iteration step function.
4. `resultSelector` *(`Function`)*: Selector function for results produced in the sequence.
5. `timeSelector` *(`Function`)*: Time selector function to control the speed of values being produced each iteration, returning Date values.
6. `[scheduler=Rx.Scheduler.timeout]` *(`Scheduler`)*: Scheduler on which to run the generator loop. If not provided, defaults to Scheduler.timeout.

#### Returns
*(`Observable`)*: The generated sequence.

#### Example

[](http://jsbin.com/pugoy/1/embed?js,console)

### Location

File:
- [/src/core/observable/generatewithabsolutetime.js](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/generatewithabsolutetime.js)

Dist:
- [rx.time.js](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.time.js)

Prerequisites:
- [`rx`](https://www.npmjs.org/package/rx).time.js
- [`rx.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.js) | [`rx.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.compat.js)

NPM Packages:
- [`rx`](https://www.npmjs.org/package/rx)

NuGet Packages:
- [`rx`](https://www.npmjs.org/package/rx)JS-Time

Unit Tests:
- [/tests/observable/generatewithabsolutetime.js](https://github.com/Reactive-Extensions/RxJS/blob/master/tests/observable/generatewithabsolutetime.js)