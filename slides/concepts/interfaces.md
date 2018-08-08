## 4 Interfaces

* **_Publisher_** produces events **when somebody subscribes**
* **_Subscriber_** can react to received events:
    * ```onNext()``` : react to normal events
    * ```onError()``` : react to error event
    * ```onComplete()``` : react to completion event
* **_Subscription_** is the resulting object when a Subscriber subscribes to a Publisher
* **_Operator_** is both a Publisher and a Subscriber