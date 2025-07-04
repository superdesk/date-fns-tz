# About

Fork was created because original library couldn't be used with out webpack 4 setup.

1. There were issues with nullish coalescing, but that could have been solved by piping it through ts-loader.
2. Main issue was compilation of classes to ES5. It was not working when webpack was compiling it, but worked with babel here.

# What was changed

* Package name
* babel plugin added to compile classes to ES5
* babel plugin added to compile optional chaining to ES5