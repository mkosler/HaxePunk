# HaxePunk
A HaXe port of the FlashPunk AS3 library.

Make sure you have Haxe 2.07 or above to compile. Using FlashDevelop is
probably the easiest way to build HaxePunk but you can use the command line
tools in the following way. You will also need SWFMill installed.

### Command Line Compiler Instructions
cd HaxePunk
swfmill simple assets.xml assets.swf
haxe compile.hxml
bin/game.swf