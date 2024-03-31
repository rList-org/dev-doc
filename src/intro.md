# Intro

Welcome to the develop documentation of the rList project. rList is a opensource project that aims to high performance and extensible file sharing system. This document is for developers who want to contribute to the project. If you are a user, please refer to the [user documentation](https://www.rlist.dev).

## Project Structure

rList has 4 crates:

1. `rlist-cli`: The main CLI application. 
2. [rlist-core](https://docs.rs/rlist-core/latest/rlist_core/): The core library that contains the main logic of the project.
3. `rlist-drivers`: The drivers that implement the core traits.
4. `rlist-driver-macro`: A macro crate that helps to create new drivers.


