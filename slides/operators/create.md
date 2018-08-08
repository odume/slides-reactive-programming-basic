## Creating sequence

* [Emit one or multiple events that I already have](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#just-T...-) : ```Flux.just(T...)```
* [Lazily emit one or multiple events returned by method call](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#defer-java.util.function.Supplier-) : ```Flux.fromSupplier(Supplier<T>)``` - or - ```Flux.defer(Supplier<Publisher<T>>)``` 
* [Emit events that iterate over array](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#fromArray-T:A-) : ```Flux.fromArray(T[])```
* [Emit events that iterate over Iterable](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#fromIterable-java.lang.Iterable-) : ```Flux.fromIterable(Iterable<T>)```
* [Emit events from Stream](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#fromStream-java.util.stream.Stream-) : ```Flux.fromStream(Stream<T>)```
* [Emit events that iterate range](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#range-int-int-) : ```Flux.range(start, count)```
* [Sequence that complete](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#empty--) : ```Flux.empty()```
* [Emit an error immediately](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#error-java.lang.Throwable-) : ```Flux.error(Throwable)```
* [Sequence that does nothing](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#never--) : ```Flux.never()```