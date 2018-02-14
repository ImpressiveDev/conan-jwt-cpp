## Conan Jwt-Cpp Package Builder

A Conan package recipe for the [jwt-cpp](https://github.com/pokowaka/jwt-cpp) library.

The recipe was forked from the [Bincrafters Conan Templates](https://github.com/bincrafters/conan-templates) recipe.

## To Build Package

```bash
conan create . impressivedev/stable
```bash

Using
https://github.com/bincrafters/conan-templates

### Notes

This repository is still a work in progress. Hopefully, the [jwt-cpp](https://github.com/pokowaka/jwt-cpp) creator will
publish [his own Conan package](https://github.com/pokowaka/jwt-cpp/issues/22). Nothing has be published on bintray.com.

Test targets compilation has been disabled for the package for now.

This package compiles a version a bit further in history than the 1.0 tag of the
[jwt-cpp repository](https://github.com/pokowaka/jwt-cpp), in order to be able to disable the test targets compilation.
