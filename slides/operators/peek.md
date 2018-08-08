## Peeking into sequences

* [execute on emissions](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#doOnNext-java.util.function.Consumer-) : ```myFlux.doOnNext(exec)```
* [execute on completion](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#doOnComplete-java.lang.Runnable-) : ```myFlux.doOnComplete(exec)```
* [execute on success (Mono)](https://raw.githubusercontent.com/reactor/reactor-core/master/src/docs/marble/doonsuccess.png): ```myMono.doOnSuccess(exec)```
* [execute on error termination](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#doOnError-java.util.function.Consumer-) : ```myFlux.doOnError(exec)```
* [execute on subscription](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#doOnSubscribe-java.util.function.Consumer-) : ```myFlux.doOnSubscribe(exec)```