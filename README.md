Just a fork of [node-cbor](https://github.com/hildjj/node-cbor), modified so that it doesn't do anything with BigInts when its loaded.  

This solves a problem for me where this library did not work in an application where it was bundled into an iOS app that wants to support older devices without BigInt support.

That is all.
