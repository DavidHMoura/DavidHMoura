```
╔══════════════════════════════════════════════════════════════════╗
║         SENTINEL COMMAND CENTER  //  NODE: DAVIDMOURA            ║
║         PROTOCOL: SSH-ED25519    //  CIPHER: AES-256-GCM         ║
╚══════════════════════════════════════════════════════════════════╝

  > initiating secure handshake...
  > verifying certificate chain...    [ OK ]
  > authenticating identity...        [ OK ]
  > loading operational profile...    [ OK ]

  ACCESS GRANTED  ──  WELCOME TO THE SENTINEL NODE
```

---

```
ROOT@DAVIDMOURA:~# whoami
```

```
┌─────────────────────────────────────────────────────────────────┐
│  IDENTITY    David Moura                                         │
│  ROLE        Backend Architect  //  Security Engineer            │
│  CLEARANCE   SYSTEM-LEVEL                                        │
│  LOCATION    /home/davidmoura  [ENCRYPTED]                       │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  Backend engineer operating at the intersection of performance   │
│  and security. I build systems that don't just work — they       │
│  resist adversity.                                               │
│                                                                  │
│  Fluent in Java/Spring for high-throughput service design.       │
│  Migrating critical workloads to Rust for memory safety and      │
│  extreme performance. Linux is my native environment.            │
│  Security is not a feature — it is the architecture.             │
│                                                                  │
│  DIRECTIVE: engineer the most secure, efficient backend          │
│  systems. no shortcuts. no compromise.                           │
└─────────────────────────────────────────────────────────────────┘
```

---

```
ROOT@DAVIDMOURA:~# cat /etc/capabilities.conf
```

| MODULE | TECHNOLOGY | STATUS |
| :--- | :--- | :---: |
| **Core Languages** | Rust · Java 21 (Loom) · Bash | `ACTIVE` |
| **Backend Frameworks** | Spring Boot 3.4+ · Axum · Tokio | `ACTIVE` |
| **Security** | AppSec · DevSecOps · Zero Trust · Cryptography | `ACTIVE` |
| **Offensive Research** | Web/API Pentesting · Vuln Exploitation | `RESEARCH` |
| **Infrastructure** | Docker · CI/CD Hardening · Container Scanning | `ACTIVE` |
| **Systems** | Linux Kernel · OS Hardening · System Auditing | `ACTIVE` |
| **Data Layer** | PostgreSQL · Secure Schema Design | `ACTIVE` |
| **Protocols** | TLS 1.3 · mTLS · JWT · OAuth2 | `ACTIVE` |

---

```
ROOT@DAVIDMOURA:~# systemctl status sentinel
```

```
● sentinel.service — Operational Profile
     Loaded: loaded  (/etc/sentinel/profile.conf)
     Active: RUNNING since boot

  ACTIVE MODULES:

  [✓] secure backend architecture design
  [✓] rust-based systems and security tooling
  [✓] web & api vulnerability research
  [✓] linux kernel hardening and auditing
  [✓] devsecops pipeline engineering
  [✓] zero trust architecture implementation
  [✓] concurrent systems in java virtual threads
  [✓] async/await performance patterns in rust

  THREAT POSTURE: defensive + offensive awareness
  MEMORY MODEL:   safe  (no undefined behavior tolerated)
  UPTIME:         continuous
```

---

```
ROOT@DAVIDMOURA:~# tail -f /var/log/sentinel/ops.log
```

```
[2026-03-16 00:00:01]  [INFO]   refactoring sentinelops threat ingestion engine → Rust/Axum
[2026-03-16 00:00:02]  [INFO]   hardening linux system auditing scripts
[2026-03-16 00:00:03]  [INFO]   researching API authentication bypass vectors
[2026-03-16 00:00:04]  [INFO]   tuning PostgreSQL query security and injection surface
[2026-03-16 00:00:05]  [INFO]   building memory-safe concurrent services with Tokio
[2026-03-16 00:00:06]  [INFO]   improving CI/CD pipeline with Trivy + Docker Scout scanning
[2026-03-16 00:00:07]  [INFO]   documenting zero trust patterns for distributed auth
[2026-03-16 00:00:08]  [INFO]   ...
[2026-03-16 00:00:09]  [WARN]   idle processes terminated
[2026-03-16 00:00:10]  [INFO]   all systems nominal
```

---

```
ROOT@DAVIDMOURA:~# ls -la projects/
```

| PROJECT | STACK | SECURITY STATUS | NOTES |
| :--- | :--- | :---: | :--- |
| **[secure-auth-api](https://github.com/DavidHMoura/secure-auth-api)** | Spring Security 6 · JWT | `STABLE` | Token rotation · reuse detection |
| **[sentinelops](https://github.com/DavidHMoura/sentinelopsproject)** | Rust · Axum · PostgreSQL | `REFACTORING` | Memory-safe threat ingestion |
| **[compliance-risk-engine](https://github.com/DavidHMoura/compliance-risk-engine)** | Java 21 · Playwright | `STABLE` | Immutable audit log · zero attack surface |
| **[linux-security-scripts](https://github.com/DavidHMoura)** | Bash · Rust | `ACTIVE` | OS hardening · system auditing |

---

```
ROOT@DAVIDMOURA:~# netstat -connections
```

```
┌──────────────────────────────────────────────────────────────────┐
│  NETWORK CONNECTIONS  //  EXTERNAL INTERFACES                    │
├──────────────────────────────────────────────────────────────────┤
│                                                                  │
│  [ESTABLISHED]  linkedin.com/in/david-h-moura-457063304          │
│                 protocol: HTTPS · status: OPEN                   │
│                                                                  │
│  [ESTABLISHED]  github.com/DavidHMoura                           │
│                 protocol: SSH · status: OPEN                     │
│                                                                  │
└──────────────────────────────────────────────────────────────────┘
```

> LinkedIn → [linkedin.com/in/david-h-moura-457063304](https://www.linkedin.com/in/david-h-moura-457063304/)
>
> GitHub → [github.com/DavidHMoura](https://github.com/DavidHMoura)

---

```
ROOT@DAVIDMOURA:~# exit
```

```
╔══════════════════════════════════════════════════════════════════╗
║                   SESSION TERMINATED                             ║
╠══════════════════════════════════════════════════════════════════╣
║                                                                  ║
║   identity  :  David Moura          [ VERIFIED ]                 ║
║   cipher    :  AES-256-GCM          [ INTACT   ]                 ║
║   integrity :  SHA-512 checksum     [ PASSED   ]                 ║
║   errors    :  0                                                 ║
║   warnings  :  0                                                 ║
║                                                                  ║
║   connection secured.                                            ║
║   session closed.                                                ║
║                                                                  ║
╚══════════════════════════════════════════════════════════════════╝

  "Talk is cheap. Show me the code."  — Linus Torvalds
```
