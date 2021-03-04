<div align="center">
	<div>
		<img width="500" src="media/awesome-seasatr.png" alt="Awesome Seastar">
	</div>
</div>

## Content

- [Content](#content)
- [Projects](#projects)
	- [Seastar](#seastar)
	- [Scylladb](#scylladb)
	- [Redpanda](#redpanda)
	- [SMF RPC](#smf-rpc)
- [Resource](#resource)
	- [Asynchronous Programming with Seastar](#asynchronous-programming-with-seastar)
	- [Seastar internals](#seastar-internals)
	- [Build a message-oriented middleware using seastar](#build-a-message-oriented-middleware-using-seastar)
- [Unprocessed](#unprocessed)
	- [worth mentioning](#worth-mentioning)
	- [evaluating](#evaluating)



## Projects

### Seastar

[Seastar](http://seastar.io/) is an open source c++ framework designed to help build highly-performant server application. It's used by [ScyllaDb](https://www.scylladb.com/), a high-performance NoSQL Database.

One of the key feature of Seastar is it's event-driven nature which makes it easy for it's user to write non-blocking, asynchronous code. Moreover, Seastar architecture is based on the following points:

- [Shared-nothing Design](http://seastar.io/shared-nothing/): Seastar uses a shared-nothing model that shards all requests onto individual cores. 

- [Futures and Promises](http://seastar.io/futures-promises/): An advanced new model for concurrent applications that offers C++ programmers both high performance and the ability to create comprehensible, testable high-quality code. 

- [High-performance networking](http://seastar.io/networking/) : Seastar offers a choice of network stack, including conventional Linux networking for ease of development, DPDK for fast user-space networking on Linux, and native networking on OSv

- [Messaging passing](http://seastar.io/message-passing/) : A design for sharing information between CPU cores without time-consuming locking.

### Scylladb
[Scylladb](https://github.com/scylladb/scylla) is the real-time big data database that is API-compatible with Apache Cassandra and Amazon DynamoDB. It's built on top of Seastar.

### Redpanda
[Redpanda](https://github.com/vectorizedio/redpanda/) is a streaming platform for mission critical workloads. Kafka® compatible, No Zookeeper®, no JVM, and no code changes required. Use all your favorite open source tooling - 10x faster.

### SMF RPC
[SMF](https://github.com/smfrpc/smf) is a new RPC framework built for microseconds latencies using the seastar framework.

## Resource

### Asynchronous Programming with Seastar
[Asynchronous Programming with Seastar](http://nadav.harel.org.il/seastar/) is a series of tutorials that covers almost all Seastar compnents along with specific ways to debug seastar programs. Another important point about this series is that it's written by two maintainers of Seastar, Nadav Har’El and Avi Kivity.

### Seastar internals
[Seastar internals](https://makedist.com/projects/seastar-internals/) is a series of deep dives into various components found in the Seastar framework such as Seastar smart pointers, temporary buffer, and the gate abstraction.

These articles are written by [Noah Watkins](https://twitter.com/dotnwat), a Principal Architect at Vectorized and the initiator of this list, who spent the last couple of years working on products using Seastar.

### Build a message-oriented middleware using seastar
[Rolling your own MOM or how I did it](https://dev.to/cppchedy/rolling-out-your-own-mom-or-how-i-did-it-general-introduction-3j20) is a series written to document the architecture and messaging model of the message-oriented middleware MOZA writting using c++17 and the framework seastar.

## Unprocessed

### worth mentioning

* ceph, crimson https://github.com/ceph/ceph/tree/master/src/crimson
* k2 https://github.com/futurewei-cloud/chogori-platform
* https://github.com/fastio/1store
* https://github.com/michoecho/parquet4seastar
* cpv-cql-driver: C++ driver for Cassandra/Scylla based on seastar framework
* cpv-framework: A web framework written in c++ based on seastar framework
* https://github.com/scylladb/seastar/blob/master/doc/tutorial.md

### evaluating

https://github.com/duanjp8617/netstar-project
https://github.com/1608502800/My-X-Deeplearning
https://github.com/utah-scs/nanoservices/blob/4e7d636907e6243d844ece6982eb56eef712c967/include/seastarkv.hh
https://github.com/utah-scs/shredder/blob/308647b9eed5ebd5fca3520b4fc02655a7dcd1a2/include/seastarkv.hh
https://github.com/sumeetchhetri/ffead-cpp/blob/5b326e976304278f9b63e67e93b0851af47ae093/lang-server-backends/c%2B%2B/seastar/SeastarFfeadCppIntf.cpp
https://github.com/concord/supervisor/blob/6cd24d59aeb0a306ad9803b040d703d9f4578701/meta/playbooks/roles/seastar/tasks/main.yml
https://github.com/tensorflow/networking/blob/e1c7ae09923293f9cce5eba0a159e75993b793be/third_party/seastar.BUILD
https://github.com/shanshanpt/seastar_example
https://github.com/RanjKuru/turn-server
https://github.com/arrabyte/bigsort
https://github.com/utah-scs/splinter
