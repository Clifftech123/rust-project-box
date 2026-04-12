# Rust Project Box

A collection of 20 Rust projects — systems programming, networking, compilers, games, and cryptography.

## Projects

### Systems & Networking
| Project | Description |
|---------|-------------|
| [tcp-server](./tcp-server) | Multi-threaded TCP server |
| [udp-server-client](./udp-server-client) | UDP server and client |
| [chat-system](./chat-system) | Multi-client TCP chat system |
| [http-server](./http-server) | Simple HTTP server with static file serving |
| [ftp-client-server](./ftp-client-server) | FTP server and client |
| [ping](./ping) | ICMP ping utility |
| [port-scanner](./port-scanner) | Concurrent TCP port scanner |

### Compilers & Parsers
| Project | Description |
|---------|-------------|
| [arithmetic-compiler](./arithmetic-compiler) | Arithmetic expression compiler |
| [lexical-analyser](./lexical-analyser) | Lexer / tokenizer |

### Applications
| Project | Description |
|---------|-------------|
| [notes-manager](./notes-manager) | CLI notes manager |
| [url-shortener](./url-shortener) | URL shortener service |
| [qr-generator](./qr-generator) | QR code to PNG generator |
| [asteroid-game](./asteroid-game) | Terminal asteroid shooter |
| [tic-tac-toe](./tic-tac-toe) | Networked tic-tac-toe |

### Cryptography
| Project | Description |
|---------|-------------|
| [sha-512](./sha-512) | SHA-512 from scratch |
| [aes-cipher](./aes-cipher) | AES-256 encryption (ECB & CBC) |
| [rsa-keygen](./rsa-keygen) | RSA key-pair generation & encryption |
| [caesar-cipher](./caesar-cipher) | Caesar cipher + brute-force cracker |
| [hash-cracker](./hash-cracker) | Dictionary & brute-force hash cracker |
| [merkle-tree](./merkle-tree) | Merkle tree with SHA-256 |

## Usage

```
cargo build --workspace
cargo run -p <project-name>
```
