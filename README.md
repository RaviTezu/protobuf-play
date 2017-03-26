# protobuf-play
Playing with Google's protocol buffers

GoLang Tutorial: https://developers.google.com/protocol-buffers/docs/gotutorial

# Installing on Ubuntu: 
 - `git clone git@github.com:google/protobuf.git`
 - `sudo apt-get install autoconf automake libtool curl make g++ unzip`
 - `cd protobuf`
 - `./autogen.sh`
 - `./configure`
 - `make`
 - `make check`
 - `sudo make install`
 - `sudo ldconfig` # To refresh shared library cache.