OkDiskLruCacheKt
================
[![GitHub license](https://img.shields.io/github/license/rockyoung/OkDiskLruCache)](https://github.com/rockyoung/OkDiskLruCache/blob/master/LICENSE)
[![Build Status](https://travis-ci.org/rockyoung/OkDiskLruCache.svg?branch=master)](https://travis-ci.org/rockyoung/OkDiskLruCache)
[![Download](https://api.bintray.com/packages/imrock/x-libs/okdisklrucache/images/download.svg) ](https://bintray.com/imrock/x-libs/okdisklrucache/_latestVersion)

A fork of [Jake Wharton's DiskLruCache](https://github.com/JakeWharton/DiskLruCache) translated to
Kotlin and using [Okio](https://github.com/square/okio) like what
[OkHttp](https://github.com/square/okhttp) has done for it's `internal` DiskLruCache
implementation, unfortunately as the mentioned word `internal`, you can not use it directly. so here
we are, also support file get in `Snapshot`.

##Download
Maven:
```xml
<dependency>
  <groupId>com.imrock.xlib</groupId>
  <artifactId>okdisklrucache</artifactId>
  <version>1.0.0</version>
  <type>pom</type>
</dependency>
```
Or Gradle:
```groovy
dependencies {
  implementation 'com.imrock.xlib:okdisklrucache:1.0.0'
}
```
