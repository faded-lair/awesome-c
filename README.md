# Awesome C

A curated list of C good stuff. This list contains only [open source](https://opensource.org/osd) code (as defined by the linked Open Source Definition), and sellers who aren't evil for physical resources.

This is released under a Creative Commons-Attribution-ShareAlike license, version 4 (SPDX code ``CC-BY-SA-4.0``). You can find its text in the LICENSE file.

**An important note:** This project does not index anything C++-related; only pure C stuff is considered.

**Note for contributors:** If you want to make a pull request, please read CONTRIBUTING.md first.

## Contents

- [AI](#ai)
- [Benchmarking](#benchmarking)
- [Build Systems](#build-systems)
- [Compilers](#compilers)
- [Compression](#compression)
- [Concurrency and Parallelism](#concurrency-and-parallelism)
- [Crypto](#crypto)
- [Database](#database)
- [Data Structures](#data-structures)
- [Debugging](#debugging)
- [Documentation Generation](#documentation-generation)
- [Frameworks](#frameworks)
- [Game Programming](#game-programming)
- [Graphics](#graphics)
- [Graphical User Interface](#graphical-user-interface)
- [Hashing](#hashing)
- [Learning, Reference and Tutorials](#learning-reference-and-tutorials)
- [Reference resources online](#reference-resources-online)
- [Beginner resources online](#beginner-resources-online)
- [Intermediate resources online](#intermediate-resources-online)
- [Advanced resources online](#advanced-resources-online)
- [Reference books](#reference-books)
- [Beginner books](#beginner-books)
- [Intermediate books](#intermediate-books)
- [Advanced books](#advanced-books)
- [Lexing and Parsing](#lexing-and-parsing)
- [Memory Management](#memory-management)
- [Multimedia](#multimedia)
- [Networking and Internet](#networking-and-internet)
- [Numerical](#numerical)
- [Profiling](#profiling)
- [Regex](#regex)
- [Serialization](#serialization)
- [Source Code Collections](#source-code-collections)
- [Standard Libraries](#standard-libraries)
- [String Manipulation](#string-manipulation)
- [Structured File Processing](#structured-file-processing)
  - [CSV](#csv)
  - [JSON](#json)
  - [INI](#ini)
  - [Others](#others)
  - [XML](#xml)
  - [YAML](#yaml)
- [Testing](#testing)
- [Tools](#tools)
- [Utilities](#utilities)
- [Web Frameworks](#web-frameworks)
- [Windows Environments](#windows-environments)

## AI

Computer vision, neural nets, machine learning, and other similar things. Basically, if your university calls it AI, it lives here.

- [ccv](http://libccv.org/) - C-based/Cached/Core Computer Vision library; modern computer vision. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [Cranium](https://100.github.io/Cranium/) - Portable, header-only ANN library in C99. [MIT](https://spdx.org/licenses/MIT.html)
- [FANN](https://github.com/libfann/fann) - Fast Artifical Neural Network library; an implementation of neural networks. [GPL-2.0-only](https://spdx.org/licenses/GPL-2.0-only.html)
- [Genann](https://codeplea.com/genann) - Simple ANN in C89, without additional dependencies. [Zlib](https://spdx.org/licenses/Zlib.html)
- [KANN](https://github.com/attractivechaos/kann) - Two-file ANN library. [MIT](https://spdx.org/licenses/MIT.html)
- [LibDEEP](https://github.com/jppbsi/LibDEEP) - Deep learning library. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [m2cgen](https://github.com/BayesWitnesses/m2cgen) - A CLI tool to transpile trained classic ML models into a native C code with zero dependencies. [MIT](https://spdx.org/licenses/MIT.html)
- [sod](https://sod.pixlab.io/) - An Embedded Computer Vision & Machine Learning Library. [GPL-3.0-only](https://spdx.org/licenses/GPL-3.0-only.html)

## Benchmarking

Comparing the performance of various subsystems across different chip/system architectures.

- [b63](https://github.com/okuvshynov/b63) - Light-weight micro-benchmarking tool for C. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)

## Build Systems

Tools that automate the building and testing of projects in C.

- [Autotools](https://www.gnu.org/software/automake/manual/html_node/GNU-Build-System.html) - Also known as the GNU build system (automake, autoconf, libtool…) is one of the most widely used build systems (configure && make). [GPL-1.0-or-later](https://spdx.org/licenses/GPL-1.0.html)
- [Autotools project skeleton](https://github.com/msune/autotools-skeleton) - A simple autotools skeleton (template) to quickly bootstrap new projects. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [CMake](https://cmake.org/) - Cross-platform family of tools designed to build, package and test software. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [GNU Make](https://www.gnu.org/software/make/) - Tool which controls the generation of executables and other non-source files of a program. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [Meson](https://mesonbuild.com/) - Extremely fast, user-friendly build system. Based on Ninja. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [Premake](https://premake.github.io/) - Command-line utility which reads a scripted definition of a software project and uses it to generate project files for Visual Studio and GNU Make. Other targets are also being worked on. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [SCons](https://www.scons.org/) - Software construction tool using Python. [MIT](https://spdx.org/licenses/MIT.html)
- [xmake](https://xmake.io/) - Cross-platform build utility. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [zproject](https://github.com/zeromq/zproject) - Project generator and build system support tool. [MPL-2.0](https://spdx.org/licenses/MPL-2.0.html)

## Compilers

Compilers, as well as compiler- and compilation-related tooling.

- [ccache](https://ccache.dev/) - Compiler cache designed to speed up recompilation. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [Clang](https://clang.llvm.org/) - Clang is a modern, open-source compiler front end for the C language family. [Apache License v2.0 with LLVM Exceptions](https://llvm.org/LICENSE.txt)
- [GCC](https://gcc.gnu.org/) - GCC (GNU Compiler Collection) is a free, open-source suite of compilers created by the GNU Project that supports many programming languages including C. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [cproc](https://git.sr.ht/~mcf/cproc) - A C11 compiler using QBE as a backend. [ISC](https://spdx.org/licenses/ISC.html)
- [distcc](https://github.com/distcc/distcc) - Program that allows builds to be distributed among several machines. [GPL-2.0-or-later](https://spdx.org/licenses/GPL-2.0-or-later.html)
- [Firm](https://pp.ipd.kit.edu/firm/) - Library that provides a graph-based intermediate representation, optimizations and assembly code generation suitable for use in compilers. Comes with an example C front-end under the same license. [LGPL-2.1-only](https://spdx.org/licenses/LGPL-2.1-only.html)
- [OrangeC](https://github.com/LADSoft/OrangeC) - OrangeC Compiler And Tool Chain. [Various licenses](https://github.com/LADSoft/OrangeC/blob/master/LICENSE.TXT)

## Compression

- [blosc](http://blosc.org/pages/blosc-in-depth) - Extremely fast, multi-threaded, meta-compressor library. Various licenses, all open source.
- [Brotli](https://github.com/google/brotli) - General-purpose lossless compression algorithm library. Has speeds comparable to DEFLATE, but much higher compression ratios. [MIT](https://spdx.org/licenses/MIT.html).
- [clzip](http://lzip.nongnu.org/clzip.html) - C version of the high-quality data compressor [Lzip](http://lzip.nongnu.org/lzip.html) (LZMA implementation). [GPL-2.0-or-later](https://spdx.org/licenses/GPL-2.0-or-later.html)
- [CRoaring](https://github.com/RoaringBitmap/CRoaring) - C implementation of [Roaring bitmaps](http://roaringbitmap.org/). [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [FiniteStateEntropy](https://github.com/Cyan4973/FiniteStateEntropy) - Two highly efficient compression codecs optimized for modern CPUs. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [heatshrink](https://github.com/atomicobject/heatshrink) - Data compression/decompression library for embedded and real-time systems. [ISC](https://spdx.org/licenses/ISC.html)
- [fast_zlib](https://github.com/gildor2/fast_zlib) - Improved zlib, which runs 2 to 10 times faster. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [fastLZ](https://github.com/ariya/fastlz) - Lightning-fast lossless compression library (LZ77 type). Embbedable on small target like ARM Cortex-M families. Source code directly embbedable on your project ( a pair of h/c files), no dynamic memory allocation. [MIT](https://spdx.org/licenses/MIT.html)
- [huffandpuff](https://github.com/adamierymenko/huffandpuff) - Minimal Huffman encoder and decoder. Public domain.
- [libzip](https://github.com/nih-at/libzip) - C library for reading, creating and modifying zip archives. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [libbzip2](http://www.bzip.org/) - Patent-free, high-quality data compression library. [BSD-4-Clause](https://spdx.org/licenses/BSD-4-Clause.html)
- [Lizard](https://github.com/inikep/lizard) - Formerly LZ5; an efficient compressor with fast decompression. Achieves compression ratios comparable with zip and zlib at decompression speeds of 1000MB/s and faster. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [lz4](http://lz4.github.io/lz4/) - Library for an extremely fast compression algorithm. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [lzo](http://www.oberhumer.com/opensource/lzo/) - Fast data compression library. [GPL-2.0-or-later](https://spdx.org/licenses/GPL-2.0-or-later.html)
- [pixz](https://github.com/vasi/pixz) - Parallel, indexed xz compressor. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [shoco](http://ed-von-schleck.github.io/shoco) - Compressor for small text strings. [MIT](https://spdx.org/licenses/MIT.html)
- [SIMDComp](https://github.com/lemire/simdcomp) - Simple library for compressing lists of integers using binary packing. Makes use of SIMD instructions on x86. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [smaz](https://github.com/antirez/smaz) - Efficient string compression library. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [squash](https://github.com/quixdb/squash) - Compression abstraction library, complete with some utilities. [MIT](https://spdx.org/licenses/MIT.html)
- [TurboPFor](https://github.com/powturbo/TurboPFor) - Fastest integer compression. [GPL-2.0-or-later](https://spdx.org/licenses/GPL-2.0-or-later.html)
- [TurboRLE](https://github.com/powturbo/TurboRLE) - Most efficient run-length encoding. [GPL-2.0-or-later](https://spdx.org/licenses/GPL-2.0-or-later.html)
- [zip](https://github.com/kuba--/zip) - Really really small zip archive processing library. [Unlicense](https://spdx.org/licenses/Unlicense.html)
- [Zlib](http://zlib.net) - Massively spiffy yet delicately unobtrusive compression library. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [libarchive](https://github.com/libarchive/libarchive) - libarchive is a portable, efficient C library that can read and write streaming archives in a variety of formats. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [zlib-ng](https://github.com/Dead2/zlib-ng) - Zlib replacement with optimizations for 'next-generation' systems. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [Zstandard](http://facebook.github.io/zstd/) - Fast, lossless compression algorithm, targeting real-time compression scenarios at zlib-level or better compression ratios. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)

## Concurrency and Parallelism

- [cchan](http://repo.hu/projects/cchan/) - Small library for channel constructs for inter-thread communication. Public domain.
- [checkedthreads](https://github.com/yosefk/checkedthreads) - A simple library for parallelism, with built-in checking for race conditions. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [ck](http://concurrencykit.org) - Concurrency primitives, safe memory reclamation mechanisms and non-blocking data structures. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [dyco-coroutine](https://github.com/piaodazhu/dyco-coroutine) - Coroutine framework with Channel, SSL hook, waitgroup, etc. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [FCFS RWLock](http://www.shlomifish.org/rwlock/) - First-come first-served Readers/Writers lock for POSIX threads. [CC0-1.0](https://spdx.org/licenses/CC0-1.0.html)
- [Libaco](https://github.com/hnes/libaco) - A blazing fast and lightweight C asymmetric coroutine library. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [libconcurrent](https://github.com/sharow/libconcurrent) - Concurrent programming library, using coroutines, for C11. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [libcsp](https://github.com/shiyanhui/libcsp) - High performance concurrency C library influenced by the CSP model. [MIT](https://spdx.org/licenses/MIT.html)
- [libdill](http://libdill.org/) - Library which makes structured concurrent programming easy. [MIT](https://spdx.org/licenses/MIT.html)
- [libhl](https://github.com/xant/libhl) - Library implementing a thread-safe API to manage a range of data structures. Also provides some supporting functions and structures for concurrent and lockfree programming. [LGPL-3.0-only](https://spdx.org/licenses/LGPL-3.0-only.html)
- [liburcu](http://liburcu.org/) - Data synchronization library, which scales linearly with the number of cores. [LGPL-2.1-or-later](https://spdx.org/licenses/LGPL-2.1-or-later.html)
- [mill](https://libmill.org/) - Go-style concurrency. [MIT](https://spdx.org/licenses/MIT.html)
- [oclkit](https://github.com/matze/oclkit) - Two-file OpenCL wrapper. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [OCL-MLA](http://tuxfan.github.io/ocl-mla/) - OpenCL Mid-Level Abstractions. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [OpenMP](https://www.openmp.org/) - Set of pragmas designed to allow for easy parallelization of code. Standard (licensing not applicable).
- [Open MPI](https://github.com/open-mpi/ompi) - Message passing interface implementation. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [pal](https://github.com/parallella/pal) - Optimized library for maths, parallel processing and data movement. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [pth](https://gnu.org/software/pth/) - Portable implementation for non-preemptive priority-based scheduling for multiple threads of execution. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [pthreads](https://en.wikipedia.org/wiki/POSIX_Threads) - POSIX thread library. Standard (no license applicable).
- [TinyCThread](https://tinycthread.github.io/) - Portable, small implementation of the C11 threads API. [Zlib](https://spdx.org/licenses/Zlib.html)

## Crypto

Mostly library implementations of well-known cryptographic algorithms or protocols.

- [GNU SASL](https://gnu.org/software/gsasl/) - Implementation of the Simple Authentication and Security Layer and a few common SASL mechanism. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [GnuTLS](http://www.gnutls.org/) - Secure communication library, implementing SSL, TLS and DTLS. [LGPL-2.1-or-later](https://spdx.org/licenses/LGPL-2.1-or-later.html)
- [libgcrypt](https://gnupg.org/related_software/libgcrypt) - General-purpose cryptography library, with a range of available ciphers. [LGPL-2.1-or-later](https://spdx.org/licenses/LGPL-2.1-or-later.html)
- [OpenSSL](https://www.openssl.org/) - TLS/SSL and crypto library. [License](https://www.openssl.org/source/license.html).
- [LibreSSL](https://github.com/libressl-portable/) - Fork of OpenSSL 1.0.1g. [License](https://github.com/libressl/portable/blob/master/COPYING).
- [wolfSSL](https://www.wolfssl.com/) - Implementation of TLS/SSL for embedded devices. [License](https://www.wolfssl.com/license/).
- [BearSSL](https://bearssl.org/) - Implementation of SSL/TLS for embedded systems, currently beta-quality software. [License](https://bearssl.org/#legal-details).
- [Mbed TLS](https://tls.mbed.org/) - Implementation of the SSL/TLS and DTLS protocols. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [s2n](https://github.com/awslabs/s2n-tls) - C99 implementation of the TLS/SSL protocols. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [NSS](https://firefox-source-docs.mozilla.org/security/nss/index.html) - A set of cryptographic libraries designed to support cross-platform development of security-enabled client and server applications. [MPL-2.0](https://spdx.org/licenses/MPL-2.0.html)
- [liboqs](https://openquantumsafe.org/) - Library for quantum-resistant cryptographicl algorithms. [MIT](https://spdx.org/licenses/MIT.html)
- [libsodium](https://download.libsodium.org/doc) - Modern and easy-to-use crypto library. [MIT](https://spdx.org/licenses/MIT.html)
- [libtomcrypt](https://www.libtom.net) - Fairly comprehensive, modular and portable cryptographic toolkit. Public domain.
- [MIRACL](https://github.com/miracl/MIRACL) - Multiprecision Integer and Rational Arithmetic Cryptographic Library; an SDK for elliptic curve cryptography. [AGPL-3.0-or-later](https://spdx.org/licenses/AGPL-3.0-or-later.html)
- [retter](https://maciejczyzewski.github.io/retter) - Collection of hash functions, ciphers, tools, libraries and materials related to cryptography and security. Public domain.
- [sphlib](http://www.saphir2.com/sphlib/) - Set of implementations of various hash functions, including several cryptographic ones. [MIT](https://spdx.org/licenses/MIT.html)
- [trezor-crypto](https://github.com/trezor/trezor-crypto) - Heavily optimized crypto algorithms for embedded devices. [MIT](https://spdx.org/licenses/MIT.html)
- [bfish](https://github.com/cjwagenius/bfish) - A single include ANSI-C Blowfish ECB crypto library. Public domain.

## Database

Databases and data stores with C APIs.

- [BerkeleyDB](http://www.oracle.com/us/products/database/berkeley-db) - Library for a high-performance embedded database for key-value data. [AGPL-3.0-only](https://spdx.org/licenses/AGPL-3.0-only.html)
- [DuckDB](https://duckdb.org/) - Fast in-process analytical database, with C API. [MIT](https://spdx.org/licenses/MIT.html)
- [EJDB2](https://ejdb.org/) - Embeddable JSON Database engine. [MIT](https://spdx.org/licenses/MIT.html)
- [Groonga](https://github.com/groonga/groonga) - Columnar store with full-text search. [LGPL-2.1-only](https://spdx.org/licenses/LGPL-2.1-only.html)
- [Hiredis](https://github.com/redis/hiredis) - Minimalistic client library for Redis. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [libmongoc](http://mongoc.org/) - High-performance client library for [MongoDB](https://www.mongodb.org/). [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [LMDB](https://www.symas.com/lmdb) - Ultra-fast, ultra-compact key-value embedded data store. [OLDAP-2.8](https://spdx.org/licenses/OLDAP-2.8.html)
- [MySQL](https://github.com/mysql/mysql-server) - The world's most popular open source database. [GPL-2.0-only](https://spdx.org/licenses/GPL-2.0-only.html)
- [PostgreSQL](https://www.postgresql.org/) - Powerful object-relational database system. [PostgreSQL](https://spdx.org/licenses/PostgreSQL.html)
- [Redis](https://redis.io/) - Advanced key-value store. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [monotone](https://github.com/amelielabs/monotone) - Embeddable Cloud-Native Key-Value Storage For Sequential Data. [MIT](https://spdx.org/licenses/MIT.html)
- [sparkey](https://github.com/spotify/sparkey) - Simple constant key/value storage library. Designed for read-heavy loads with infrequent, large bulk inserts. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [SQLite](https://www.sqlite.org/) - Self-contained, serverless, zero-configuration, transactional SQL database engine. Public domain.
- [UnQLite](https://unqlite.symisc.net/) - Self-contained, serverless, zero-configuration, transactional NoSQL engine. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [WhiteDB](https://github.com/priitj/whitedb) - Lightweight database library, operating entirely in main memory. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [FlashDB](https://github.com/armink/FlashDB) - An ultra-lightweight database that supports key-value and time series data. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [TDengine](https://github.com/taosdata/TDengine) - High-performance, cloud native time-series database. [AGPL-3.0-only](https://spdx.org/licenses/AGPL-3.0-only.html)

## Data Structures

- [C-Macro-Collections](https://github.com/LeoVen/C-Macro-Collections) - Generate simple and generic data structures using macros. [MIT](https://spdx.org/licenses/MIT.html)
- [CLIST](https://github.com/AlexanderAgd/CLIST) - Simple and lightweight [dynamic array](https://en.wikipedia.org/wiki/Dynamic_array) implementation. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [Collections-C](https://github.com/srdja/Collections-C) - Library of generic data structures. [LGPL-3.0-or-later](https://spdx.org/licenses/LGPL-3.0-or-later.html)
- [CTL](https://github.com/rurban/ctl) - C CONTAINER TEMPLATE LIBRARY (CTL) [MIT](https://spdx.org/licenses/MIT.html)
- [ds](https://github.com/recp/ds) - Common Data Structures and Algorithms. [MIT](https://spdx.org/licenses/MIT.html)
- [igraph](https://igraph.org/) - A graph processing library. [GPL-2.0-or-later](https://spdx.org/licenses/GPL-2.0-or-later.html)
- [kdtree](https://github.com/jtsiomb/kdtree) - Simple library for working with KD-trees. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [libavl](http://adtinfo.org/libavl.html/index.html) - Library containing a range of self-balancing binary trees. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [libcdada](https://msune.github.io/libcdada/) - A small, portable, MACRO-less library for basic data structures (list, set, map, queue…) in C (C++ backend). [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [liblfds](https://liblfds.org/) - Portable lock-free data structure library. Public domain (more exactly, whatever license you want).
- [libsrt](https://faragon.github.io/libsrt.html) - Soft and hard real-time data structures. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html).
- [list.h](https://github.com/nbulischeck/list.h) - Implementations for singly linked and doubly linked list functions. [GPL-3.0-only](https://spdx.org/licenses/GPL-3.0-only.html)
- [M\*LIB](https://github.com/P-p-H-d/mlib) - Library for generic, but typesafe C containers. Implemented as header-only. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [offbrand](https://github.com/theck01/offbrand_lib) - Collection of generic, reference-counted data structures. [MIT](https://spdx.org/licenses/MIT.html)
- [PackedArray](https://github.com/gpakosz/PackedArray) - Random-access array of tightly packed unsigned integers of any desired width. Has a SIMD-optimized implementation. [WTFPL](https://spdx.org/licenses/WTFPL.html)
- [rb3ptr](http://jstimpfle.de/projects/rb3ptr/rb3ptr.html) - Red-Black tree. Exposes almost all implementation primitives, so can be used for scenarios like augmentation, multiple compatible ordering functions, and more. [MIT](https://spdx.org/licenses/MIT.html)
- [uthash](http://troydhanson.github.io/uthash/) - Single-file hash table implementation. [BSD-1-Clause](https://spdx.org/licenses/BSD-1-Clause.html)
- [vector.h](https://github.com/swenson/vector.h) - Header library for typed lists. [MIT](https://spdx.org/licenses/MIT.html)
- [hashmap](https://github.com/DavidLeeds/hashmap) - Templated type-safe hashmap implementation in C using open addressing and linear probing for collision resolution. [MIT](https://spdx.org/licenses/MIT.html)
- [STC](https://github.com/stclib/STC) - STC is a mature, comprehensive, general purpose container and algorithm library for C99/C11. [MIT](https://spdx.org/licenses/MIT.html)
- [clibs](https://github.com/paulborile/clibs) - Simple, fast, threadsafe C language hashtable, LRU map, Thread pool, go like channel, vector. [MIT](https://spdx.org/licenses/MIT.html)

## Debugging

Because we all have to do it sometimes. Various tools for making debugging easier or better, as well as libraries or code that allows better debugging work.

- [C-Reduce](https://embed.cs.utah.edu/creduce/) - Tool that takes a large C file with a property of interest and automatically produces a much smaller C file that has the same property. Intended to help create minimal bug-demonstrating cases in complex code. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [CBMC](https://www.cprover.org/cbmc/) - C Bounded Model Checker; a tool for verification of array bounds, pointer safety and user-specified assertions. [BSD-4-Clause](https://spdx.org/licenses/BSD-4-Clause.html)
- [cflow](http://www.gnu.org/software/cflow/) - Analyzes a collection of source files and prints a graph charting control flow in the program. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [Complexity](https://www.gnu.org/software/complexity/) - Tool for measuring the complexity of source code. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [CScout](https://www.spinellis.gr/cscout/) - Source code analyzer and refactoring browser for C programs. [GPL-3.0-only](https://spdx.org/licenses/GPL-3.0-only.html)
- [DDD](https://www.gnu.org/software/ddd/ddd.html) - Graphical front-end for a range of command-line debuggers. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [debug](https://github.com/esneider/debug) - One-header library for easier 'printf debugging'. [MIT](https://spdx.org/licenses/MIT.html)
- [ESBMC](http://esbmc.org/) - Efficient SMT-based Bounded Model Checker; a tool for verification of single and multithread programs, user assertions, overflow, and pointer/memory safety. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [GDB](https://www.gnu.org/software/gdb/) - GNU Project debugger. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [lldb](https://lldb.llvm.org/) - LLVM debugger. [Apache License v2.0 with LLVM Exceptions](https://llvm.org/LICENSE.txt)
- [Owi](https://github.com/OCamlPro/owi) - A symbolic execution tool ([paper](https://hal.science/hal-04627413)) [AGPL-3.0-or-later](https://spdx.org/licenses/AGPL-3.0-or-later.html)
- [rr](https://rr-project.org/) - Debugger that records non-deterministic executions to allow for deterministic debugging. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [Valgrind](http://www.valgrind.org/) - Range of dynamic analysis tools, including a leak checker. [GPL-2.0-only](https://spdx.org/licenses/GPL-2.0-only.html)

## Documentation Generation

- [Cxref](http://www.gedanken.org.uk/software/cxref/) - Generates documentation in either LaTeX, HTML, RTF or SGML. [GPL-2.0-only](https://spdx.org/licenses/GPL-2.0-only.html)
- [DocOnce](https://hplgit.github.io/doconce/doc/web/index.html) - Modestly tagged markup language that can be used to generate a range of formats. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [Doxygen](http://www.doxygen.nl/) - De-facto standard tool for generating documentation from annotated sources. Can generate a large range of formats. [GPL-2.0-only](https://spdx.org/licenses/GPL-2.0-only.html)

## Frameworks

Big libraries that provide data structures and other stuff you expect of a 'modern' standard library.

- [APR](http://apr.apache.org/) - Apache Portable Runtime; another library of cross-platform utility functions. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [NSPR](https://firefox-source-docs.mozilla.org/nspr/index.html) - A platform-neutral API for system level and libc like functions. [MPL-2.0](https://spdx.org/licenses/MPL-2.0.html)
- [C Algorithms](https://fragglet.github.io/c-algorithms) - Collection of common algorithms and data structures. [ISC](https://spdx.org/licenses/ISC.html)
- [CPL](http://www.eso.org/sci/software/cpl/) - The Common Pipeline Library; a set of libraries designed to be a comprehensive, efficient and robust software toolkit. [GPL-2.0-only](https://spdx.org/licenses/GPL-2.0-only.html)
- [EFL](https://www.enlightenment.org) - Large collection of useful data structures and functions. Various licenses, all open source.
- [GLib](https://wiki.gnome.org/Projects/GLib) - Library of utility functions and structures, designed to be portable, efficient and powerful. [LGPL-2.1-only](https://spdx.org/licenses/LGPL-2.1-only.html)
- [klib](http://attractivechaos.github.io/klib/#About) - Small and lightweight implementations of common algorithms and data structures. [MIT](https://spdx.org/licenses/MIT.html)
- [libcork](http://libcork.readthedocs.io/en/0.14.0/) - Utility functions and structures, designed for resource-constrained systems. Can be embedded. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [libnih](https://github.com/keybuk/libnih) - Lightweight library of functions and structures. [GPL-2.0-only](https://spdx.org/licenses/GPL-2.0-only.html)
- [libU](http://www.koanlogic.com/libu/) - Small library of basic utilities, including memory allocation, string manipulation and logging. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [PBL](http://www.mission-base.com/peter/source/) - Large library of utilities, featuring data structures, among other things. [LGPL-2.1-or-later](https://spdx.org/licenses/LGPL-2.1-or-later.html)
- [plibsys](https://github.com/saprykin/plibsys) - Cross-platform system C library. Zero third-party dependencies, uses only native system calls. [MIT](https://spdx.org/licenses/MIT.html)
- [qlibc](http://wolkykim.github.io/qlibc) - Simple and powerful library, designed as a replacement for GLib while focusing on being small and light. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [sc](https://github.com/tezc/sc) - Common libraries and data structures for C. [MIT](https://spdx.org/licenses/MIT.html)
- [TBOX](https://github.com/waruqi/tbox) - Multi-platform library with a large number of capabilities. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [pspsdk](https://github.com/pspdev/pspsdk) - An open-source SDK for PSP homebrew development. [Various licences](https://github.com/pspdev/pspsdk/blob/master/LICENSE).
- [gear-lib](https://github.com/gozfree/gear-lib) - Gear-Lib, C library for IOT Embedded Multimedia and Network. [MIT](https://spdx.org/licenses/MIT.html)
- [Melon](https://github.com/Water-Melon/Melon) - Melon is a generic cross-platform C library. It contains many algorithms, data structures, functional components, scripting languages and practical frameworks, which can facilitate developers to quickly develop applications and avoid the dilemma of repeated wheel building. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)

## Game Programming

Engines, libraries and other helpful things specifically for making games.

- [Allegro](https://liballeg.org) - Cross-platform, video game development and multimedia library. [Zlib](https://spdx.org/licenses/Zlib.html)
- [AssetKit](https://github.com/recp/AssetKit) 🎨 3D asset importer/exporter/util library based on COLLADA/glTF specs [MIT](https://spdx.org/licenses/MIT.html)
- [astera](https://github.com/tek256/astera) - C99 Cross Platform 2D Game Library [MIT](https://spdx.org/licenses/MIT.html)
- [cglm](https://github.com/recp/cglm) - 📽 Optimized OpenGL/Graphics Math (glm) for C. [MIT](https://spdx.org/licenses/MIT.html)
- [Chipmunk2D](http://chipmunk-physics.net) - Fast and lightweight 2D game physics library. [MIT](https://spdx.org/licenses/MIT.html)
- [cmt](https://github.com/recp/cmt) - 🎮 C Bindings/Wrappers for Apple's METAL Graphics Framework. [MIT](https://spdx.org/licenses/MIT.html)
- [Corange](https://github.com/orangeduck/Corange) - Game engine in pure C. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [CSFML](https://www.sfml-dev.org/download/csfml/) - Binding for [SFML](https://www.sfml-dev.org/index.php). [Zlib](https://spdx.org/licenses/Zlib.html)
- [Darkplaces](https://icculus.org/twilight/darkplaces/) - Modified version of the Quake2 engine. [GPL-2.0-only](https://spdx.org/licenses/GPL-2.0-only.html)
- [Epoxy](https://github.com/anholt/libepoxy) - Library for handling OpenGL function pointer management. [MIT](https://spdx.org/licenses/MIT.html)
- [exengine](https://github.com/solenum/exengine) - 3D game engine in C99 with a starting template. [MIT](https://spdx.org/licenses/MIT.html)
- [Flecs](https://github.com/SanderMertens/flecs) - A Multithreaded Entity Component System written for C89 & C99 [MIT](https://spdx.org/licenses/MIT.html)
- [Freecell Solver](https://github.com/shlomif/fc-solve) - Set of libraries and command-line programs for automatically solving FreeCell and some similar variants of card Solitaire. [MIT](https://spdx.org/licenses/MIT.html)
- [FreeGLUT](http://freeglut.sourceforge.net) - Alternative to the OpenGL Utility Toolkit. Allows the creation and management of windows with OpenGL contexts. [X11](https://spdx.org/licenses/X11.html)
- [GLFW](https://www.glfw.org/) - Multi-platform library for creating windows with OpenGL contexts. [Zlib](https://spdx.org/licenses/Zlib.html)
- [ioquake3](https://ioquake3.org) - Quake3 engine, freed at last. [GPL-2.0-only](https://spdx.org/licenses/GPL-2.0-only.html)
- [kazmath](https://github.com/Kazade/kazmath) - Maths library for games. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [libao](https://xiph.org/ao/) - Cross-platform audio library with a wide variety of outputs. [GPL-2.0-or-later](https://spdx.org/licenses/GPL-2.0-or-later.html)
- [librg](https://github.com/librg/librg) - Pure C99 game networking library for building simple and elegant cross-platform multiplayer client-server solutions. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [MATHC](https://github.com/ferreiradaselva/mathc) - Math library for 2D and 3D programming. [ZLib](https://spdx.org/licenses/Zlib.html)
- [Orx](http://orx-project.org) - Portable, lightweight, plugin-based, data-driven, 2D-oriented game engine. [Zlib](https://spdx.org/licenses/Zlib.html)
- [Quake](https://github.com/id-Software/Quake) - Quake engine. [GPL-2.0-only](https://spdx.org/licenses/GPL-2.0-only.html)
- [Quake2](https://github.com/id-Software/Quake-2) - Quake2 engine. [GPL-2.0-only](https://spdx.org/licenses/GPL-2.0-only.html)
- [raylib](https://www.raylib.com) - Simple and easy-to-use library to learn video game programming. [Zlib](https://spdx.org/licenses/Zlib.html)
- [RetroArch](https://github.com/libretro/RetroArch) - Reference frontend for [libretro](https://www.libretro.com/). [GPL-3.0-only](https://spdx.org/licenses/GPL-3.0-only.html)
- [SDL2](https://www.libsdl.org/) - Cross-platform library designed to provide low-level access to audio, keyboard, mouse, joystick and graphics hardware via OpenGL. [Zlib](https://spdx.org/licenses/Zlib.html)
- [sdl-gpu](https://github.com/grimfang4/sdl-gpu) - Library for high-performance, modern 2D graphics. Based on SDL. [MIT](https://spdx.org/licenses/MIT.html)
- [SIGIL](http://www.libsigil.com/) - Sound, Input and Graphics Integration Library; a simple alternative to other libraries for doing all those things. Various licenses, all open source.
- [uastar](https://github.com/ferreiradaselva/uastar) - Minimal A\* implementation. [ZLib](https://spdx.org/licenses/Zlib.html)
- [sokol_gp](https://github.com/edubart/sokol_gp) - Minimal modern efficient cross platform 2D graphics painter in C. [MIT-0](https://spdx.org/licenses/MIT-0.html)
- [SOIL2](https://github.com/SpartanJ/SOIL2) - SOIL2 is a tiny C library used primarily for uploading textures into OpenGL. [MIT-0](https://spdx.org/licenses/MIT-0.html)
- [TIGR](https://github.com/erkkah/tigr) - TIGR - the TIny GRaphics library for Windows, macOS, Linux, iOS and Android. [Unlicense](https://spdx.org/licenses/Unlicense.html)
- [ufbx](https://github.com/ufbx/ufbx) - Single source file FBX loader. [MIT](https://spdx.org/licenses/MIT.html) or [Unlicense](https://spdx.org/licenses/Unlicense.html)
- [linmath.h](https://github.com/datenwolf/linmath.h) - a lean linear math library, aimed at graphics programming. Supports vec3, vec4, mat4x4 and quaternions [WTFPL](https://spdx.org/licenses/WTFPL.html)
- [HandmadeMath](https://github.com/HandmadeMath/HandmadeMath) - A simple math library for games and computer graphics. Compatible with both C and C++. [CC0-1.0](https://spdx.org/licenses/CC0-1.0.html)
- [Equilibrium Engine](https://github.com/clibequilibrium/EquilibriumEngine) - Data-oriented and multi-threaded C11 Game Engine with libraries & shaders hot-reloading. [GPL-2.0-or-later](https://spdx.org/licenses/GPL-2.0-or-later.html)
- [Permafrost Engine](https://github.com/eduard-permyakov/permafrost-engine) - Permafrost Engine is an OpenGL 3.3 Real Time Strategy game engine written in C. It is made in the image of old classics, but incorporating some modern ideas. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [RGFW](https://github.com/ColleagueRiley/RGFW) - Lightweight multi-platform single-header library for creating windows, supports many graphics contexts and software rendering. [Zlib](https://spdx.org/licenses/Zlib.html)
- [PainterEngine](https://github.com/matrixcascade/PainterEngine) - PainterEngine is a application/game engine with software renderer. PainterEngine can be transplanted to any platform that supports C. [MIT](https://spdx.org/licenses/MIT.html)

## Graphics

Programmatic manipulation of graphics in C; if you want to make a GUI, the Graphical User Interface section has what you need.

- [AssetKit](https://github.com/recp/AssetKit) 🎨 3D asset importer/exporter/util library based on COLLADA/glTF specs [MIT](https://spdx.org/licenses/MIT.html)
- [Cairo](http://cairographics.org/) - 2D graphics library. [LGPL-2.1-only](https://spdx.org/licenses/LGPL-2.1-only.html) or [MPL-1.1](https://spdx.org/licenses/MPL-1.1.html).
- [cmt](https://github.com/recp/cmt) - 🎮 C Bindings/Wrappers for Apple's METAL Graphics Framework. [MIT](https://spdx.org/licenses/MIT.html)
- [giflib](https://sourceforge.net/projects/giflib/) - Library for reading and writing gif images. [MIT](https://spdx.org/licenses/MIT.html)
- [graphene](http://ebassi.github.io/graphene/) - Thin layer of graphical data types. [MIT](https://spdx.org/licenses/MIT.html)
- [heman](https://github.com/prideout/heman) - Tiny library of image utilities dealing with height maps, normal maps, distance fields and the like. [MIT](https://spdx.org/licenses/MIT.html)
- [libcaca](https://github.com/cacalabs/libcaca) - ASCII renderer for terminal-based interfaces. [WTFPL](https://spdx.org/licenses/WTFPL.html)
- [libgd](https://github.com/libgd/libgd) - Library for the dynamic creation of images by programmers. [MIT](https://spdx.org/licenses/MIT.html)
- [libimagequant](https://pngquant.org/lib/) - Small, portable library for high-quality conversion of RGBA images to 8-bit indexed colour images. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [libjpeg-turbo](https://libjpeg-turbo.virtualgl.org/) - Faster library for reading and writing JPEG files. [Various licences](https://www.libjpeg-turbo.org/About/License).
- [libpng](http://www.libpng.org/) - Official PNG reference library. [Libpng](https://spdx.org/licenses/Libpng.html)
- [libRSVG](https://wiki.gnome.org/Projects/LibRsvg) - Library to render SVG files using Cairo. [LGPL-2.1-or-later](https://spdx.org/licenses/LGPL-2.1-or-later.html)
- [libsixel](https://github.com/saitoha/libsixel) - Library implementing the SIXEL protocol, allowing beautiful graphics in your terminal. [MIT](https://spdx.org/licenses/MIT.html)
- [libspng](https://libspng.org/) - A simpler interface for reading and writing PNG files. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [libvips](https://libvips.github.io/libvips/) - Image processing library. [LGPL-2.1-or-later](https://spdx.org/licenses/LGPL-2.1-or-later.html)
- [libxmi](https://gnu.org/software/libxmi/) - Function library for rasterizing 2D vector graphics. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [lightmapper](https://github.com/ands/lightmapper) - Single-file library for lightmap baking, using an existing OpenGL renderer. Public domain.
- [little CMS](https://www.littlecms.com/) - A Color Management System. It provides fast transforms between ICC profiles. [MIT](https://spdx.org/licenses/MIT.html)
- [mozjpeg](https://github.com/mozilla/mozjpeg) - Improved JPEG encoder. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [nanovg](https://github.com/memononen/nanovg) - Anti-aliased 2D vector drawing library on top of OpenGL, for UI and visualizations. [Zlib](https://spdx.org/licenses/Zlib.html)
- [OpenGL](https://www.opengl.org/) - Industry standard for high-performance graphics, with a native C binding. [Various licenses](http://www.sgi.com/tech/opengl/?/license.html).
- [PlutoVG](https://github.com/sammycage/plutovg) - A standalone 2D vector graphics library in C [MIT](https://spdx.org/licenses/MIT.html)
- [SAIL](https://github.com/smoked-herring/sail) - ⛵ The missing small and fast image decoding library for humans (not for machines) [MIT](https://spdx.org/licenses/MIT.html)

## Graphical User Interface

Widget toolkits, or things meant to be used in a similar way to them.

- [GTK+](https://www.gtk.org/) - Cross-platform widget toolkit. [LGPL-2.1-only](https://spdx.org/licenses/LGPL-2.1-only.html)
- [IUP](https://www.tecgraf.puc-rio.br/iup/) - Another cross-platform widget toolkit. [MIT](https://spdx.org/licenses/MIT.html)
- [microui](https://github.com/rxi/microui) - Tiny immediate-mode UI library written in portable ANSI C. [MIT](https://spdx.org/licenses/MIT.html)
- [nappgui](https://nappgui.com/) - Professional SDK to build cross-platform desktop applications using C. [MIT](https://spdx.org/licenses/MIT.html)
- [nuklear](https://github.com/Immediate-Mode-UI/Nuklear) - Small, C89, single-header widget toolkit. Public domain.
- [tinyfiledialogs](https://sourceforge.net/projects/tinyfiledialogs/) - Single-file library for simple dialogs. Compatible with many other toolkits and OSes. [Zlib](https://spdx.org/licenses/Zlib.html)
- [Tk](http://www.tcl.tk/) - Basic widget toolkit. Part of Tcl/Tk. [TCL](https://spdx.org/licenses/TCL.html)
- [XForms Toolkit](http://xforms-toolkit.org/) - Widget toolkit designed for the XWindow system. [LGPL-2.1-only](https://spdx.org/licenses/LGPL-2.1-only.html)
- [LVGL](https://lvgl.io/) - embedded GUI with easy-to-use graphical elements, beautiful visuals and a low memory footprint. [MIT](https://spdx.org/licenses/MIT.html)
- [luigi](https://github.com/nakst/luigi) - A barebones single-header GUI library for Win32, X11 and Essence. [MIT](https://spdx.org/licenses/MIT.html)
- [dwindows](https://github.com/dbsoft/dwindows) - A GTK-like window toolkit for creating modern crossplatform applications. (OS/2, Windows, Unix, Mac, iOS, Android) [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [libui-ng](https://github.com/libui-ng/libui-ng) - Simple and portable (but not inflexible) GUI library in C that uses the native GUI technologies of each platform it supports. [MIT](https://spdx.org/licenses/MIT.html)
- [AWTK](https://github.com/zlgopen/awtk) - AWTK = Toolkit AnyWhere (a cross-platform embedded GUI) [LGPL-2.1-or-later](https://spdx.org/licenses/LGPL-2.1-or-later.html)
- [MiniGUI](https://github.com/VincentWei/MiniGUI) - A modern and mature cross-platform window system for embedded systems. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [u8g2](https://github.com/olikraus/u8g2) - U8glib library for monochrome displays, version 2. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [Clay](https://github.com/nicbarker/clay/) - High performance UI layout library in C. [Zlib](https://spdx.org/licenses/Zlib.html)

## Hashing

Hash function implementations for non-crypto purposes. Cryptographic hashes can be found in the Crypto section.

- [CLHash](https://github.com/lemire/clhash) - Library implementing the ridiculously fast CLHash hashing function. Only works on Intel Haswell or newer. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [HighwayHash](https://github.com/google/highwayhash) - Fast, strong, SIMD-using hash function. Also contains an implementation of SipHash (although this is slower). [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [SpookyHash](https://github.com/centaurean/spookyhash) - Extremely fast hash function. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [t1ha](https://github.com/leo-yuriev/t1ha) - Fast Positive Hash - a portable, fast hash function. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [xxHash](http://cyan4973.github.io/xxHash) - Extremely fast hashing algorithm. Comes in 32 and 64-bit varieties. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)

## Learning, Reference and Tutorials

Resources for learning C programming in general, or something useful relating to C programming.

### Reference resources online

- [Benchmarks of the Lockless Memory Allocator](https://locklessinc.com/benchmarks_allocator.shtml)
- [C FAQ - comp.lang.c Frequently Asked Questions](http://c-faq.com/)
- [Comparison of C/POSIX standard library implementations for Linux](http://www.etalabs.net/compare_libcs.html)
- [Pre-defined Compiler Macros wiki](https://github.com/cpredef/predef)
- [Modern C features](https://github.com/AnthonyCalandra/modern-c-features)
- [How to be low-level programmer](https://github.com/gurugio/lowlevelprogramming-university)
- [Finding the best 64-bit simulation PRNG](http://nullprogram.com/blog/2017/09/21/)
- [SEI CERT C Coding Standard](https://wiki.sei.cmu.edu/confluence/display/c/SEI+CERT+C+Coding+Standard)
- [tinyc.game](https://github.com/superjer/tinyc.games) - Tiny C games you can compile and run RIGHT NOW <http://tinyc.games> [MIT](https://spdx.org/licenses/MIT.html)

### Beginner resources online

- [A tutorial on pointers](https://pdos.csail.mit.edu/6.828/2017/readings/pointers.pdf)
- [A tutorial on portable Makefiles](http://nullprogram.com/blog/2017/08/20/)
- [Building C Projects](http://nethack4.org/blog/building-c.html)
- [C Programming Wikibook](https://en.wikibooks.org/wiki/C_Programming)
- [Introduction to "Fun" C (using GCC)](https://gist.github.com/eatonphil/21b3d6569f24ad164365)
- [Learning C with GDB](https://www.recurse.com/blog/5-learning-c-with-gdb)
- [memcpy vs memmove](https://web.archive.org/web/20170620131430/https://www.tedunangst.com/flak/post/memcpy-vs-memmove)
- [POSIX Threads Programming tutorial](https://computing.llnl.gov/tutorials/pthreads/) (a little dated, but most of it is still valid and useful)
- [The GNU C Programming Tutorial](http://www.crasseux.com/books/ctut.pdf) (online PDF)
- [GNU C Language Manual](https://raw.githubusercontent.com/VernonGrant/gnu-c-language-manual/main/gnu-c-language-manual.pdf) (online PDF)
- [Templating in C](http://blog.pkh.me/p/20-templating-in-c.html)
- [What a C programmer should know about memory](https://marek.vavrusa.com/memory/)
- [CodeforWin: Learn C Programming, Data Structures Tutorials and Exercises online](https://codeforwin.org/2015/09/singly-linked-list-data-structure-in-c.html)
- [Learn C: Free and Open-Source Interactive C Tutorial](https://www.learn-c.org)
- [How to program a text adventure in C](https://github.com/helderman/htpataic)

### Intermediate resources online

- [8 gdb tricks you should know](https://blogs.oracle.com/linux/8-gdb-tricks-you-should-know-v2)
- [10 C99 tricks](http://blog.noctua-software.com/c-tricks.html)
- [A comprehensive MPI tutorial resource](http://mpitutorial.com/)
- [Build Your Own Text Editor](https://viewsourcecode.org/snaptoken/kilo/)
- [Diving into concurrency: trying out mutexes and atomics](https://jvns.ca/blog/2014/12/14/fun-with-threads/)
- [Generic C reference counting](https://nullprogram.com/blog/2015/02/17)
- [How to write portable C without complicating your build](https://nullprogram.com/blog/2017/03/30)
- [Introduction to OpenMP](https://www.youtube.com/playlist?list=PLLX-Q6B8xqZ8n8bwjGdzBJ25X2utwnoEG) (video)
- [OpenMP tutorial](https://computing.llnl.gov/tutorials/openMP/) (for the OpenMP3 standard)
- [MPI tutorial](https://computing.llnl.gov/tutorials/mpi/)
- [Scalable C - Writing Large-Scale Distributed C](https://hintjens.gitbooks.io/scalable-c/content/index.html)
- [Some unknown features or tricks in C language](https://proprogramming.org/some-unknown-features-or-tricks-in-c-language/)
- [What every C programmer should know about undefined behaviour](http://blog.llvm.org/2011/05/what-every-c-programmer-should-know.html)

### Advanced resources online

- [Advanced metaprogramming in C](http://250bpm.com/blog:56)
- [A quick tutorial on implementing and debugging malloc, free, calloc, and realloc](http://danluu.com/malloc-tutorial/)
- [Bit twiddling hacks](https://graphics.stanford.edu/~seander/bithacks.html)
- [Implementing smart pointers for the C programming language](http://snaipe.me/c/c-smart-pointers/)
- [Inline functions in C](http://www.greenend.org.uk/rjk/tech/inline.html)
- [Metaprogramming custom control structures in C](https://www.chiark.greenend.org.uk/~sgtatham/mp/)
- [Solving the temporary storage problem of C macros](https://web.archive.org/web/20170429175803/http://www.samnip.ps/thought/macro-storage-for-inverse-comma)
- [Some dark corners of C](https://docs.google.com/presentation/d/1h49gY3TSiayLMXYmRMaAEMl05FaJ-Z6jDOWOz3EsqqQ/edit?pli=1#slide=id.gaf50702c_0153)
- [Writing efficient C and C code optimization](https://www.codeproject.com/Articles/6154/Writing-Efficient-C-and-C-Code-Optimization)
- [Compiling Algebraic Data Types in Pure C99](https://hirrolot.github.io/posts/compiling-algebraic-data-types-in-pure-c99.html)

### Reference books

- [C: A Reference Manual 5E](https://savedparadigms.files.wordpress.com/2014/09/harbison-s-p-steele-g-l-c-a-reference-manual-5th-ed.pdf) - Full reference book for C99.
- [C in a Nutshell 2E](http://shop.oreilly.com/product/0636920033844.do) - Concise reference book for C11.
- [C Pocket Reference](http://shop.oreilly.com/product/9780596004361.do) - Concise reference book for C99.
- [The C Programming Language 2E](https://en.wikipedia.org/wiki/The_C_Programming_Language) - Original book on C, by its creators.

### Beginner books

- [C Primer Plus 6E](https://www.pearson.com/us/higher-education/program/Prata-C-Primer-Plus-6th-Edition/PGM4399.html) - Complete tutorial on programming in C11.
- [C Programming: A Modern Approach](http://knking.com/books/c2/index.html) - Excellent book to learn the basics of C.
- [Head First C](http://shop.oreilly.com/product/0636920015482.do) - 'Head-first' style book for learning C.

### Intermediate books

- [21st Century C](http://shop.oreilly.com/product/0636920033677.do) - Good second programming book on C.
- [Understanding and Using C Pointers](http://shop.oreilly.com/product/0636920028000.do) - In-depth resource on pointers in C.
- [ZeroMQ](http://shop.oreilly.com/product/0636920026136.do) - Book for using ZeroMQ with C.

### Advanced books

- [Expert C Programming: Deep C Secrets](https://dl.acm.org/citation.cfm?id=179241) - Interesting, in-depth and entertaining look at the innards of C.
- [Modern C, Third Edition: Covers the C23 standard](http://savannah.nongnu.org/projects/attr/) - In Modern C, Third Edition you'll learn to harness C's full potential using the latest tools and techniques.

## Lexing and Parsing

Libraries specifically for lexical analysis (or lexing) and syntactic analysis (or parsing).

- [flex](https://github.com/westes/flex) - Fast lexical analyzer generator. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [GNU Bison](https://www.gnu.org/software/bison/) - General-purpose parser generator that converts an annotated context-free grammar into a range of parsers. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [hammer](https://github.com/abiggerhammer/hammer) - Parser combinators for binary formats. [GPL-2.0-only](https://spdx.org/licenses/GPL-2.0-only.html)
- [mpc](https://github.com/orangeduck/mpc) - Parser combinator library. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [owl](https://github.com/ianh/owl) - A parser generator for visibly pushdown languages. [MIT](https://spdx.org/licenses/MIT.html)
- [re2c](http://re2c.org/index.html) - Lexer generator, producing fast lexers, with access to its internals. Public domain.

## Memory Management

Whether a different, faster malloc or outright garbage collection, anything to do with managing C memory lives here.

- [Boehm GC](https://www.hboehm.info/gc/) - Garbage collection for C. Various licenses, all open source.
- [jemalloc](http://jemalloc.net) - Malloc implementation that emphasizes avoidance of fragmentation and scalable concurrency support. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [Lockless Memory Allocator](https://locklessinc.com/) - Efficient memory allocator. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [libcsptr](https://github.com/Snaipe/libcsptr) - Smart pointers for C. [MIT](https://spdx.org/licenses/MIT.html)
- [rpmalloc](https://github.com/rampantpixels/rpmalloc) - Thread-caching, fast memory allocator, naturally aligned on 32-byte boundaries. Public domain.
- [talloc](https://talloc.samba.org/talloc/doc/html/index.html) - Hierarchical, reference-counted memory pool system with destructors. [LGPL-3.0-or-later](https://spdx.org/licenses/LGPL-3.0-or-later.html)
- [tlsf](http://www.gii.upv.es/tlsf/) - Two-Level Segregated Fit allocator; a general-purpose, dynamic memory allocator designed to meet real-time requirements. [Up-to-date implementation](https://github.com/minad/tlsf). [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [c-raii](https://github.com/zelang-dev/c-raii) - An general RAII implementation for C, with Defer, simple high-level C11/C++11 like Threading/Futures, custom malloc/heap allocation. [MIT](https://spdx.org/licenses/MIT.html)

## Multimedia

- [aubio](https://github.com/aubio/aubio) - Library for audio and music analysis. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [FFMPEG](https://www.ffmpeg.org/) - Complete, cross-platform solution to record, convert and stream audio and video. [LGPL-2.1-or-later](https://spdx.org/licenses/LGPL-2.1-or-later.html)
- [GStreamer](https://gstreamer.freedesktop.org/) - Framework for audio and visual media. [LGPL-2.1-or-later](https://spdx.org/licenses/LGPL-2.1-or-later.html)
- [libmpv](https://mpv.io) - Music-playing library. [GPL-2.0-or-later](https://spdx.org/licenses/GPL-2.0-or-later.html)
- [libsndfile](http://www.mega-nerd.com/libsndfile/) - Library for reading and writing sound files. Supports many formats. [LGPL-2.1-only](https://spdx.org/licenses/LGPL-2.1-only.html) or [LGPL-3.0-only](https://spdx.org/licenses/LGPL-3.0-only.html)
- [libsoundio](http://libsound.io) - Library for cross-platform, real-time audio input and output. Has a range of back-ends. [MIT](https://spdx.org/licenses/MIT.html)
- [libVLC](https://wiki.videolan.org/LibVLC) - Complete multimedia library for audio and video encoding, decoding, playing and streaming. [GPL-2.0-only](https://spdx.org/licenses/GPL-2.0-only.html)
- [lodepng](https://lodev.org/lodepng/) - Simple PNG image decoder and encoder, requiring no other dependencies. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [minimp3](https://github.com/lieff/minimp3) - Lightweight MP3 decoder single header library. [CC0-1.0](https://spdx.org/licenses/CC0-1.0.html)
- [Soundpipe](http://paulbatchelor.github.io/proj/soundpipe.html) - Lightweight music DSP library. [MIT](https://spdx.org/licenses/MIT.html)

## Networking and Internet

Low-level networking and internet-related stuff. If you want something more comprehensive and high-level, you may want the Web Frameworks section.

- [asnlc](http://lionet.info/asn1c/compiler.html) - Compiler of ASN.1 specifications into C source code. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [CHL](https://github.com/it4e/CHL) - C Hypertext Library - A library for writing web applications in C. [GPL-3.0-only](https://spdx.org/licenses/GPL-3.0-only.html)
- [czmq](http://czmq.zeromq.org) - High-level binding for ZeroMQ. [MPL-2.0](https://spdx.org/licenses/MPL-2.0.html)
- [Dyad.c](https://github.com/rxi/dyad) - Lightweight, easy, asynchronous networking library. [MIT](https://spdx.org/licenses/MIT.html)
- [GNU adns](https://www.gnu.org/software/adns/) - Advanced, easy-to-use, asynch-capable DNS client library and utilities. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [gumbo-parser](https://github.com/google/gumbo-parser) - HTML5 parsing library in C99. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [H20](https://h2o.examp1e.net/) - A new-generation HTTP server. [MIT](https://spdx.org/licenses/MIT.html)
- [llhttp](https://llhttp.org) - HTTP request/response parser. [MIT](https://spdx.org/licenses/MIT.html)
- [ldns](http://www.nlnetlabs.nl/projects/ldns/index.html) - Library to simplify DNS programming. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [libcurl](https://curl.haxx.se/libcurl/) - Client-side URL transfer library, supporting a wide range of formats. [curl](https://spdx.org/licenses/curl.html)
- [LibEtPan](http://www.etpan.org) - Mail library providing an efficient network for IMAP, SMTP, POP and NNTP. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [libev](http://software.schmorp.de/pkg/libev.html) - Yet another event loop. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [libevent](http://libevent.org/) - Event loop replacement for network servers. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [libhv](https://github.com/ithewei/libhv) - Cross platform event loop library. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [libidn](https://gnu.org/software/libidn/) - Implementation of the Stringprep, Punycode and IDNA specifications. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [libmicrohttpd](https://gnu.org/software/libmicrohttpd/) - Small library that makes it easy to run an HTTP server as part of another application. [LGPL-2.1-or-later](https://spdx.org/licenses/LGPL-2.1-or-later.html)
- [libnl](https://www.infradead.org/~tgr/libnl/) - libnl is a collection of libraries to provie APIs to the Netlink protocol (replacement for ioctl). It's primary use is to communicate with the Linux kernel, to modify networking state (interfaces, routing etc…). [LGPL-2.1-only](https://spdx.org/licenses/LGPL-2.1-only.html)
- [libonion](https://www.coralbits.com/libonion/) - HTTP server library, designed to be easy to use. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [libpcap](https://github.com/the-tcpdump-group/libpcap) - API provides to various kernel packet capture mechanism. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [libquickmail](http://sourceforge.net/projects/libquickmail/) - Library intended to give developers a way to send email from their applications. Supports multiple To/Cc/Bcc recipients and attachments without size limits. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [libsagui](https://risoflora.github.io/libsagui/) - Library for cross-platform HTTP servers. [LGPL-3.0-or-later](https://spdx.org/licenses/LGPL-3.0-or-later.html)
- [libuhttpd](https://github.com/zhaojh329/libuhttpd) - A very flexible, lightweight and fully asynchronous HTTP server library based on libev and http-parser for Embedded Linux. [MIT](https://spdx.org/licenses/MIT.html)
- [LibVNCServer](https://github.com/LibVNC/libvncserver) - Cross-platform libraries to implement VNC server and/or client functionality. [GPL-2.0-or-later](https://spdx.org/licenses/GPL-2.0-or-later.html)
- [libwebsock](https://github.com/JonnyWhatshisface/libwebsock) - Easy-to-use and powerful web socket library. [LGPL-3.0-only](https://spdx.org/licenses/LGPL-3.0-only.html)
- [libzmq](https://github.com/zeromq/libzmq) - Core ZeroMQ library, a high-performance asynchronous messaging library, aimed at use in distributed or concurrent applications. C API (backend C++) [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html) with static linking exception
- [lwan](https://lwan.ws) - Experimental, scalable, high-performance HTTP server. [GPL-2.0-only](https://spdx.org/licenses/GPL-2.0-only.html)
- [mongoose](https://cesanta.com) - Embedded web server. [GPL-2.0-only](https://spdx.org/licenses/GPL-2.0-only.html)
- [MQTT-C](https://github.com/LiamBindle/MQTT-C) - A portable MQTT C client for embedded systems and PCs alike. [MIT](https://spdx.org/licenses/MIT.html)
- [nanomsg](https://github.com/nanomsg/nanomsg) - C-based implementation of ZeroMQ. [MIT](https://spdx.org/licenses/MIT.html)
- [NNG](https://nanomsg.github.io/nng/) - nanomsg-next-generation - lightweight brokerless messaging. [MIT](https://spdx.org/licenses/MIT.html)
- [oSip](https://gnu.org/software/osip/) - SIP implementation without additional dependencies. [LGPL-2.1-or-later](https://spdx.org/licenses/LGPL-2.1-or-later.html)
- [silgy](https://github.com/silgy/silgy) - Asynchronous HTTP(S) engine for C/C++ projects. [MIT](https://spdx.org/licenses/MIT.html)
- [socket99](https://github.com/silentbicycle/socket99) - C99 wrapper for the BSD sockets API. [ISC](https://spdx.org/licenses/ISC.html)
- [twitc](https://github.com/sinemetu1/twitc) - Mini library for interacting with the Twitter OAuth API. [MIT](https://spdx.org/licenses/MIT.html)
- [uriparser](https://uriparser.github.io) - Strictly RFC 3986-compliant URI parsing and handling library. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [Wslay](https://tatsuhiro-t.github.io/wslay/) - WebSocket library. Implements version 13 of the WebSocket protocol, as described in RFC 6455. [MIT](https://spdx.org/licenses/MIT.html)
- [zyre](https://github.com/zeromq/zyre) - Framework for proximity-based peer-to-peer applications. [MPL-2.0](https://spdx.org/licenses/MPL-2.0.html)
- [acl](https://github.com/acl-dev/acl) - C/C++ server and network library, including coroutine,redis client,http/https/websocket,mqtt, mysql/postgresql/sqlite client with C/C++ for Linux, Android, iOS, MacOS, Windows, etc.. [LGPL-2.1-only](https://spdx.org/licenses/LGPL-2.1-only.html)

## Numerical

- [apophenia](http://apophenia.info) - Library for statistical and scientific computing. [GPL-2.0-only](https://spdx.org/licenses/GPL-2.0-only.html)
- [Arb](https://github.com/fredrik-johansson/arb) - Library for arbitrary-precision interval arithmetic. [LGPL-2.1-or-later](https://spdx.org/licenses/LGPL-2.1-or-later.html)
- [ATLAS](http://math-atlas.sourceforge.net/) - Automatically Tuned Linear Algebra Software. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [clBLAS](https://github.com/clMathLibraries/clBLAS) - BLAS functions written in OpenCL. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [cmathl](https://scientificc.github.io/cmathl/) - Math library with a great variety of mathematical functions with CMake build support. Seeks to be close to C89/C90 compliant for portability. [MIT](https://spdx.org/licenses/MIT.html)
- [Cuba](http://www.feynarts.de/cuba/) - Library for multidimensional numerical integration. [LGPL-3.0-only](https://spdx.org/licenses/LGPL-3.0-only.html)
- [fft-c](https://github.com/adis300/fft-c) - A high-performance Fourier Transform from netlib's fftpack; wrapped in a user-friendly format \[MIT\]\[ MIT\]
- [FFTW](http://www.fftw.org/) - The Fastest Fourier Transform in the West; a highly optimized fast Fourier transform routine. [GPL-2.0-or-later](https://spdx.org/licenses/GPL-2.0-or-later.html)
- [FLINT](http://flintlib.org/) - Fast Library for Number Theory; a library supporting arithmetic with numbers, polynomials, power series and matrices, among others. [GPL-2.0-or-later](https://spdx.org/licenses/GPL-2.0-or-later.html)
- [GLPK](https://gnu.org/software/glpk/) - GNU Linear Programming Kit; a package designed for solving large-scale linear programming, mixed integer programming and other related problems. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [GMP](https://gmplib.org/) - GNU Multple Precision Arithmetic Library; a library for arbitrary-precision arithmetic. [GPL-2.0-only](https://spdx.org/licenses/GPL-2.0-only.html) or [LGPL-3.0-only](https://spdx.org/licenses/LGPL-3.0-only.html)
- [GNU MPC](http://www.multiprecision.org/mpc/) - Library for complex number arithmetic. [LGPL-3.0-or-later](https://spdx.org/licenses/LGPL-3.0-or-later.html)
- [GNU MPFR](http://mpfr.loria.fr/index.html) - Library for arbitrary-precision floating-point arithmetic. [LGPL-3.0-or-later](https://spdx.org/licenses/LGPL-3.0-or-later.html)
- [GNU MPRIA](https://gnu.org/software/mpria/) - Portable mathematics library for multi-precision rational interval arithmetic. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [GSL](https://www.gnu.org/software/gsl/) - The GNU Scientific Library; a sophisticated numerical library. [GPL-3.0-only](https://spdx.org/licenses/GPL-3.0-only.html).
- [KISS FFT](https://sourceforge.net/projects/kissfft/) - Simple fast Fourier transform library. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [LAPACKE](http://www.netlib.org/lapack/lapacke.html) - Interface to [LAPACK](http://www.netlib.org/lapack/). [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [LibTomMath](http://www.libtom.net/LibTomMath/) - Portable, number-theoretic, multiple-precision integer library. Supports algebra, digit manipulation, modular reductions, and various number-theoretic routines. Public domain.
- [LibTomPoly](http://www.libtom.net/LibTomPoly/) - Polynomial-related maths library. Public domain.
- [PARI/GP](http://pari.math.u-bordeaux.fr/) - Computer algebra system for number theory; includes a compiler to C. [GPL-2.0-or-later](https://spdx.org/licenses/GPL-2.0-or-later.html)
- [PETSc](http://www.mcs.anl.gov/petsc/) - Suite of data structures and routines for scalable parallel solution of scientific applications modelled by partial differential equations. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [SCS](https://github.com/cvxgrp/scs) - Splitting Conic Solver; a numerical optimization package for solving large-scale convex cone problems. [MIT](https://spdx.org/licenses/MIT.html)
- [SLEPc](http://slepc.upv.es/) - Library for the solution of large, sparse eigenvalue problems on parallel computers. [LGPL-3.0-only](https://spdx.org/licenses/LGPL-3.0-only.html)
- [TomsFastMath](http://www.libtom.net/TomsFastMath/) - Set of optimized maths operations (in assembly), suitable for cryptographic use. Public domain.
- [Yeppp!](https://bitbucket.org/MDukhan/yeppp) - Fast, SIMD-optimized mathematical library. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)

## Profiling

- [gperftools](https://github.com/gperftools/gperftools) - Collection of utilities for measuring and improving performance. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [gprof](https://www.gnu.org/software/binutils/) - Performance analysis tool. Part of GNU binutils. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [OProfile](http://oprofile.sourceforge.net/news/) - Statistical profiler for Linux. Can profile any code (including the kernel!) with low overhead and without recompilation. [GPL-2.0-only](https://spdx.org/licenses/GPL-2.0-only.html)
- [perf](https://perf.wiki.kernel.org/index.php/Main_Page) - Linux kernel-based profiler with a lot of functionality. [GPL-2.0-only](https://spdx.org/licenses/GPL-2.0-only.html)

## PDF

- [pdfio](https://github.com/michaelrsweet/pdfio) - PDFio is a simple C library for reading and writing PDF files. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)

## Regex

- [Onigmo](https://github.com/k-takata/Onigmo) - Fork of Oniguruma, supporting more advanced regexps. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [Oniguruma](https://github.com/kkos/oniguruma) - Regex library supporting a wide range of encodings, and incorporating many security-oriented fixes. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [PCRE](http://www.pcre.org/) - Implementation of regexes identical to that of Perl 5. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [SLRE](https://github.com/cesanta/slre) - Super Light Regular Expression library; a small implementation of a subset of Perl regex syntax. [GPL-2.0-only](https://spdx.org/licenses/GPL-2.0-only.html)
- [TRE](https://github.com/laurikari/tre/) - POSIX-compliant, feature-full regex library. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)

## Serialization

- [binn](https://github.com/liteserver/binn) - Binary serialization format, meant to be compact, fast and easy-to-use. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [c-capnproto](https://github.com/jmckaskill/c-capnproto) - Implementation of the Cap'n Proto serialization protocol. [MIT](https://spdx.org/licenses/MIT.html)
- [cmp](https://github.com/camgunz/cmp) - Implementation of the [MessagePack](https://msgpack.org/) serialization protocol. [MIT](https://spdx.org/licenses/MIT.html)
- [flatcc](https://github.com/dvidelabs/flatcc) - [FlatBuffers](https://google.github.io/flatbuffers/) compiler and library. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [libavro](https://avro.apache.org/) - Implementation of the Avro data serialization system. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [mpack](https://github.com/ludocode/mpack) - Another implementation of the [MessagePack](https://msgpack.org/) serialization protocol. [MIT](https://spdx.org/licenses/MIT.html)
- [OPIC](http://opic.rocks/) - Object Persistence in C; a revolutionary serialization framework, with matching on-disk and in-memory representations. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [protobuf-c](https://github.com/protobuf-c/protobuf-c) - Implementation of Google Protocol Buffer. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [tpl](https://github.com/troydhanson/tpl) - Small binary serialization library. [MIT](https://spdx.org/licenses/MIT.html)
- [xdr](https://en.wikipedia.org/wiki/External_Data_Representation) - External Data Representation; a standard for data serialization. Standard (no license applicable).
- [pbtools](https://github.com/eerimoq/pbtools) - Google Protocol Buffers C source code generator. [MIT](https://spdx.org/licenses/MIT.html)

## Source Code Collections

Collections of small source code. If you want something big and integrated, check the Frameworks section.

- [CCAN](http://ccodearchive.net/) - Modelled after Perl's CPAN, this is a big collection of code that does stuff. The full list is [here](http://ccodearchive.net/list.html). Various licenses, all open source.
- [clib](https://github.com/clibs/clib) - Something of a package manager. Comes with a [bunch of libraries of its own](https://github.com/clibs/clib/wiki/Packages). [MIT](https://spdx.org/licenses/MIT.html)
- [gnulib](https://www.gnu.org/software/gnulib/) - Collection of common GNU code. Various licenses, all open source.
- [zpl](https://github.com/zpl-c/zpl) - C99 cross-platform header-only library with many goodies. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html) or [Unlicense](https://spdx.org/licenses/Unlicense.html)
- [libs](https://github.com/mattiasgustavsson/libs) - Single-file public domain libraries for C/C++. [MIT](https://spdx.org/licenses/MIT.html) or [Unlicense](https://spdx.org/licenses/Unlicense.html)
- [libfastcommon](https://github.com/happyfish100/libfastcommon) - c common functions library copied only under the terms of [LGPL-3.0-or-later](https://spdx.org/licenses/LGPL-3.0-or-later.html), detail info please see the c header files.
- [libdjb](http://www.fefe.de/djb/) - Collection of libraries doing various things. (Apparently) public domain.
- [mmx](https://github.com/vurtun/mmx) - Collection of single-header libraries. Various licenses, all open source.
- [par](https://github.com/prideout/par) - Bunch of single-file libraries. [MIT](https://spdx.org/licenses/MIT.html)
- [Snippets](https://github.com/DanielGibson/Snippets/) - Useful code snippets and header-only libraries. Public domain.
- [stb](https://github.com/nothings/stb) - Range of single-file libraries. Public domain.
- [sokol](https://github.com/floooh/sokol) - minimal cross-platform standalone C headers. [Zlib](https://spdx.org/licenses/Zlib.html)
- [tinyheaders](https://github.com/RandyGaul/tinyheaders) - Collection of header-only libraries, primarily oriented toward game development. [Zlib](https://spdx.org/licenses/Zlib.html)
- [cute_headers](https://github.com/RandyGaul/cute_headers) - Collection of cross-platform one-file C/C++ libraries with no dependencies, primarily used for games. [Zlib](https://spdx.org/licenses/Zlib.html) or [Unlicense](https://spdx.org/licenses/Unlicense.html)
- [pico_headers](https://github.com/empyreanx/pico_headers) - Single-header, cross-platform libraries for game development. [Zlib](https://spdx.org/licenses/Zlib.html) or [Unlicense](https://spdx.org/licenses/Unlicense.html)
- [gunslinger](https://github.com/MrFrenik/gunslinger) - C99, header-only framework for games and multimedia applications. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)

## Standard Libraries

Implementations of the (standard-mandated) C standard library.

- [Bionic](https://github.com/aosp-mirror/platform_bionic) - Google's standard library, developed for Android. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [cloudlibc](https://github.com/NuxiNL/cloudlibc) - Standard library based on the concept of [capability-based security](https://en.wikipedia.org/wiki/Capability-based_security). [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [dietlibc](https://www.fefe.de/dietlibc/) - Standard library designed for the smallest possible binaries. [GPL-2.0-only](https://spdx.org/licenses/GPL-2.0-only.html)
- [glibc](https://www.gnu.org/software/libc/) - The GNU C Library; an implementation of the standard library. [LGPL-2.1-only](https://spdx.org/licenses/LGPL-2.1-only.html).
- [musl](https://musl.libc.org/) - Standard library, compatible with POSIX 2008 and C11. Designed for static linking. [MIT](https://spdx.org/licenses/MIT.html)
- [PDCLib](http://pdclib.e43.eu/) - The Public Domain C Library. Implements most of C99 and some of C11. [CC0-1.0](https://spdx.org/licenses/CC0-1.0.html)
- [uClibc-ng](https://uclibc-ng.org/) - Small C library for developing embedded systems. [LGPL-2.1-or-later](https://spdx.org/licenses/LGPL-2.1-or-later.html)
- [Newlib](https://sourceware.org/newlib/) - Newlib is a C library intended for use on embedded systems. It is a conglomeration of several library parts, all under [free software licenses](https://sourceware.org/newlib/COPYING.NEWLIB) that make them easily usable on embedded products.
- [picolibc](https://github.com/picolibc/picolibc) - picolibc - a C library designed for embedded 32- and 64- bit systems. Various licenses, all are [free software licenses](https://github.com/picolibc/picolibc/blob/main/COPYING.picolibc)

## String Manipulation

- [bstring](http://mike.steinert.ca/bstring/) - The Better String Library. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [ICU](http://site.icu-project.org/) - International Components for Unicode; a library for Unicode support. [ICU](https://spdx.org/licenses/ICU.html)
- [levenstein.c](https://github.com/wooorm/levenshtein.c) - [Levenstein distance](https://en.wikipedia.org/wiki/Levenshtein_distance) algorithm implementation. [MIT](https://spdx.org/licenses/MIT.html).
- [libunistring](https://gnu.org/software/libunistring/) - Library for manipulating Unicode strings. [LGPL-3.0-only](https://spdx.org/licenses/LGPL-3.0-only.html)
- [libgiconv](https://gnu.org/software/libiconv/) - Text conversion library. [LGPL-2.1-only](https://spdx.org/licenses/LGPL-2.1-only.html)
- [librope](https://github.com/josephg/librope) - UTF-8 rope ('heavy' string) library. [MIT](https://spdx.org/licenses/MIT.html)
- [SDS](https://github.com/antirez/sds) - Simple Dynamic Strings; a library for handling strings in a simpler way, but one that is compatible with normal C string functions. Available via [clib](https://github.com/clibs/clib). [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [stmr.c](https://github.com/wooorm/stmr.c) - [Porter Stemmer](http://tartarus.org/martin/PorterStemmer/) algorithm implementation. [MIT](https://spdx.org/licenses/MIT.html)
- [str](https://github.com/maxim2266/str) - Yet another string library for C language. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [StringZilla](https://github.com/ashvardanian/StringZilla) - Up to 10x faster SIMD and SWAR-accelerated string search, sort, hashes, edit distances, alignments, and generators. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [utf8.h](https://github.com/sheredom/utf8.h) - Single-header UTF-8 library, designed to mimic C-style string functions. Public domain.
- [utf8proc](https://github.com/JuliaLang/utf8proc) - Library for processing UTF-8 data. [MIT](https://spdx.org/licenses/MIT.html)
- [cuneicode](https://github.com/soasis/cuneicode) - A C library for converting between two different encodings in a simple, easy, and powerful way. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)

## Structured File Processing

This includes libraries for things like XML, JSON, CSV, and other similar formats.

### CSV

- [libcsv](https://github.com/rgamble/libcsv) - Simple, streaming CSV parser. [LGPL-2.1-or-later](https://spdx.org/licenses/LGPL-2.1-or-later.html)
- [zsv](https://github.com/liquidaty/zsv) - a fast CSV parser (simd) library and extensible command-line utility. [MIT](https://spdx.org/licenses/MIT.html)

### JSON

- [Jansson](http://www.digip.org/jansson/) - Library for encoding, decoding and manipulating JSON. [MIT](https://spdx.org/licenses/MIT.html)
- [jfes](https://github.com/NeonMercury/jfes) - JSON For Embedded Systems; simple JSON engine without any dependencies. [MIT](https://spdx.org/licenses/MIT.html)
- [jsmn](https://zserge.com/jsmn.html) - Minimalistic JSON parser. [MIT](https://spdx.org/licenses/MIT.html)
- [json](https://github.com/recp/json) - Simple, low-memory-use JSON parser. [MIT](https://spdx.org/licenses/MIT.html)
- [json-c](https://github.com/json-c/json-c) - Easily work with JSON in C. Comes with a reference-counted object model, and aims for conformance with [RFC 7159](https://tools.ietf.org/html/rfc7159). [MIT](https://spdx.org/licenses/MIT.html)
- [json.h](https://github.com/sheredom/json.h) - Single-file non-streaming JSON parser. [Unlicense](https://spdx.org/licenses/Unlicense.html)
- [parson](https://github.com/kgabis/parson) - Two-file, C89-compatible JSON parser. [MIT](https://spdx.org/licenses/MIT.html)
- [WJElement](https://github.com/netmail-open/wjelement/) - Advanced JSON manipulation library, with support for JSON Schema. [LGPL-2.0-or-later](https://spdx.org/licenses/LGPL-2.0-or-later.html) or [LGPL-2.1-or-later](https://spdx.org/licenses/LGPL-2.1-or-later.html) or [LGPL-3.0-or-later](https://spdx.org/licenses/LGPL-3.0-or-later.html)
- [YAJL](https://lloyd.github.io/yajl/) - Fast streaming JSON parser library. [ISC](https://spdx.org/licenses/ISC.html)

### INI

- [inih](https://github.com/benhoyt/inih) - Small and simple INI file parser, good for embedded systems. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [iniparser](https://github.com/ndevilla/iniparser) - Parser for .ini files. [MIT](https://spdx.org/licenses/MIT.html)
- [libconfini](https://madmurphy.github.io/libconfini/html/index.html) - Yet another INI parser. [GPL-3.0-only](https://spdx.org/licenses/GPL-3.0-only.html)
- [minIni](https://github.com/compuphase/minIni) - Small and portable INI parser. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)

### Others

- [libbson](https://github.com/mongodb/libbson) - BSON utility library. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [libcbor](https://github.com/PJK/libcbor): CBOR protocol implementation for C and others. [MIT](https://spdx.org/licenses/MIT.html)
- [libconfuse](https://github.com/martinh/libconfuse) - Small configuration file parser library. [ISC](https://spdx.org/licenses/ISC.html)
- [libelf](https://github.com/0intro/libelf) - Simple library for parsing ELF files. [MIT](https://spdx.org/licenses/MIT.html)
- [libucl](https://github.com/vstakhov/libucl) - Universal configuration library parser. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [libxo](https://github.com/Juniper/libxo) - Allows an application to generate plain text, XML, JSON and HTML output using a common set of function calls. The application decides at runtime what output style should be produced. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)

### XML

- [Expat](http://expat.sourceforge.net/) - Stream-oriented XML parser. [MIT](https://spdx.org/licenses/MIT.html)
- [libxml2](http://xmlsoft.org/) - Standards-compliant, portable XML parser. [MIT](https://spdx.org/licenses/MIT.html)
- [xml](https://github.com/recp/xml) - Simple, low-memory-use XML parser / tokenizer. [MIT](https://spdx.org/licenses/MIT.html)

### YAML

- [libYAML](https://www.pyyaml.org/wiki/LibYAML) - YAML 1.1 parser and emitter. [MIT](https://spdx.org/licenses/MIT.html)

## Signal Processing

- [libsigrok](https://sigrok.org/wiki/Libsigrok) - signal analysis software suite that supports various device types (such as logic analyzers, oscilloscopes, multimeters, and more). [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)

## Testing

- [CHEAT](https://github.com/Tuplanolla/cheat) - Simple unit testing framework. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [Check](https://libcheck.github.io/check) - Unit testing framework. [LGPL-2.1-only](https://spdx.org/licenses/LGPL-2.1-only.html)
- [ciut](https://github.com/yhfudev/cpp-ci-unit-test.git) - A modern minimal hassle unit test framework. [MIT](https://spdx.org/licenses/MIT.html)
- [clar](https://github.com/vmg/clar) - Clear and simple unit testing framework. [MIT](https://spdx.org/licenses/MIT.html)
- [CMock](http://www.throwtheswitch.org/cmock) - Mock/stub generator. [MIT](https://spdx.org/licenses/MIT.html)
- [cmocka](https://cmocka.org/) - Unit testing framework with support for mock objects. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [Criterion](https://criterion.readthedocs.io/en/master) - KISS, non-intrusive test framework. [MIT](https://spdx.org/licenses/MIT.html)
- [ctest](https://github.com/bvdberg/ctest) - Yet another unit testing framework. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [CUnit](http://cunit.sourceforge.net/) - Another unit testing framework. [LGPL-2.1-or-later](https://spdx.org/licenses/LGPL-2.1-or-later.html)
- [greatest](https://github.com/silentbicycle/greatest) - Unit testing library in one file, with no memory allocation. [ISC](https://spdx.org/licenses/ISC.html)
- [minctest](https://github.com/codeplea/minctest) - Unit testing microlibrary. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [munit](https://nemequ.github.io/munit) - Small unit testing framework. [MIT](https://spdx.org/licenses/MIT.html)
- [Nala](https://github.com/eerimoq/nala) - A test framework for C projects. [MIT](https://spdx.org/licenses/MIT.html)
- [Owi](https://github.com/OCamlPro/owi) - A bug-finding tool built on symbolic execution ([paper](https://hal.science/hal-04627413)) [AGPL-3.0-or-later](https://spdx.org/licenses/AGPL-3.0-or-later.html)
- [Rexo](https://github.com/christophercrouzet/rexo) - Framework for C89/C++ featuring automatic registration of tests and a polished API. [Unlicense](https://spdx.org/licenses/Unlicense.html)
- [Tau](https://github.com/jasmcaus/tau) - A Micro Unit testing framework for C/C++ (~1k lines of code). Includes a rich set of assertion macros, supports automatic test registration and can output to multiple formats, like the TAP format or JUnit XML. Supported on Linux, macOS, FreeBSD, and Windows. [MIT](https://spdx.org/licenses/MIT.html)
- [theft](https://github.com/silentbicycle/theft) - Property-based testing (similar to [Quickcheck](https://wiki.haskell.org/Introduction_to_QuickCheck2)). [MIT](https://spdx.org/licenses/MIT.html)
- [Unity](http://www.throwtheswitch.org/unity) - Simple unit testing framework. [MIT](https://spdx.org/licenses/MIT.html)
- [utest](https://github.com/evolutional/utest) - Single-header unit testing library. [Unlicense](https://spdx.org/licenses/Unlicense.html)

## Tools

Useful programs to help you write and debug C code which are not editors, libraries or compilers.

- [Artistic Style](http://astyle.sourceforge.net/) - Fast and small automatic source code formatter that supports C. [LGPL-3.0-only](https://spdx.org/licenses/LGPL-3.0-only.html)
- [address-sanitizer](https://github.com/google/sanitizers) - Fast memory error detector. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [bcc](https://projects.malikania.fr/bcc) - A byte array generator to import binary files directy from C in the spirit of xxd. [ISC](https://spdx.org/licenses/ISC.html)
- [c](https://github.com/ryanmjacobs/c) - Compile and execute C "scripts" in one go on the command line. Also has shebang support. [MIT](https://spdx.org/licenses/MIT.html)
- [c99sh](https://github.com/RhysU/c99sh) - Run C files using hash-bang. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [cdecl](https://cdecl.org/) - Online service to translate C declarations into English and vice versa. Public domain.
- [cinclude2dot](https://www.flourish.org/cinclude2dot/) - Graphs include dependencies in a project using Graphviz. [GPL-1.0-or-later](https://spdx.org/licenses/GPL-1.0.html) or [GPL-2.0-or-later](https://spdx.org/licenses/GPL-2.0-or-later.html) or [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [ClangCheck](https://clang.llvm.org/docs/ClangCheck.html) - Static analysis tool, designed to work with Clang. [Apache License v2.0 with LLVM Exceptions](https://llvm.org/LICENSE.txt)
- [clangd](https://clangd.llvm.org/) - clangd is a language server that can work with many editors via a plugin. clangd understands your C++ code and adds smart features to your editor: code completion, compile errors, go-to-definition and more. [Apache License v2.0 with LLVM Exceptions](https://llvm.org/LICENSE.txt)
- [cc-wrapper](https://github.com/eranif/cc-wrapper) - A small wrapper around CC (gcc or clang) to capture, log and generate compile_commands.json file. [MIT](https://spdx.org/licenses/MIT.html).
- [Bear](https://github.com/rizsotto/Bear) - Bear is a tool that generates a compilation database for clang tooling. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [conan.io](https://conan.io/) - Something of a package manager for C. [MIT](https://spdx.org/licenses/MIT.html).
- [Cppcheck](http://cppcheck.sourceforge.net/) - Static analysis tool. Despite the name, works well with C. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [Glade](https://glade.gnome.org/) - RAD tool to enable quick development of GTK+ GUIs. [GPL-2.0-only](https://spdx.org/licenses/GPL-2.0-only.html)
- [GMSL](https://gmsl.sourceforge.net/) - GNU Make Standard Library; a collection of additional functionality for GNU Make. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [GNU Global](https://www.gnu.org/software/global/) - Source code tagging tool. [GPL-3.0-only](https://spdx.org/licenses/GPL-3.0-only.html)
- [GPP](https://logological.org/gpp) - General-purpose preprocessor. More versatile than the C preprocessor, but more flexible than m4. [LGPL-3.0-or-later](https://spdx.org/licenses/LGPL-3.0-or-later.html)
- [Highlight](http://www.andre-simon.de/index.php) - Converts source code to formatted text with nice highlighting. [GPL-3.0-only](https://spdx.org/licenses/GPL-3.0-only.html)
- [include-what-you-use](https://github.com/include-what-you-use/include-what-you-use) - Helps find unecessary inclusions and make suggestions for fixing them. Based on LLVM/Clang (and only works with it). [NCSA](https://spdx.org/licenses/NCSA.html)
- [incbin](https://github.com/graphitemaster/incbin) - Include binary files in your C/C++ applications with ease [Unlicense](https://spdx.org/licenses/Unlicense.html)
- [indent](https://www.gnu.org/software/indent/) - Formats C source code automatically to make it easier to read. Also converts from one style of source to another. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [SMACK](https://github.com/smackers/smack) - Modular software verification toolchain and a self-contained software verifier. Currently only works with programs compiled using Clang. [MIT](https://spdx.org/licenses/MIT.html)
- [unifdef](http://dotat.at/prog/unifdef/) - Removes #ifdef and #if directives with their delimited text without touching any other part of the file. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html) or [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)

## Utilities

A 'catch-all' category for anything that doesn't fit well anywhere else.

- [ApeTagLibs](https://github.com/jeremyevans/ape_tag_libs/tree/master/c) - Library for working with APEv2 tags. [MIT](https://spdx.org/licenses/MIT.html)
- [argparse](https://github.com/cofyc/argparse) - Command-line argument parsing library, inspired by Python's argparse module. [MIT](https://spdx.org/licenses/MIT.html)
- [attr](http://savannah.nongnu.org/projects/attr/) - Commands for manipulating filesystem extended attributes. [GPL-2.0-or-later](https://spdx.org/licenses/GPL-2.0-or-later.html)
- [bfd](http://sourceware.org/binutils/docs/bfd/) - Library for manipulating binary object files. Part of GNU binutils. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [Caffeine](https://github.com/dmw/caffeine) - Library for building daemons and services for Linux and FreeBSD systems. [LGPL-2.1-or-later](https://spdx.org/licenses/LGPL-2.1-or-later.html)
- [CException](http://www.throwtheswitch.org/cexception) - Implementation of exceptions. [MIT](https://spdx.org/licenses/MIT.html)
- [CommonMark](https://github.com/commonmark/commonmark-spec) - Implementation of the CommonMark spec. [CC-BY-SA-4.0](https://spdx.org/licenses/CC-BY-SA-4.0.html)
- [cosmopolitan](https://github.com/jart/cosmopolitan) - fast portable static native textmode containers (build C programs for Linux\\Mac\\Windows in one go). [Various licenses, all open source](https://github.com/commonmark/commonmark-spec/blob/master/LICENSE).
- [cpu_features](https://github.com/google/cpu_features) - Get CPU features at runtime. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html).
- [CRIU](https://criu.org/Main_Page) - Checkpoint/Restore In Userspace; a software tool (with a C API) for 'freezing' a running application to disk, then restoring it. [GPL-2.0-only](https://spdx.org/licenses/GPL-2.0-only.html) or [LGPL-2.1-only](https://spdx.org/licenses/LGPL-2.1-only.html)
- [D-Bus](https://www.freedesktop.org/wiki/Software/dbus/) - Simple way for applications to talk to one another. [AFL-2.1](https://spdx.org/licenses/AFL-2.1.html) or [GPL-2.0-or-later](https://spdx.org/licenses/GPL-2.0-or-later.html)
- [Discount](http://www.pell.portland.or.us/~orc/Code/discount/) - Simple implementation of a Markdown parser. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [dlx](https://github.com/blynn/dlx) - Implementation of [Knuth's Algorithm X](https://en.wikipedia.org/wiki/Knuth's_Algorithm_X), with example solvers. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [docopt.c](https://github.com/docopt/docopt.c) - Implementation of a command-line option parser. [MIT](https://spdx.org/licenses/MIT.html)
- [dyncall](http://www.dyncall.org/) - Another foreign function interface library. [MIT](https://spdx.org/licenses/MIT.html)
- [GNU FreeIPMI](https://gnu.org/software/freeipmi/index.html) - In-band and out-of-band IPMI implementation. [GPL-3.0-only](https://spdx.org/licenses/GPL-3.0-only.html)
- [GNU gperf](https://www.gnu.org/software/gperf/) - Perfect hash function generator, given a list of strings. Outputs C code. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [GNU Libffcall](https://gnu.org/software/libffcall/) - Collection of libraries for building foreign function interfaces. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [Hoedown](https://github.com/hoedown/hoedown) - Fully standards-compliant, extension-supporting, UTF-8 aware, fast Markdown parser. [MIT](https://spdx.org/licenses/MIT.html)
- [Kitsune](http://kitsune-dsu.com/) - Efficient, general-purpose framework for dynamic software updating. [LGPL-3.0-or-later](https://spdx.org/licenses/LGPL-3.0-or-later.html)
- [libCello](http://libcello.org/) - Library introducing higher-level programming to C. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [libcmark](https://github.com/jgm/cmark) - Library for parsing the CommonMark dialect of Markdown. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [libcoap](https://github.com/obgm/libcoap) - Implementation of the [Constrained Application Protocol](https://coap.space/). [GPL-2.0-or-later](https://spdx.org/licenses/GPL-2.0-or-later.html) or [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [libcox](http://libcox.symisc.net/) - Library which permits cross-platform system calls and standard utilities across different operating systems. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [libffi](https://github.com/atgreen/libffi) - Portable foreign-function interface library. [MIT](https://spdx.org/licenses/MIT.html)
- [libgeohash](https://github.com/simplegeo/libgeohash) - Pure C implementation of the Geohash algorithm. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [libgit2](https://libgit2.org/) - Portable implementation of the Git core methods, provided as a re-entrant linkable library. [Custom license](https://github.com/libgit2/libgit2/blob/master/COPYING).
- [libgss](https://gnu.org/software/gss/) - Generic Security Service. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [libimobiledevice](https://github.com/libimobiledevice/libimobiledevice) - Cross-platform protocol library to communicate with iThings. [LGPL-2.1-or-later](https://spdx.org/licenses/LGPL-2.1-or-later.html)
- [libnfc](https://github.com/nfc-tools/libnfc) - Platform-independent Near-Field Communication library. [LGPL-3.0-only](https://spdx.org/licenses/LGPL-3.0-only.html)
- [libpostal](https://github.com/openvenues/libpostal) - Library for parsing and normalization of street addresses around the world. Powered by statistical NLP and open geo data. [MIT](https://spdx.org/licenses/MIT.html)
- [libtrading](http://libtrading.org/) - Implementation of network protocols for communicating with exchanges, dark pools and other trading venues. Supports FIX, FIX/FAST and many proprietary protocols. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [libusb](https://libusb.info/) - Provides generic access to USB devices. [LGPL-2.1-or-later](https://spdx.org/licenses/LGPL-2.1-or-later.html)
- [libuv](http://libuv.org) - Cross-platform asynchronous I/O. [MIT](https://spdx.org/licenses/MIT.html)
- [libvldmail](https://github.com/dertuxmalwieder/libvldmail) - Your friendly email validation library. No external dependencies (not even regexps). [WTFPL](https://spdx.org/licenses/WTFPL.html)
- [linenoise](https://github.com/antirez/linenoise) - Small, self-contained alternative to readline and libedit. [BSD-2-Clause](https://spdx.org/licenses/BSD-2-Clause.html)
- [libXDGdirs](https://github.com/Jorengarenar/libXDGdirs) - An implementation of XDG Base Directory Specification [MIT](https://spdx.org/licenses/MIT.html)
- [MegaMimes](https://kobbyowen.github.io/MegaMimes) - Library for getting the [MIME](https://en.wikipedia.org/wiki/MIME) types of a file. [MIT](https://spdx.org/licenses/MIT.html)
- [ncurses](https://gnu.org/software/ncurses/) - Coloured terminal UI library. [MIT](https://spdx.org/licenses/MIT.html)
- [netbsd-curses](https://github.com/sabotage-linux/netbsd-curses) - Simplified and small version of ncurses, with the same interface. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [nope.c](https://github.com/riolet/WAFer) - Ultra-light software platform for scalable server-side and networking applications (think node.js for C programmers). [GPL-2.0-only](https://spdx.org/licenses/GPL-2.0-only.html)
- [obj.h](https://github.com/small-c/obj.h) - A single-header supports OOP in pure C. [MIT](https://spdx.org/licenses/MIT.html)
- [OOC](https://ooc-coding.sourceforge.net/) - Object Oriented C (oo tools for C) kit is for those who want to program in an object oriented manner, but stick on the good old C as well. [LGPL-3.0-or-later](https://spdx.org/licenses/LGPL-3.0-or-later.html)
- [PLOOC](https://github.com/GorgonMeducer/PLOOC) - Protected Low-overhead Object Oriented Programming with ANSI-C. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [COS](https://github.com/CObjectSystem/COS) - C Object System: a framework that brings C to the level of other high level programming languages and beyond. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [parg](https://github.com/jibsen/parg) - A single-file reimplementation of getopt with better defaults. [CC0-1.0](https://spdx.org/licenses/CC0-1.0.html)
- [pbc](https://github.com/cloudwu/pbc) - Protocol buffers library. [MIT](https://spdx.org/licenses/MIT.html)
- [progressbar](https://github.com/doches/progressbar) - Easy-to-use library for displaying text progress bars. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [rabbitmq-c](https://github.com/alanxz/rabbitmq-c) - Client library for [RabbitMQ](http://www.rabbitmq.com/). [MIT](https://spdx.org/licenses/MIT.html)
- [Ragel](http://www.colm.net/open-source/ragel/) - DSL for state machines that compiles to C. [GPL-2.0-only](https://spdx.org/licenses/GPL-2.0-only.html)
- [rmw](https://remove-to-waste.info) - safe-remove utility for the command line that can purge items from your waste directories after x number of days. [GPL-3.0-or-later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- [Rogueutil](https://github.com/sakhmatd/rogueutil) - Cross-platform library for creating text-based user interfaces (TUI) [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [sort](https://github.com/swenson/sort) - Collection of sorting routines, which type-specialize at compile-time with a user-defined type. [MIT](https://spdx.org/licenses/MIT.html)
- [termbox](https://github.com/nsf/termbox) - Library for writing text-based interfaces. [MIT](https://spdx.org/licenses/MIT.html)
- [termbox2](https://github.com/termbox/termbox2) - terminal I/O library for creating TUIs. [MIT](https://spdx.org/licenses/MIT.html)
- [tinyexpr](https://github.com/codeplea/tinyexpr) - Tiny recursive-descent parser, compiler and evaluation engine for simple mathematical expressions. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [tm](https://github.com/recp/tm) - ⏱ Timer and Timeline Utils for C. [MIT](https://spdx.org/licenses/MIT.html)
- [Tulip Indicators](https://tulipindicators.org/) - Library of functions for technical analysis of financial data. [LGPL-3.0-or-later](https://spdx.org/licenses/LGPL-3.0-or-later.html)
- [whereami](https://github.com/gpakosz/whereami) - One-file library for locating the current executable on the file system. [WTFPL](https://spdx.org/licenses/WTFPL.html)
- [XLSX I/O](https://brechtsanders.github.io/xlsxio/) - Cross-platform library for reading and writing .xlsx files. [MIT](https://spdx.org/licenses/MIT.html)
- [xlsx_drone](https://github.com/damian-m-g/xlsx_drone) - Fast Microsoft Excel's .xlsx reader. [MIT](https://spdx.org/licenses/MIT.html)
- [zlog](http://hardysimpson.github.io/zlog/) - Reliable, pure C logging library. [LGPL-2.1-only](https://spdx.org/licenses/LGPL-2.1-only.html)
- [zproto](https://github.com/zeromq/zproto) - Protocol framework for ZeroMQ. [MIT](https://spdx.org/licenses/MIT.html)
- [Metalang99](https://github.com/Hirrolot/metalang99) - Full-blown preprocessor metaprogramming. [MIT](https://spdx.org/licenses/MIT.html)
- [Datatype99](https://github.com/Hirrolot/datatype99) - Algebraic data types for C99. [MIT](https://spdx.org/licenses/MIT.html)
- [EasyLogger](https://github.com/armink/EasyLogger) - An ultra-lightweight, high-performance C/C++ log library. [MIT](https://spdx.org/licenses/MIT.html)
- [microlog](https://github.com/an-dr/microlog) - Extensible and configurable logging library with topics for embedded and desktop [MIT](https://spdx.org/licenses/MIT.html)
- [MetaCall](https://github.com/metacall/core) - A library for providing inter-language foreign function interface calls. [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
- [subprocess.h](https://github.com/sheredom/subprocess.h) - 🐜 single header process launching solution for C and C++ [Unlicense](https://spdx.org/licenses/Unlicense.html)

## Web Frameworks

Comprehensive and integrated solutions for building the next brilliant web application in C.

- [Concord](https://github.com/Cogmasters/concord) - A Discord API wrapper library written in C. [MIT](https://spdx.org/licenses/MIT.html)
- [facil.io](http://facil.io/) - Mini-framework for web applications. Includes a fast HTTP and Websocket server, and also supports custom protocols. [MIT](https://spdx.org/licenses/MIT.html)
- [kcgi](https://kristaps.bsd.lv/kcgi) - CGI and FastCGI library for C [ISC](https://spdx.org/licenses/ISC.html).
- [KLone](http://www.koanlogic.com/klone/) - Fully featured, multi-platform, web application development framework, targeted especially at embedded systems and appliances. [BSD-3-Clause](https://spdx.org/licenses/BSD-3-Clause.html)
- [Kore](https://kore.io/) - Easy-to-use web application framework for writing scalable web APIs in C. [ISC](https://spdx.org/licenses/ISC.html)

## Windows Environments

Technologies designed to bring Windows into the 21st century with respect to support for C.

- [Cygwin](https://cygwin.com/) - Designed to emulate a POSIX-compatible environment extensively under Windows. [Various licenses, all open source](https://cygwin.com/licensing.html).
- [MinGW-w64](https://www.mingw-w64.org/) - Minimalist environment for C development on Windows with 64 bit support. Various licenses, all open source.
- [MSYS2](http://msys2.github.io/) - Minimal SYStem 2; aims to provide support for a POSIX environment on Windows, with a package manager based on Arch Linux's pacman. Packages have individual licenses, otherwise, as MinGW and Cygwin.
- [w64devkit](https://github.com/skeeto/w64devkit) - Portable C and C++ Development Kit for x64 (and x86) Windows. [busybox-w32](https://github.com/rmyorston/busybox-w32) is [GPL-2.0-only](https://spdx.org/licenses/GPL-2.0-only.html). [pdpmake](https://github.com/rmyorston/pdpmake) is Public Domain. w64devkit itself is [Unlicense](https://spdx.org/licenses/Unlicense.html). Note: default Make implementation is GNU Make.

[AFL-2.1]: https://spdx.org/licenses/AFL-2.1.html
[AGPL-3.0-only]: https://spdx.org/licenses/AGPL-3.0-only.html
[AGPL-3.0-or-later]: https://spdx.org/licenses/AGPL-3.0-or-later.html
[Apache-2.0]: https://spdx.org/licenses/Apache-2.0.html
[BSD-1-Clause]: https://spdx.org/licenses/BSD-1-Clause.html
[BSD-2-Clause]: https://spdx.org/licenses/BSD-2-Clause.html
[BSD-3-Clause]: https://spdx.org/licenses/BSD-3-Clause.html
[BSD-4-Clause]: https://spdx.org/licenses/BSD-4-Clause.html
[CC0-1.0]: https://spdx.org/licenses/CC0-1.0.html
[CC-BY-SA-4.0]: https://spdx.org/licenses/CC-BY-SA-4.0.html
[curl]: https://spdx.org/licenses/curl.html
[GPL-2.0-only]: https://spdx.org/licenses/GPL-2.0-only.html
[GPL-2.0-or-later]: https://spdx.org/licenses/GPL-2.0-or-later.html
[GPL-3.0-only]: https://spdx.org/licenses/GPL-3.0-only.html
[GPL-3.0-or-later]: https://spdx.org/licenses/GPL-3.0-or-later.html
[ICU]: https://spdx.org/licenses/ICU.html
[ISC]: https://spdx.org/licenses/ISC.html
[LGPL-2.0-or-later]: https://spdx.org/licenses/LGPL-2.0-or-later.html
[LGPL-2.1-only]: https://spdx.org/licenses/LGPL-2.1-only.html
[LGPL-2.1-or-later]: https://spdx.org/licenses/LGPL-2.1-or-later.html
[LGPL-3.0-only]: https://spdx.org/licenses/LGPL-3.0-only.html
[LGPL-3.0-or-later]: https://spdx.org/licenses/LGPL-3.0-or-later.html
[Libpng]: https://spdx.org/licenses/Libpng.html
[MIT]: https://spdx.org/licenses/MIT.html
[MIT-0]: https://spdx.org/licenses/MIT-0.html
[MPL-2.0]: https://spdx.org/licenses/MPL-2.0.html
[NCSA]: https://spdx.org/licenses/NCSA.html
[OLDAP-2.8]: https://spdx.org/licenses/OLDAP-2.8.html
[PostgreSQL]: https://spdx.org/licenses/PostgreSQL.html
[TCL]: https://spdx.org/licenses/TCL.html
[Unlicense]: https://spdx.org/licenses/Unlicense.html
[WTFPL]: https://spdx.org/licenses/WTFPL.html
[X11]: https://spdx.org/licenses/X11.html
[Zlib]: https://spdx.org/licenses/Zlib.html
