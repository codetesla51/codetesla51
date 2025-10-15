# Uthman Oladele

Backend Engineer building systems from first principles in Go | Exploring compilers, parsers, and distributed systems

> "Understanding comes from building it yourself. Frameworks are tools, but knowing what's underneath makes you dangerous."

```go
type Engineer struct {
    Name              string
    Expertise         []string
    CurrentFocus      string
    LearningApproach  string
}

me := Engineer{
    Name:              "Uthman",
    Expertise:         []string{"Systems Programming", "Network Protocols", "Language Design"},
    CurrentFocus:      "Building Git from scratch",
    LearningApproach:  "First principles - no shortcuts",
}
```

---

## Philosophy

I don't just use frameworks - I understand what they're abstracting. Whether it's building an HTTP server from raw TCP sockets or implementing Git's internals, I learn by reconstructing systems from the ground up. This approach has taught me more about performance optimization, protocol design, and distributed systems than any course could.

My approach is stoic: **focus on what I can control.** I can't control market trends or what's popular. I can control the quality of my code, the depth of my understanding, and the consistency of my effort. Everything else is noise.

---

## What I've Built

### GO-CHAT - Concurrent Terminal Chat Server
Real-time messaging system with TLS encryption, AI integration, and rate limiting. Handles 100+ concurrent connections with goroutines.

**Key challenges solved:**
- Concurrent connection management with proper cleanup
- Real-time message broadcasting across lobbies
- AI assistant with conversation context
- Rate limiting and abuse prevention

**Performance:** Tested with 100+ simultaneous users, ~50MB baseline memory, minimal CPU under load.

[View Project →](https://github.com/codetesla51/go-chat-server)

---

### Raw-HTTP - HTTP Server From TCP Sockets
No frameworks. Just sockets, the HTTP spec, and Go. Built to understand networking at the protocol level.

**Performance journey:**
- Started at 250 RPS (buggy)
- Fixed connection handling: 1,389 RPS
- Added keep-alive optimization: 1,710 RPS
- Peak performance: 4,000 RPS
- **16x improvement from initial version**

**What this taught me:** Connection pooling, HTTP/1.1 keep-alive, goroutine management, and how low-level implementation details impact throughput.

[View Project →](https://github.com/codetesla51/raw-http)

---

### Axion - Mathematical Engine & CLI Calculator
Production-ready calculator with AST parser, trigonometric functions, unit conversions, and persistent history.

**Technical highlights:**
- Recursive descent parser with proper operator precedence
- AST construction and traversal
- Edge case handling (division by zero, factorial limits, domain errors)
- 95% test coverage

**Why it matters:** Understanding how parsers work is fundamental to building compilers and interpreters. This project was my entry point into language design.

[View Project →](https://github.com/codetesla51/Axion)

---

### GoLexer - High-Performance Lexical Analyzer
Tokenizer for building compilers, interpreters, and DSLs. Supports Unicode identifiers, multiple number formats, and JSON-based configuration.

**Features:**
- 50+ token types
- Single-pass tokenization with low memory allocation
- Error recovery (detects errors while continuing)
- Validated against 1700+ tokens

**Use cases:** Compiler frontends, configuration parsers, code analysis tools.

[View Project →](https://github.com/codetesla51/golexer)

---

### Swift2FA - Secure Two-Factor Authentication Library
PHP library supporting authenticator apps, email, and SMS verification with built-in encryption.

**Integration is dead simple:**
```php
use Swift2FA\Swift2FA;
$swift2fa = new Swift2FA();
```

**Security measures:**
- Secret key encryption before storage
- TOTP-based code generation
- QR code generation for easy setup

[View Project →](https://github.com/codetesla51/swift2FA)

---

### Brevity - AI-Powered PDF Summarizer
AI summarization tool with multiple output styles (short, detailed, objective questions, simplified explanations). Used extensively by students during exam preparation.

**Technical challenges:**
- UTF-8 encoding normalization
- Character corruption fixes with replacement hashmaps
- PDF text extraction and processing

**Impact:** Helped coursemates study for Computer-Based Tests (CBT) by generating objective questions from study materials.

**Student feedback:** "Brevity helped me through my exams, and I use it in my everyday life." - Olamide (Course Mate)

[View Project →](https://ai-brevity.vercel.app)

---

## The Stoic Approach to Engineering

I focus on what I can control:
- The quality of my code
- The depth of my understanding
- The consistency of my effort
- The problems I choose to solve

Market trends, popularity, what's "hot" right now - that's all external noise. I build systems that work, understand principles that last, and let the rest take care of itself. This mindset keeps me focused on craft over hype, fundamentals over frameworks.

---

## Current Focus

```
Building mini-git to understand version control internals
Exploring distributed consensus algorithms
Extending Axion into a full programming language
Studying systems design patterns at scale
```

---

## Tech Stack

**Languages**

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Svelte](https://img.shields.io/badge/Svelte-FF3E00?style=for-the-badge&logo=svelte&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)

---

## GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=codetesla51&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=codetesla51&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

## Let's Connect

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://devuthman.vercel.app/)
[![X/Twitter](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/uthman_dev)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:uoladele99@gmail.com)

---

<div align="center">

**Building things from first principles, one project at a time**

![Profile Views](https://komarev.com/ghpvc/?username=codetesla51&color=blueviolet&style=for-the-badge)

</div>