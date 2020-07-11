Requirements
=============

- Linux, Windows, or OS X
- Rust 1.36 or later
- [SFML 2.5](http://www.sfml-dev.org/download.php)
- [CSFML 2.5](http://www.sfml-dev.org/download/csfml/)

Setup
=====
### Build your project
- Copy the *.dll files from CSFML\bin to the working directory of your compiled executable (usually target\debug or target\release)
- Note: You only need to copy the *.dll files that correspond to the rust-sfml modules you are using. e.g. copy csfml-graphics-2.dll if your code contains using sfml::graphics.