## Transforming a sequence

* [Transform existing data on a 1-to-1 basis](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#map-java.util.function.Function-) : ```myFlux.map(mapping function)```
* [Transform existing data running async task for each](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#flatMap-java.util.function.Function-) : ```myFlux.flatMap(mapping to publisher function)```
* [Aggregate a sequence into list](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#collectList--) : ```myFlux.collectList()```
* [Aggregate a sequence into map](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#collectMap-java.util.function.Function-) : ```myFlux.collectMap(keyExtract)```
* [Aggregate a sequence into the size of the sequence](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#count--) : ```myFlux.count()```
* [Aggregate a sequence by applying a function](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#reduce-A-java.util.function.BiFunction-) : ```myFlux.reduce(reduction)```
* [Test value of events](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#any-java.util.function.Predicate-) : ```myFlux.any(predicate)``` - or - ```myFlux.all(predicate)```
* [Test presence of event(s)](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#hasElements--) : ```myFlux.hasElements()``` - or - ```myFlux.hasElement(value)```