# How does text turn into an executable file?
- ### Preprocessor Statements
  - These are statements that begin with a hash (#).
  - They are evaluated before the compiler starts looking at the actual code.
  - The most common is ```#include file```. The compiler deals with this by copying the contents of the given file directly into the .cpp file.

- ### Compilation
  - Header files are not compiled at all, the contents are compiled when they are included (copied) into a .cpp file.
  - .cpp files are compiled into .obj files.

- ### Linking
  - The linker takes all the .obj files, which were previously compiled, then stitches them into a .exe file.

## Definitions vs Declarations
Declarations show the compiler that an object _exists_.  Definitions explain what that object is. If an object (function or class) is not _declared_, there will be a compiler error. If the declaration exists but the object is not _defined_, there will be a linker error.

source video: <https://www.youtube.com/watch?v=SfGuIVzE_Os&list=PLlrATfBNZ98dudnM48yfGUldqGD0S4FFb&index=5>.
