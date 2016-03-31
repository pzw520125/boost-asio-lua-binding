# boost asio lua binding

A tcp client implementated by boost.asio and binded to lua.

The original purpose is to develop a game with cocos2d-x and lua.


# buid

Set the environment variable BOOST\_HOME=path/to/boost

and build boost libs to $(BOOST\_HOME)/stage/lib

# proto
first 4 bit is then content length, then the content.

you and run `github:shinexia/netty-server`: `io.xgh.netty.demo.simple.DemoServer` as the test server.

# Notes

because io\_service is in the different thread to the lua interpretor, i commented out the callbacks.

in cocos2d-x, you can deal with this by `cocos2d::Director::getInstance()->getScheduler()->performFunctionInCocosThread`

# More

<http://xgh.io/blog/boost-asio-lua-binding>
