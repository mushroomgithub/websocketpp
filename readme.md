WebSocket++ (0.6.0)（WebSocket 的 C++ 开发包 websocket++）
==========================

WebSocket++ is a header only C++ library that implements RFC6455 The WebSocket
Protocol. It allows integrating WebSocket client and server functionality into
C++ programs. It uses interchangeable network transport modules including one
based on raw char buffers, one based on C++ iostreams, and one based on Asio 
(either via Boost or standalone). End users can write additional transport
policies to support other networking or event libraries as needed.

WebSocket++ 是一个只包含 C++ 头文件的 WebSocket 的 C++ 开发包，实现了 RFC 6455 也就是 WebSocket 协议。可以在 C++ 应用中实现 WebSocket 客户端和服务器端功能。使用可交换的网络传输模块，包括 C++ iostreams 和 Boost Asio。

Major Features
==============
* Full support for RFC6455
* Partial support for Hixie 76 / Hybi 00, 07-17 draft specs (server only)
* Message/event based interface
* Supports secure WebSockets (TLS), IPv6, and explicit proxies.
* Flexible dependency management (C++11 Standard Library or Boost)
* Interchangeable network transport modules (raw, iostream, Asio, or custom)
* Portable/cross platform (Posix/Windows, 32/64bit, Intel/ARM/PPC)
* Thread-safe

Get Involved
============

[![Build Status](https://travis-ci.org/zaphoyd/websocketpp.png)](https://travis-ci.org/zaphoyd/websocketpp)

**Project Website**
http://www.zaphoyd.com/websocketpp/

**User Manual**
http://www.zaphoyd.com/websocketpp/manual/

**GitHub Repository**
https://github.com/zaphoyd/websocketpp/

GitHub pull requests should be submitted to the `develop` branch.

**Announcements Mailing List**
http://groups.google.com/group/websocketpp-announcements/

**IRC Channel**
 #websocketpp (freenode)

**Discussion / Development / Support Mailing List / Forum**
http://groups.google.com/group/websocketpp/

Author
======
Peter Thorson - websocketpp@zaphoyd.com
