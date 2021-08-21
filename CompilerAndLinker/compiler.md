Compilation is a very complicated process and it was not fully covered in the scope of the video. I researched some [very basic additonal information](https://www.bbc.co.uk/bitesize/guides/zmthsrd/revision/3) to supplement the contents of the video.

# Steps of compilation
- ## Preprocessing
  - The compiler goes through the code and expands any preprocessor statements
  - This step involves handling `#include file`, `#define MACRO value`, `#pragma`, and more
  - `#include` statements are handled by directly copying the contents of the included file into the source file
  - To demonstrate this, this example given in the video compiles without any errors: 
    ```cpp
    // end_brace.cpp
    }

    // main.cpp
    void main() {
      // some action
    #include end_brace.cpp
    ```
    
- ## Tokenization
  - Converts the text in the source file to 'tokens' which identify what elements are

- ## Syntax Analysis
  - Checks the syntax of the source file and creats an *abstract syntax tree* (need to look up)

- ## Code generation and opimization
  - The compiler generates assmebly code and then optimizes it to reduce unnecessary operations
  - Optimization has a **huge** effect on the size of the resulting assembly code

Obviously, the compiler is much more complicated than this and has many more steps but that is outside of my scope for now.


[Reference Video](https://www.youtube.com/watch?v=3tIqpEmWMLI&list=PLlrATfBNZ98dudnM48yfGUldqGD0S4FFb&index=6&ab_channel=TheCherno).
