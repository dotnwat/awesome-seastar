# Awesome Seastar [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of resources related to [Seastar](http://seastar.io), an industrial-grade C++ framework for building high-performance servers.

## News

* What's new in Seastar (infrequently released)
  * [Issue 1 - Apr '23](https://makedist.com/posts/2023/04/30/whats-new-in-seastar-issue-1/)
  * [Issue 2 - Dec '23](https://makedist.com/posts/2023/12/01/whats-new-in-seastar-issue-2/)

## Projects

*Systems and projects using Seastar*

* [Ceph](https://github.com/ceph/ceph) - Distributed storage system for object, block, and file
    * The seastar-based storage engine is called [Crimson](https://github.com/ceph/ceph/tree/master/src/crimson)
* [CPV](https://github.com/cpv-project/cpv-framework) - Web framework written in C++ and Seastar
* [Chogori](https://github.com/futurewei-cloud/chogori-platform) - Low-latency distributed OLTP database
* [Lightbits](https://www.youtube.com/watch?v=kWfhVaeY2BE) - Lightbits LightOS
* [ministun](https://github.com/nguyenminh-phuc/ministun) - RFC 8489 STUN server
* [Parquet4Seastar](https://github.com/michoecho/parquet4seastar) - Parquet file format implementation for use in Seastar projects
* [Pedis/1store](https://github.com/fastio/1store) - Replacement for Redis written in Seastar
* [RageDB](https://github.com/ragedb/ragedb) - In Memory Property Graph Server using the Shared Nothing design from Seastar
* [Redpanda](https://github.com/redpanda-data/redpanda/) - Replacement for Apache Kafka designed for modern hardware
* [Scylladb](https://github.com/scylladb/scylla) - Replacement for Apache Cassandra and Amazon DynamoDB
* [Shredder](https://github.com/utah-scs/shredder) - Research prototype for [SoCC '19 paper](https://www.cs.utah.edu/~lifeifei/papers/shredder.pdf) embedding v8 in Seastar
* [SMF](https://github.com/smfrpc/smf) - RPC framework built for microseconds latencies using Seastar
* [SpiderDB](https://github.com/chungphb/spiderdb) - An on-disk key-value database based on a b-link tree

## Learning

*Resources for learning Seastar*

* [Official tutorial](https://github.com/scylladb/seastar/blob/master/doc/tutorial.md) - a comprehensive tutorial from the creators of Seastar
* [Seastar internals](https://makedist.com/projects/seastar-internals/) - is a series of deep dives into various Seastar components
* [Asynchronous Programming with Seastar](http://nadav.harel.org.il/seastar/) - is a series of tutorials covering Seastar compnents
* [Rolling your own MOM](https://dev.to/cppchedy/rolling-out-your-own-mom-or-how-i-did-it-general-introduction-3j20) - a series documenting the MOZA middleware
* [Seabrute](https://github.com/VictorDenisov/seabrute) - a selfstudy project for learning seastar by implementing distributed password bruteforce

## Archived

These appear to no longer exist :(

* [seastar-kafka-client](https://github.com/haaawk/seastar-kafka-client) - A seastar-based kafka client

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
