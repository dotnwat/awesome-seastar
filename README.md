# Awesome Seastar [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of resources related to [Seastar](http://seastar.io), an industrial-grade C++ framework for building high-performance servers.

One of the key feature of Seastar is it's event-driven nature which makes it easy for it's user to write non-blocking, asynchronous code. Moreover, Seastar architecture is based on the following points:

- [Shared-nothing Design](http://seastar.io/shared-nothing/): Seastar uses a shared-nothing model that shards all requests onto individual cores. 

- [Futures and Promises](http://seastar.io/futures-promises/): An advanced new model for concurrent applications that offers C++ programmers both high performance and the ability to create comprehensible, testable high-quality code. 

- [High-performance networking](http://seastar.io/networking/) : Seastar offers a choice of network stack, including conventional Linux networking for ease of development, DPDK for fast user-space networking on Linux, and native networking on OSv

- [Messaging passing](http://seastar.io/message-passing/) : A design for sharing information between CPU cores without time-consuming locking.

## Projects

*Systems and projects using Seastar*

* [Ceph](https://github.com/ceph/ceph) - Distributed storage system for object, block, and file
    * The seastar-based storage engine is called [Crimson](https://github.com/ceph/ceph/tree/master/src/crimson)
* [CPV](https://github.com/cpv-project/cpv-framework) - Web framework written in C++ and Seastar
* [Chogori](https://github.com/futurewei-cloud/chogori-platform) - Low-latency distributed OLTP database
* [Parquet4Seastar](https://github.com/michoecho/parquet4seastar) - Parquet file format implementation for use in Seastar projects
* [Pedis](https://github.com/fastio/1store) - Replacement for Redis written in Seastar
* [Redpanda](https://github.com/vectorizedio/redpanda/) - Replacement Apache Kafka designed for modern hardware
* [Scylladb](https://github.com/scylladb/scylla) - Replacement for Apache Cassandra and Amazon DynamoDB
* [Shredder](https://github.com/utah-scs/shredder) - Research prototype for [SoCC '19 paper](https://www.cs.utah.edu/~lifeifei/papers/shredder.pdf) embedding v8 in Seastar
* [SMF](https://github.com/smfrpc/smf) - RPC framework built for microseconds latencies using Seastar

## Learning

*Resources for learning Seastar*

* [Official tutorial](https://github.com/scylladb/seastar/blob/master/doc/tutorial.md) - a comprehensive tutorial from the creators of Seastar
* [Seastar internals](https://makedist.com/projects/seastar-internals/) - is a series of deep dives into various Seastar components
* [Asynchronous Programming with Seastar](http://nadav.harel.org.il/seastar/) - is a series of tutorials covering Seastar compnents
* [Rolling your own MOM](https://dev.to/cppchedy/rolling-out-your-own-mom-or-how-i-did-it-general-introduction-3j20) - a series documenting the MOZA middleware

## Contributors

<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://twitter.com/cppchedy"><img src="https://avatars.githubusercontent.com/u/18627131?s=100&v=3" width="100px;" alt=""/><br/><sub><b>Chedy Najjar</b></sub></a></td>
    <td align="center"><a href="https://twitter.com/dotnwat"><img src="https://avatars.githubusercontent.com/u/242417?s=100&v=3" width="100px;" alt=""/><br/><sub><b>Noah Watkins</b></sub></a></td>
  </tr>
</table>
<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->
