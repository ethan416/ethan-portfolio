# ethan-portfolio
Security-focused computer science student specializing in web application security, low-level systems security (C), applied cryptography, and full-stack backend engineering (Django/SQL).

## Cryptography Project – Practical Cryptographic Attacks
Implemented real-world cryptographic attacks in a controlled Docker-based environment to analyze vulnerabilities arising from improper use of hash functions, symmetric encryption, and RSA padding schemes.

**Key Concepts Explored** 
- Length extension attacks against SHA-256 (Merkle–Damgård construction)
- MD5 collision generation producing identical hashes with different program behavior
- CBC padding oracle attack to decrypt ciphertext without access to the secret key
- RSA PKCS#1 v1.5 signature forgery via Bleichenbacher’s attack (e = 3)
- Cryptographic padding validation weaknesses and MAC-then-encrypt flaws
- 
**Technical Stack**
- Python 3 (standard libraries only)
- Docker development container
- OpenSSL toolkit
- AES (CBC mode), SHA-256, HMAC
- Modular arithmetic & RSA number theory
- Linux command-line tooling

[Project Repository](https://github.com/ethan416/cryptography-project)

## Application Security Project – Control-Flow Hijacking

Developed exploits in a controlled Linux VM environment to analyze and exploit stack-based buffer overflow vulnerabilities in native C programs.

**Key Concepts Explored**
- Stack variable and return address overwrites
- Redirecting execution to injected shellcode
- Indirect control-flow hijacking under constrained input
- Bypassing DEP using return-to-libc and ROP techniques
- Exploiting targets with randomized stack positions (ASLR considerations)

**Technical Stack**
- C 
- Python 
- x86_64 assembly analysis
- GDB for dynamic debugging
- ROPgadget for gadget discovery
- Linux VM environment

[Project Repository](https://github.com/ethan416/application-security-project)

**Spotify Wrapped Project**

Android application integrating the Spotify Developer API to generate personalized music analytics and recommendations.

**Key Features**
- Retrieved and analyzed user listening data (top tracks, artists, genres)
- Generated dynamic music recommendations
- Seasonal themed modes (Halloween & Christmas)
- In-app preview playback and Spotify deep-linking

**Technical Stack**
- Java (Android)
- RESTful API integration (Spotify API)
- Backend database for persistent user/session data
- Object-Oriented Design (SOLID principles)
- Agile Scrum + CI/CD pipeline

[Project Repository](https://github.com/radah19/Spotify-Wrapped)


## Auction Marketplace Project

Django-based e-commerce auction platform inspired by eBay, allowing users to create listings, place bids, comment, and manage personalized watchlists.

**Key Features**
- Created and managed auction listings with category support
- Implemented competitive bidding system with validation logic
- Enabled user watchlists and listing comments
- Auction close functionality with automatic winner determination
- Django Admin interface for full CRUD management

**Technical Stack**
- Python (Django Framework)
- SQL relational database (Django ORM)
- Server-side validation for bid integrity and auction rules
- Django authentication system for user login/registration
- MVC architecture with model-driven database design

[Project Repository](https://github.com/me50/ethan416/tree/web50/projects/2020/x/commerce)

