## Laziness

* Publishers are lazy: nothing happens until you subscribe
* Allows to build the processing pipeline before the first value is emitted
* Allows to reuse a Publisher with a second Subscriber
* Beware to respect the contract

| |  |
|-|--|
| <img class="plain icon" src="lib/images/no.png"/> | ```Flux.just(someService.doSomething(input))``` |
| <img class="plain icon" src="lib/images/yes.png"/> | ```Flux.just(input).map(i -> someService.doSomething(i)) ``` |

