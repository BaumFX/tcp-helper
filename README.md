# tcp helper

a simple library to help handle tcp connections on the server.

### usage

simply create a class that inherits the tcp_listener class from tcp_listener.h... you can then proceed to override the 3 functions on_client_connected(),
on_client_disconnected() and on_message_received(). these get called at each event.

check my demo project [cppwebserver](https://github.com/BaumFX/cppwebserver) for an example on what you could do.

## contributing

if you have any contributions just make a pull request or an issue thanks

## versioning

no need to update something thats perfect :sunglasses:

## authors

* **Robert 'BaumFX'** - *initial work* - [website](https://baumfx.xyz) - [GitHub](https://github.com/BaumFX)

## license

dont say you made it, okay?

## acknowledgements

* Mr. Sloan Kelly on YouTube for his tutorials on c++ networking
