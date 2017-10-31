# Thread Safe

Thread Safe is a collection of simple thread safe classes that can be used when developing applications in C++.

Currently it contains the following classes:
* **SafeQueue**: Simple queue that can be used to pass data between threads.

## Installation

Currently the library only consists of a single header file. It just needs to be copied to `/usr/local/include`.

```shell
sudo su
cd /usr/local/src
git clone https://github.com/BioBoost/thread_safe.git
cp -r thread_safe/include/thread_safe /usr/local/include
```
