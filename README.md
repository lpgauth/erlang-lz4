erlang-lz4
==========

> **Archived (lpgauth fork).** Superseded by
> [**lz4_nif**](https://github.com/lpgauth/lz4_nif), a clean-room
> rewrite published to hex.pm. lz4_nif vendors upstream `lz4 v1.10.0`,
> exposes the same `compress/1,2` / `uncompress/2` API, adds dirty
> CPU scheduler dispatch + `enif_consume_timeslice` accounting, and
> builds correctly on macOS aarch64 (the original motivation for this
> fork). See [szktty/erlang-lz4](https://github.com/szktty/erlang-lz4)
> for the upstream original.

branch: master [![Build Status](https://secure.travis-ci.org/szktty/erlang-lz4.png?branch=master)](http://travis-ci.org/szktty/erlang-lz4)
develop [![Build Status](https://secure.travis-ci.org/szktty/erlang-lz4.png?branch=develop)](http://travis-ci.org/szktty/erlang-lz4)

LZ4 bindings for Erlang

This library uses source code of LZ4 from https://github.com/Cyan4973/lz4.


LZ4 implementation version
--------------------------

https://github.com/Cyan4973/lz4/releases/tag/r119


Licenses
--------

This program is distributed under Apache License 2.0.

LZ4 library is distributed under New BSD License.


Author
------

SUZUKI Tetsuya <tetsuya.suzuki@gmail.com>

