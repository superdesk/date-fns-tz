# About

Fork was created because original library couldn't be used with out webpack 4 setup.

1. There were issues with nullish coalescing, but that could have been solved by piping it through ts-loader.
2. Main issue was compilation of classes to ES5. It was not working when webpack was compiling it, but worked with babel here.

# Publishing new versions

1. Change code
2. Run `make build`
3. Navigate to `lib` and run `npm publish` from inside the directory

# What was changed

* Package name
* babel plugin added to compile classes to ES5
* babel plugin added to compile optional chaining to ES5
* version bumped to v1.2.1 due to a mistake when publishing the original v1.2.0