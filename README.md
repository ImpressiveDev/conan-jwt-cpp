## Conan Jwt-Cpp Package

A Conan package recipe for [jwt-cpp](https://github.com/pokowaka/jwt-cpp).

The recipe was forked from: https://github.com/bincrafters/conan-templates.

### To Build Package

```bash
conan create . impressivedev/stable
```

### Notes

This repository is still a work in progress. Hopefully, the [jwt-cpp](https://github.com/pokowaka/jwt-cpp) creator will
publish [his own Conan package](https://github.com/pokowaka/jwt-cpp/issues/22). Nothing has been published on bintray.com.

Test targets compilation has been disabled for now.

This package compiles a version a bit further in history than the 1.0 tag of the
[jwt-cpp repository](https://github.com/pokowaka/jwt-cpp), in order to be able to disable the test targets compilation.
