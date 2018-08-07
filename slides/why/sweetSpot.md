## Sync and Async in Java

A method or function is synchronous or asynchronous depending on the returned Type

|         | Single    | Multiple     |
|---------|:---------:|:------------:|
|**Sync** | T         | Iterable&lt;T&gt; <br> Stream&lt;T&gt;|
|**Async**| Future&lt;T&gt; <br> CompletableFuture&lt;T&gt;| Publisher&lt;T&gt;|
