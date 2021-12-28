# Parse Args Library
A small library for Rust that simplifies parsing command line arguments, and in particular options.

## Installation
To add the library to your project, add it as a dependency to the cargo build system. Simply add the following line to `[dependencies]` to let cargo auto-pull the repo:
```
opstring = { git = "https://github.com/Lut99/parse-args", branch="main" }
```
You can also refer a specific version by defining a tag:
```
opstring = { git = "https://github.com/Lut99/parse-args", tag="v1.0.0" }
```
All tags can be found in the [tags](https://github.com/Lut99/parse-args/tags) page.

## Testing
The Parse Args library has build-in unit tests. Run them for the library by running:
```
cargo test
```
either in the library's root folder or in the root folder of the project including this library.

## Usage
For a complete overview of what the library has to offer, check the [wiki](https://github.com/Lut99/parse-args/wiki) page.

## Dependencies
The Parse Args library only depends on the [`OpString`](https://github.com/Lut99/opstring) library. It will automatically be pulled and compiled if you use cargo.

## Contribution
Do you have a suggestion, bugfix or something you don't like? Let it know by creating an issues in the [issues](https://github.com/Lut99/parse-args/issues) page, and we'll look into it as soon as we can.

You're also free to create a pull request yourself, which we will review as soon as we can.
