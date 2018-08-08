## Combining sequences

* [Combine publishers in sequential order](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#concatWith-org.reactivestreams.Publisher-) : ```myFlux.concatWith(otherPub)```
* [Combine publishers in emission order](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#mergeWith-org.reactivestreams.Publisher-) : ```myFlux.mergeWith(otherPub)```
* [Combine publishers by pairing values](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#zipWith-org.reactivestreams.Publisher-java.util.function.BiFunction-) : ```myFlux.zipWith(otherPub, combinator)```