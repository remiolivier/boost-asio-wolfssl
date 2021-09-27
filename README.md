# boost-asio-wolfssl
A WolfSSL wrapper for boost asio

## Usage

Add `include` as include directory for your project and link against WolfSSL instead of OpenSSL.

Use the header:
```cpp
#include <boost/asio/wolfssl.hpp>
```

Instead of:
```cpp
#include <boost/asio/ssl.hpp>
```