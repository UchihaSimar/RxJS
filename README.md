This is my take and notes on different features of RxJS.

Usually we will find RxJS being used in an Angular, Node, React etc kind of project,which already have a transpiler built in. So in that case, you would be able to use Import, Export etc ES6 features. 

Here, all I am using is an index file, with RxJS being inserted using a cdn. It works similar to lodash or jquery. So just like Lodash provides an '_' or Jquery provides '$' to access, similarly Rxjs provides 'rxjs'. We can destructure it to access the methods and features.

1. **Observable**: represents the idea of an invokable collection of future values or events.
2. **Observer**: is a collection of callbacks that knows how to listen to values delivered by the Observable.
3. **Subscription**: represents the execution of an Observable, is primarily useful for cancelling the execution.
4. **Operators**: are pure functions that enable a functional programming style of dealing with collections with operations like map, filter,  concat, reduce, etc.
5. **Subject**: is equivalent to an EventEmitter, and the only way of multicasting a value or event to multiple Observers.
6. **Schedulers**: are centralized dispatchers to control concurrency, allowing us to coordinate when computation happens on e.g. setTimeout or requestAnimationFrame or others.
