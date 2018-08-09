## Handling errors

* [create an error](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#error-java.lang.Throwable-) : ```Flux.error(throwable)```
* [fall back on default value](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#onErrorReturn-T-) : ```myFlux.onErrorReturn(defaultVal)```
* [fall back on another publisher](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#onErrorResume-java.lang.Class-java.util.function.Function-) : ```myFlux.onErrorResume(publisher)```
* [transform and rethrowing](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Flux.html#onErrorMap-java.util.function.Function-) : ```myFlux.onErrorMap(mapper)```
* [retrying](https://raw.githubusercontent.com/reactor/reactor-core/master/src/docs/marble/retry.png) : ```myFlux.retry(number)```