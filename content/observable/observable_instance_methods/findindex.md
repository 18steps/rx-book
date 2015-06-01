# findIndex

<rx-marbles key="findIndex"></rx-marbles>

`Rx.Observable.prototype.findIndex(predicate, [thisArg])`
<a href="#rxobservableprototypefindindexpredicate-thisarg">#</a> [&#x24C8;](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.aggregates.js#L712-L714 "View in source") 

Searches for an element that matches the conditions defined by the specified predicate, and returns the first occurrence within the entire Observable sequence.
 
#### Arguments
1. `predicate` *(`Function`)*: A function to test each source element for a condition;  The callback is called with the following information:
    1. the value of the element
    2. the index of the element
    3. the Observable object being subscribed
2. `[thisArg]` *(`Any`)*: Object to use as `this` when executing the predicate.

#### Returns
*(`Observable`)*: An Observable sequence with the first element that matches the conditions defined by the specified predicate, if found; otherwise, undefined.

#### Example

[](http://jsbin.com/nodec/1/embed?js,console)

#### Location

- [`rx`](https://www.npmjs.org/package/rx).aggregates.js