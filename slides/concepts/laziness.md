## Laziness

* Publishers are lazy: nothing happens until you subscribe
* Allows to build the processing pipeline before the first value is emitted
* Allows to reuse a Publisher with a second Subscriber
* Beware to respect the contract

| |  |
|-|--|
| <img src="lib/images/no.png" style="border:0;background:black"/> | ```Flux.just(someService.doSomething(input))``` |
| <img src="lib/images/yes.png" style="border:0;background:black"/> | ```Flux.just(input).map(i -> someService.doSomething(i)) ``` |

