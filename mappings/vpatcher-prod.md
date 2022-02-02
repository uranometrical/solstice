# vpatcher-prod
**(Status: core classes fully remapped, libraries partially mapped)**
---
`vpatcherprod` is a program shipped with all versions of Lunar Client, and manages launching the game. It contains a custom `URLClassLoader` and applies OptiFine XDelta patches, and manages `.lclass` class files. It also validates numerous hashes if needed.

## Resources
Currently known packaged libraries:
* https://github.com/lightbend/config/
  * This is the library `vpatcher-prod` uses to parse HOCON config files.
* https://github.com/apache/commons-compress (Likely)
* https://github.com/google/gson (Likely)
 * Seems to be fragmented, likely just classes taken from some other library.
* https://github.com/mantlik/xdeltaencoder/tree/master/src/main/java/com/nothome/delta
 * The library used to apply OptiFine XDelta patches.
* https://github.com/malensek/jbsdiff
 * Seems to be fragmented alongside `gson`, requires some looking into.
