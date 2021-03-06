# Network
* [Lwan](https://github.com/lpereira/lwan)<br>
Lwan is a high-performance & scalable web server.
It's suitable to be used from embedded devices to robust servers. Both static and dynamic content can be served, as it can also be used as a library. Dynamic content can be generated by code written in either C or Lua.
* [NNG](https://github.com/nanomsg/nng)<br>
NNG, like its predecessors nanomsg (and to some extent ZeroMQ), is a lightweight, broker-less library, offering a simple API to solve common recurring messaging problems, such as publish/subscribe, RPC-style request/reply, or service discovery. The API frees the programmer from worrying about details like connection management, retries, and other common considerations, so that they can focus on the application instead of the plumbing.
NNG is implemented in C, requiring only C99 and CMake to build. It can be built as a shared or a static library, and is readily embeddable. It is also designed to be easy to port to new platforms if your platform is not already supported.

# Queue
* [liblfds](https://www.liblfds.org/)<br>
Welcome to liblfds, a portable, license-free, lock-free data structure library written in C.
Lock-free data structures are process, thread and interrupt safe (i.e. the same data structure instance can be safely used concurrently and simultaneously across cores, processes, threads and both inside and outside of interrupt handlers), never sleep (and so are safe for kernel use when sleeping is not permitted), operate without context switches, cannot fail (no need to handle error cases, as there are none), perform and scale literally orders of magnitude better than locking data structures, and liblfds itself (as of release 7.0.0) is implemented such that it performs no allocations (and so works with NUMA, stack, heap and shared memory) and compiles not just on a freestanding C89 implementation, but on a bare C89 implementation.
