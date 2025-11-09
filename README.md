# Uthman Oladele

Backend Developer | Systems Programming in Go

```go
type Engineer struct {
    Name     string
    Focus    []string
    Building string
}

me := Engineer{
    Name:     "Uthman",
    Focus:    []string{"Systems Programming", "Network Protocols", "Compilers"},
    Building: "HTTP servers, version control, and CLI tools from first principles",
}
```

---

## Projects

### go-git - Git Implementation from Scratch
Built Git's core in Go without using any Git libraries. Content-addressable storage, tree objects, staging area, and commit history.

**What works:**
- SHA-256 based object storage with automatic deduplication
- Three-tree architecture (working dir → staging → repository)
- Tree objects built bottom-up with proper hash dependencies
- zlib compression for all objects
- Persistent commit history

[View Project →](https://github.com/codetesla51/go-git) | [Read Article →](https://dev.to/uthman_dev/building-git-from-scratch-in-go-what-i-learned-about-version-control-internals-4dih)

---

### Raw-HTTP - HTTP Server from TCP Sockets
HTTP/HTTPS server built directly on TCP. No frameworks, just sockets and the HTTP spec.

**Performance:**
- Started at 250 RPS (buggy implementation)
- Fixed connection handling: 1,389 RPS
- Added keep-alive optimization: 1,710 RPS  
- Peak: 4,000 RPS
- **16x improvement from initial version**

[View Project →](https://github.com/codetesla51/raw-http) | [Read Article →](https://dev.to/uthman_dev/building-an-http-server-from-tcp-sockets-250-4000-rps-2m93)

---

### GO-CHAT - Concurrent Terminal Chat Server
Real-time messaging system handling 100+ concurrent connections. TLS encryption, AI integration, rate limiting.

**Technical implementation:**
- Concurrent connection management with goroutines
- Real-time message broadcasting across lobbies
- AI assistant with conversation context
- Rate limiting to prevent abuse

**Performance:** 100+ simultaneous users, ~50MB baseline memory, minimal CPU under load.

[View Project →](https://github.com/codetesla51/go-chat-server)

---

### Axion - CLI Calculator with Logical Operations
Mathematical computing environment with AST parser, comparison operators, logical operations, and unit conversions.

**Features:**
- Recursive descent parser with proper precedence
- Comparison operators (>, <, >=, <=, ==, !=) returning boolean values
- Logical operators (&&, ||) with correct precedence
- Scientific functions (trig, log, stats)
- Unit conversion system (length, weight, time)
- Persistent variable storage and calculation history

**Test coverage:** 95% on core modules (tokenizer, parser, evaluator, units)

[View Project →](https://github.com/codetesla51/Axion) | [Read Article →](https://dev.to/uthman_dev/building-a-terminal-calculator-that-actually-does-logic-axion-1p0m)

---

### GoLexer - Lexical Analyzer for Compilers
Tokenizer library for building compilers, interpreters, and DSLs.

**Implementation:**
- 50+ token types with Unicode support
- Single-pass tokenization, low memory allocation
- Error recovery (continues after detecting errors)
- Validated against 1700+ test tokens

**Use cases:** Compiler frontends, configuration parsers, code analysis tools.

[View Project →](https://github.com/codetesla51/golexer)

---

### Brevity - AI PDF Summarizer
AI tool for summarizing PDFs with multiple output styles. Built for exam prep, used by students for CBT preparation.

**Technical challenges:**
- UTF-8 encoding normalization
- Character corruption fixes
- PDF text extraction

[View Project →](https://ai-brevity.vercel.app)

---

### Swift2FA - Two-Factor Authentication Library
PHP library for 2FA with authenticator apps, email, and SMS verification.

**Security:**
- TOTP-based code generation
- Secret key encryption before storage
- QR code generation

[View Project →](https://github.com/codetesla51/swift2FA)

---

## Writing

- [Building Git from Scratch in Go](https://dev.to/uthman_dev/building-git-from-scratch-in-go-what-i-learned-about-version-control-internals-4dih)
- [Building an HTTP Server from TCP Sockets: 250-4000 RPS](https://dev.to/uthman_dev/building-an-http-server-from-tcp-sockets-250-4000-rps-2m93)
- [Building a Terminal Calculator That Actually Does Logic - Axion](https://dev.to/uthman_dev/building-a-terminal-calculator-that-actually-does-logic-axion-1p0m)
- [More articles on DEV.to](https://dev.to/uthman_dev)

---

## Stack

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Svelte](https://img.shields.io/badge/Svelte-FF3E00?style=flat-square&logo=svelte&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

---

## Connect

[![Portfolio](https://img.shields.io/badge/Portfolio-000?style=flat-square&logo=vercel&logoColor=white)](https://devuthman.vercel.app/)
[![X](https://img.shields.io/badge/X-000?style=flat-square&logo=x&logoColor=white)](https://x.com/uthman_dev)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:uoladele99@gmail.com)

---

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=codetesla51&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&count_private=true)

</div>