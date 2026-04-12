# Rust Projects Collection

A collection of Rust programming projects covering systems programming, networking, compilers, games, and cryptography. Each project is self-contained with its own `Cargo.toml` and documentation.

## Projects Overview

### 1. [TCP Server](tcp-server/)
A multi-threaded TCP server that demonstrates:
- Socket programming in Rust
- Spawning threads per connection
- Standard library networking (`std::net`)

### 2. [UDP Server/Client](udp-server-client/)
A UDP datagram system that teaches:
- UDP socket programming
- Client-server architecture
- Stateless communication

### 3. [Chat System](chat-system/)
A real-time multi-client chat app that covers:
- TCP socket programming
- Concurrent connections
- Message broadcasting

### 4. [HTTP Server](http-server/)
A simple HTTP/1.1 server that demonstrates:
- Raw socket + HTTP protocol parsing
- Serving static files
- Request/response handling

### 5. [FTP Client/Server](ftp-client-server/)
An FTP implementation that covers:
- FTP protocol commands and responses
- File transfer over TCP
- Client and server roles

### 6. [Ping](ping/)
A custom ICMP ping utility that teaches:
- Raw socket programming
- ICMP protocol
- Round-trip time measurement

### 7. [Port Scanner](port-scanner/)
A concurrent TCP port scanner that demonstrates:
- Concurrent scanning with threads
- TCP connect probing
- CLI argument parsing

### 8. [Arithmetic Compiler](arithmetic-compiler/)
A compiler for arithmetic expressions that covers:
- Lexical analysis (tokenization)
- Parsing and AST construction
- Assembly code generation

### 9. [Lexical Analyser](lexical-analyser/)
A tokenizer / lexer that demonstrates:
- Scanning and token classification
- String manipulation
- Compiler front-end design

### 10. [Notes Manager](notes-manager/)
A CLI notes manager that teaches:
- File or database-backed persistence
- CRUD operations
- Command-line interface design

### 11. [URL Shortener](url-shortener/)
A URL shortening service that covers:
- Hash-based key generation
- Key-value store design
- Simple HTTP or CLI interface

### 12. [QR Generator](qr-generator/)
A QR code generator that demonstrates:
- QR encoding algorithm
- PNG image writing
- Binary data manipulation

### 13. [Asteroid Game](asteroid-game/)
A terminal-based asteroid shooter that teaches:
- Game loop design
- Terminal rendering
- Collision detection

### 14. [Tic-Tac-Toe](tic-tac-toe/)
A networked tic-tac-toe game that covers:
- TCP game server
- Turn-based state management
- Client/server game logic

### 15. [SHA-512](sha-512/)
SHA-512 implemented from scratch that demonstrates:
- Bitwise operations in Rust
- Message scheduling and compression
- Cryptographic padding

### 16. [AES Cipher](aes-cipher/)
AES-256 encryption and decryption that covers:
- SubBytes, ShiftRows, MixColumns, AddRoundKey
- ECB and CBC block cipher modes
- Symmetric cryptography fundamentals

### 17. [RSA Keygen](rsa-keygen/)
RSA key-pair generation and encryption that teaches:
- Prime number generation
- Modular exponentiation
- Public-key cryptography

### 18. [Caesar Cipher](caesar-cipher/)
Classical Caesar cipher with a brute-force cracker that demonstrates:
- Substitution cipher logic
- Frequency analysis
- Brute-force decryption

### 19. [Hash Cracker](hash-cracker/)
A dictionary and brute-force hash cracker that covers:
- MD5, SHA-1, SHA-256, SHA-512 cracking
- Dictionary attack and brute-force modes
- Parallel candidate testing

### 20. [Merkle Tree](merkle-tree/)
A Merkle tree with SHA-256 that teaches:
- Tree construction from data blocks
- Merkle root computation
- Inclusion proof generation and verification

## Getting Started

Each project is a standalone Cargo package. To run any project:

```
cd <project-name>
cargo run
```

Or build everything at once from the workspace root:

```
cargo build --workspace
```

## Prerequisites

- Rust toolchain (`rustup` — stable channel)
- Basic understanding of Rust ownership and borrowing
- For network projects: familiarity with TCP/UDP concepts
- For crypto projects: basic understanding of binary and modular arithmetic

## Learning Path

1. Start with **Caesar Cipher** — simple logic, no dependencies
2. Move to **TCP Server** and **UDP Server/Client** for networking basics
3. Try **Chat System** and **Tic-Tac-Toe** for concurrent networking
4. Tackle **SHA-512** and **AES Cipher** for cryptography fundamentals
5. Build up to **RSA Keygen**, **Hash Cracker**, and **Merkle Tree** for advanced crypto
6. Explore **Arithmetic Compiler** and **Lexical Analyser** for compiler design

## Contributing

Feel free to:
- Report bugs
- Suggest improvements
- Add new features
- Create new projects
- Improve documentation

## License

This project is open source and available for learning purposes.

## Note

Some network projects (Port Scanner, Ping) may require administrator privileges due to raw socket usage. Use responsibly and only on networks you have permission to test.
