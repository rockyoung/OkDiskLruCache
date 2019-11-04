OkDiskLruCacheKt
================

A fork of [Jake Wharton's DiskLruCache](https://github.com/JakeWharton/DiskLruCache) translated to
Kotlin and using [Okio](https://github.com/square/okio) like what
[OkHttp](https://github.com/square/okhttp) has done for it's `internal` DiskLruCache
implementation, unfortunately as the mentioned word `internal`, you can not use it directly. so here
we are, also support file get in `Snapshot`.
