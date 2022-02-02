# mappings
This is the root directory containing subdirectories for different projects. Any project that has multiple versions will have further subdirectories that split them up appropriately.

A class that contains a fully-qualified package (i.e. `dev.tomat.myproject.MyClass` as opposed to `MyClass`) indicates that a class has been either fully remapped or remapped enough to understand its functionality.

For smaller programs, such as `vpatcher-prod`, which have libraries included in the raw `.jar` file (and, in turn, are obfuscated alongside the actual project), most third-party libraries will remain obfuscated (unless partially unobfuscating it will aid in readability of the core code). The current focus is for the actual relevant pieces of a project to be remapped. Feel free to PR further remappings for libraries if you'd like.

For more information regarding different projects, view the appropriately-named markdown files included in this directory.
