# List of core Rust libraries

- [std : Rust Standard library](https://doc.rust-lang.org/std/)
- [Rust patterns](#rust-patterns)
- [Data structures](#data-structures)
- [Debugging](#debugging): Errors, logging
- [Algorithms](#algorithms): Random numbers generators
- [Encoding data](#encoding-data)
- [Text processing](#text-processing)
- [Network programming](#network-programming)
- [Operating systems](#operating-systems)
- [Build utils](#build-utils)
- [Procedural-macros](#procedural-macros)

## Rust patterns
- shared solutions for particular situations specific to programming in Rust.

| Rust Crate | Description |
| -| - |
| [**bitflags**](https://docs.rs/bitflags/latest/bitflags/) | Macro to generate structures which behave like bitflags |
| [**itertools**](https://docs.rs/itertools/latest/itertools/) | Extra iterator adaptors, iterator methods, free functions, and macros |
| [**once_cell**](https://docs.rs/once_cell/latest/once_cell/) | Single assignment cells and lazy values | 

## Data structures 
- Rust implementations of data structures for specific purposes.

| Rust Crate | Description |
| -| - |
| [**hashbrown**](https://docs.rs/hashbrown/latest/hashbrown/) | Port of Google's SwissTable hash map |
| [**indexmap**](https://docs.rs/indexmap/latest/indexmap/) | A hash table with consistent order and fast iteration |

## Debugging 
- Figure out what is going on with your code via logging, tracing, or assertions.

### Errors

| Rust Crate | Description |
| -| - |
| [**thiserror**](https://docs.rs/thiserror/latest/thiserror/) | derive(Error) - custom error handling | 
| [**thiserror-impl**](https://docs.rs/thiserror-impl/latest/thiserror_impl/) | Implementation detail of the `thiserror` crate | 

### Logging

| Rust Crate | Description |
| -| - |
| [**log**](https://docs.rs/log/latest/log/) | Logging library |

## Algorithms 
- Core algorithms such as hashing, sorting and searching.

### Random numbers

| Rust Crate | Description |
| -| - |
| [**getrandom**](https://docs.rs/getrandom/latest/getrandom/) | A small cross-platform library for retrieving random data from system source | 
| [**rand**](https://docs.rs/rand/latest/rand/) | Random number generators and other randomness functionality |
| [**rand_chacha**](https://docs.rs/rand_chacha/latest/rand_chacha/) | ChaCha random number generator | 
| [**rand_core**](https://docs.rs/rand_core/latest/rand_core/) | Core random number generator traits and tools for implementation |

## Encoding data 
- Encoding and/or decoding data from one data format to another.
- Serialization, deserialization, string conversion

| Rust Crate | Description |
| -| - |
| [**base64**](https://docs.rs/base64/latest/base64/) | encodes and decodes base64 as bytes or utf8 |
| [**itoa**](https://docs.rs/itoa/latest/itoa/) | Fast integer primitive to string conversion | 
| [**serde**](https://docs.rs/serde/latest/serde/) | Generic serialization/deserialization framework - [Additional docs](https://serde.rs/) |
| [**serde_derive**](https://docs.rs/serde_derive/latest/serde_derive/) | Macros 1.1 implementation of #[derive(Serialize, Deserialize)] - [Additional docs](https://serde.rs/derive.html) |

## Text processing
- Text processing Deal with the complexities of human language when expressed in textual form.
- String searching, Regular Expressions

| Rust Crate | Description |
| -| - |
| [**memchr**](https://docs.rs/memchr/latest/memchr/) | Provides extremely fast (uses SIMD on x86_64, aarch64 and wasm32) routines for 1, 2 or 3 byte search and single substring search |
| [**regex-automata**](https://docs.rs/regex-automata/latest/regex_automata/) | Automata construction and matching using regular expressions |
| [**unicode-ident**](https://docs.rs/unicode-ident/latest/unicode_ident/) | Determine whether characters have the XID_Start or XID_Continue properties according to Unicode Standard Annex #31 |

## Network programming 
- Network protocols such as FTP, HTTP, or SSH, or lower-level TCP or UDP.

| Rust Crate | Description |
| -| - |
| [*socket2*](https://docs.rs/socket2/latest/socket2/) | Utilities for handling networking sockets with a maximal amount of configuration possible intended. |

## Operating Systems
- Bindings to operating system-specific APIs.

| Rust Crate | Description |
| -| - |
| [**libc**](https://docs.rs/libc/latest/libc/) | Raw FFI bindings to platform libraries like libc |
| [*windows-sys*](https://docs.rs/windows-sys/latest/windows_sys/) | Rust for Windows |

## Build Utils
- Utilities for build scripts and other build time steps.

| Rust Crate | Description |
| -| - |
| [**autocfg**](https://docs.rs/autocfg/latest/autocfg/) | Automatic cfg for Rust compiler features |

## Procedural macros
- Extend Rust language with procedural macros.

| Rust Crate | Description |
| -| - |
| [**cfg-if**](https://docs.rs/cfg-if/latest/cfg_if/) | Macro to ergonomically define an item depending on a large number of #[cfg] parameters. Structured like an if-else chain, the first matching branch is the item that gets emitted |
| [**proc-macro2**](https://docs.rs/proc-macro2/latest/proc_macro2/) | substitute implementation of the compiler's `proc_macro` API to decouple token-based libraries from the procedural macro use case |
| [**quote**](https://docs.rs/quote/latest/quote/) | Quasi-quoting macro quote!(...) |
| [**syn**](https://docs.rs/syn/latest/syn/) | Parser for Rust source code |

----
## Notes
- Crates in bold are top 25 all time downloads
- Crates in italic are in the top 25 of recent download (but not top 25 all time)
- Updated: Nov 2025
- Data source: crates.io


