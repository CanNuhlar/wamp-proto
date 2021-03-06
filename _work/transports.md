-- this should probably move to the main document --

# Alternative Transports

As mentioned in the [Basic Profile](basic.md), the only requirements that WAMP expects from a transport are: the transport must be message-based, bidirectional, reliable and ordered. This allows WAMP to run over different transports without any impact at the application layer.

Besides the WebSocket transport, the following WAMP transports are currently specified:

* [RawSocket Transport](rawsocket-transport.md)
* [Batched WebSocket Transport](batched-websocket-transport.md)
* [LongPoll Transport](longpoll-transport.md)
* [Multiplexed Transport](multiplexed-transport.md)

> Other transports such as HTTP 2.0 ("SPDY") or UDP might be defined in the future.
