# List of popular libraries

- [std : Rust Standard library](https://doc.rust-lang.org/std/)
- [List of core Rust libraries](rust-core-libraries.md): top 25

- [Algorithms](#algorithms)
- [Asynchronous](#asynchronous)
- [CLI](#cli): Command-line interface
- [Concurrency](#concurrency)
- [Cryptography](#cryptography)
- [Database](#database)
- [Data structures](#data-structures)
- [Date - Time](#date---time)
- [Encoding data](#encoding-data)
- [Filesystem](#filesystem)
- [HTTP Client](#http-client)
- [HTTP Servers](#http-servers)
- [Network Programming](#network-programming)
- [Parser implementations](#parser-implementations)
- [Rust patterns](#rust-patterns)
- [Text processing](#text-processing)
- [Value formatting](#value-formatting)
- [Development tools](development-tools):
  - [Debugging](#debugging): Errors, logging
  - [Build utils](#build-utils)
  - [Procedural-macros](#procedural-macros)

## Algorithms 
- Core algorithms such as hashing, sorting and searching.

| Rust Crate | Description |
| -| - |
| strsim | Implementations of string similarity metrics. Includes Hamming, Levenshtein, OSA, Damerau-Levenshtein, Jaro, Jaro-Winkler, and Sørensen-Dice. |
  
## Asynchronous 
- Async program flow using techniques like futures, promises, waiting, or eventing.

| Rust Crate | Description |
| -| - |
| mio | Lightweight non-blocking I/O |
| tokio | An event-driven, non-blocking I/O platform for writing asynchronous I/O backed applications |
| h2 | An HTTP/2 client and server |

## CLI
- Argument parsers, line-editing, or output coloring and formatting.

| Rust Crate | Description |
| -| - |
| clap | Command-line argument parser |

## Concurrency
- Implementing concurrent and parallel computation

| Rust Crate | Description |
| -| - |
| parking_lot_core | An advanced API for creating custom synchronization primitives |
| parking_lot | More compact and efficient implementations of the standard synchronization primitives |
| rayon | Parallelism library |

## Cryptography
- Algorithms intended to secure data

| Rust Crate | Description |
| -| - |
| rustls | modern TLS library written in Rust |
| rustls-webpki | Web PKI X.509 Certificate Verification |
| digest | Traits for cryptographic hash functions and message authentication codes |
| sha2 | Pure Rust implementation of the SHA-2 hash function family including SHA-224, SHA-256, SHA-384, and SHA-512 |

## Database 
- implementations Database management systems implemented in Rust.

| Rust Crate | Description |
| -| - |
| diesel | ORM and Query Builder for PostgreSQL, SQLite, and MySQL |
| sqlx | Rust SQL Toolkit. An async, pure Rust SQL crate featuring compile-time checked queries without a DSL. Supports PostgreSQL, MySQL, and SQLite. |

## Data structures
- Rust implementations of data structures for specific purposes

| Rust Crate | Description |
| -| - |
| smallvec | Small, fixed-size vector - 'Small vector' optimization: store up to a small number of items on the stack |

## Date - Time

| Rust Crate | Description |
| -| - |
| time | Date and time library. Fully interoperable with the standard library. Mostly compatible with #![no_std]. |

## Encoding data 
- Encoding and/or decoding data from one data format to another.
- Serialization, deserialization, string conversion

| Rust Crate | Description |
| -| - |
| serde_json | JSON serialization and deserialization library |
| serde_yaml | YAML serialization and deserialization library |

## Filesystem

| Rust Crate | Description |
| -| - |
| tempfile | Managing temporary files and directories |

## HTTP Client
- Make HTTP network requests

| Rust Crate | Description |
| -| - |
| reqwest | High level HTTP client library |

## HTTP Servers
- Server-side programming

| Rust Crate | Description |
| -| - |
| actix-web | Web framework |
| axum | Web framework that focuses on ergonomics and modularity |

## Network programming
- Network protocols such as FTP, HTTP, or SSH, or lower-level TCP or UDP.

| Rust Crate | Description |
| -| - |
| tower | modular and reusable components for building robust clients and servers |

## Parser implementations
- Parse data formats or languages.

| Rust Crate | Description |
| -| - |
| semver | Parser and evaluator for Cargo's flavor of Semantic Versioning |

## Rust patterns
- shared solutions for particular situations specific to programming in Rust.

| Rust Crate | Description |
| -| - |
| anyhow | Error handling library - general error handling |

## Text processing
- Text processing Deal with the complexities of human language when expressed in textual form.
- String searching, Regular Expressions

| Rust Crate | Description |
| -| - |
| aho-corasick | Fast multiple substring searching |
| heck | Case conversion library - checking and manipulating strings |
| regex | Regular expressions for Rust |
| regex-syntax | Regular expressions |. This implementation uses finite automata and guarantees linear time matching on all inputs. |

## Unix APIs 
- Bindings to Unix-specific APIs.

| Rust Crate | Description |
| -| - |
| rustix | Safe Rust bindings to POSIX/Unix/Linux/Winsock-like syscalls | 

## Value formatting
- Format values for display to a user, potentially adapting the display to various languages and regions.

| Rust Crate | Description |
| -| - |
| uuid | Generate and parse UUIDs |
| ryu | Fast floating point to string conversion |

## Development tools

### Debugging 
- Figure out what is going on with your code via logging, tracing, or assertions.

### Build Utils
- Utilities for build scripts and other build time steps.

| Rust Crate | Description |
| -| - |
| cc | A build-time dependency for Cargo build scripts to assist in invoking the native C compiler to compile native C code into a static archive to be linked into Rust code. |

----
## Notes
- Updated: Nov 2025
- Data source: [crates.io](https://crates.io/), [lib.rs](https://lib.rs/)
