# OSI model vs. TCP/IP model

In the TCP/IP model, the four layers are

* 4\. Application layer: This corresponds, approximately, to layer 7 in the OSI model.
* 3\. Transport layer: Corresponds to layer 4 in the OSI model.
* 2\. Internet layer: Corresponds to layer 3 in the OSI model.
* 1\. Network access layer: Combines the processes of layers 1 and 2 in the OSI model.

\
But where are OSI layers 5 and 6 in the TCP/IP model? Some sources hold that the processes at OSI layers 5 and 6 either are no longer necessary in the modern Internet, or actually belong to [layers 7](https://www.cloudflare.com/learning/ddos/what-is-layer-7/) and 4 (represented by layers 4 and 3 in the TCP/IP model).

\
For instance, since the TCP protocol opens and maintains sessions at OSI layer 4, one could consider OSI layer 5 (the "session" layer) to be unnecessary — and it is not represented in the TCP/IP model. Additionally, HTTPS encryption and decryption can be considered an application layer (OSI layer 7 or TCP/IP layer 4) process instead of a presentation layer (OSI layer 6) process.



