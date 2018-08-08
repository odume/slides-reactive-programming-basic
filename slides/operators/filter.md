## Filtering sequence

* [filter a sequence](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#filter-java.util.function.Predicate-) : ```myFlux.filter(predicate)```
* [ignore duplicate](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#distinct--) : ```myFlux.distinct()```
* [take N elements](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#take-long-) : ```myFlux.take(number)```
* [take 1 element or fail](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#single--) : ```myFlux.single()```