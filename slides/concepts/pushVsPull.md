## Pull and push comparison

| Pull             | Push              |
|:-----------------|:------------------|
| Iterable         | Publisher         |
| T next()         | onNext(T)         |
| throws Exception | onError(Throwable)|
| returns          | onCompleted()     |
