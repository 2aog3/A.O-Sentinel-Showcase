<div align="center">

```
 █████╗  ██████╗     ███████╗███████╗███╗   ██╗████████╗██╗███╗   ██╗███████╗██╗
██╔══██╗██╔═══██╗    ██╔════╝██╔════╝████╗  ██║╚══██╔══╝██║████╗  ██║██╔════╝██║
███████║██║   ██║    ███████╗█████╗  ██╔██╗ ██║   ██║   ██║██╔██╗ ██║█████╗  ██║
██╔══██║██║   ██║    ╚════██║██╔══╝  ██║╚██╗██║   ██║   ██║██║╚██╗██║██╔══╝  ██║
██║  ██║╚██████╔╝    ███████║███████╗██║ ╚████║   ██║   ██║██║ ╚████║███████╗███████╗
╚═╝  ╚═╝ ╚═════╝     ╚══════╝╚══════╝╚═╝  ╚═══╝   ╚═╝   ╚═╝╚═╝  ╚═══╝╚══════╝╚══════╝
```

**Privacy-First · Local AI · Zero Data Leakage**

[![Node.js](https://img.shields.io/badge/Node.js-Express_5-339933?style=flat-square&logo=node.js&logoColor=white)](https://expressjs.com/)
[![React](https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react&logoColor=black)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-8-646CFF?style=flat-square&logo=vite&logoColor=white)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![Ollama](https://img.shields.io/badge/Ollama-Llama3-FF6B35?style=flat-square)](https://ollama.ai/)
[![License](https://img.shields.io/badge/License-ISC-green?style=flat-square)](./LICENSE.txt)
[![Author](https://img.shields.io/badge/Author-Ahmad_Oglah_Abuzaid-a78bfa?style=flat-square)](https://github.com/AhmadOglah)

---

> *"A.O Sentinel doesn't just match strings — it reads your code."*

</div>

---
<p align="center">
  <img src="Photos/Screenshot%202026-04-01%20182008.png" width="900" alt="A.O Sentinel Main Dashboard">
  <br>
  <b><i>Core Dashboard: Real-time AI Risk Assessment & Vulnerability Detection</i></b>
</p>

| 🧠 AI Context Analysis | 💬 SSE Streaming Chat |
| :---: | :---: |
| <img src="Photos/Screenshot%202026-04-01%20185703.png" width="400"> | <img src="Photos/Screenshot%202026-04-01%20181604.png" width="400"> |
| *Deep 11-line code window auditing* | *Interactive consultant powered by Llama 3* |

| 🛡️ Security Probes Config | ⚡ GPU-Accelerated Scans |
| :---: | :---: |
| <img src="Photos/Screenshot%202026-04-01%20192341.png" width="400"> | <img src="Photos/Screenshot%202026-04-01%20181345.png" width="400"> |
| *Customizing 33+ detection modules* | *Ultra-fast local processing with Ollama* |

<h3 align="center">📄 Professional PDF Reporting Engine</h3>
<p align="center">
  <img src="Photos/Screenshot%202026-04-01%20192617.png" width="280">
  <img src="Photos/Screenshot%202026-04-01%20192604.png" width="280">
  <img src="Photos/Screenshot%202026-04-01%20192631.png" width="280">
  <br>
  <i>Automated professional reports with Executive Summaries and Detailed Findings.</i>
</p>

<details>
  <summary><b>🔍 Click here to view more UI details & Vulnerability Detection Panels</b></summary>
  <br>
  <p align="center">
    <img src="Photos/Screenshot%202026-04-01%20192350.png" width="800"><br>
    <img src="Photos/Screenshot%202026-04-01%20192402.png" width="800"><br>
    <img src="Photos/Screenshot%202026-04-01%20192450.png" width="800"><br>
    <img src="Photos/Screenshot%202026-04-01%20192505.png" width="800"><br>
    <img src="Photos/Screenshot%202026-04-01%20192523.png" width="800">
  </p>
</details>

## Table of Contents

1. [Executive Overview](#1-executive-overview)
2. [Deep AI Analysis Engine](#2-deep-ai-analysis-engine)
3. [Interactive Security Chat](#3-interactive-security-chat)
4. [PDF Reporting Engine](#4-pdf-reporting-engine)
5. [Technical Architecture](#5-technical-architecture)
6. [Scan Capabilities](#6-scan-capabilities)
7. [Installation & Setup](#7-installation--setup)
8. [GPU Acceleration](#8-gpu-acceleration)
9. [Privacy & Ethics](#9-privacy--ethics)
10. [API Reference](#10-api-reference)
11. [Project Structure](#11-project-structure)

---

## 1. Executive Overview

**A.O Sentinel** is a full-stack, privacy-first cybersecurity auditing platform that leverages a locally-running large language model (Llama3 via Ollama) to perform **context-aware** security analysis. Unlike conventional pattern-matching scanners that flag every keyword match, A.O Sentinel is designed to *understand code logic* — it reads the surrounding execution context of every potential finding before rendering a verdict.

### What makes it different

| Feature | Traditional Scanners | A.O Sentinel |
|---|---|---|
| Analysis Method | Regex / string matching | 11-line context window + Llama3 |
| False Positive Rate | High | Minimized (AI discards non-secrets) |
| Severity Assessment | Static (type-based) | Dynamic (context-aware CRITICAL → LOW) |
| PII Detection | Keyword only | AI-verified (real vs. dummy data) |
| Remediation | Generic advice | Language-specific, exact corrected line |
| Data Privacy | Cloud API (data leaves machine) | **100% local — zero egress** |
| Reporting | Basic CSV/JSON | CTO-grade PDF Executive Briefing |
| Consultation | None | Per-finding AI chat (SSE streaming) |

A.O Sentinel supports two distinct scanning modes:

- **File / Directory Scanner** — Recursively audits codebases for hardcoded secrets, credentials, and PII using a 4-phase AI pipeline
- **URL Active Probe** — Actively tests live web endpoints for 17+ vulnerability classes across three scan intensities (Stealth, Balanced, Insane), backed by a Smart Fingerprint engine that auto-detects the target tech stack

---

## 2. Deep AI Analysis Engine

The core intelligence of A.O Sentinel lives in `backend/Utils/secretScanner.js`. Every potential finding passes through a four-phase pipeline before being surfaced to the user.

### Phase 1 — Regex + Pre-filters

Fourteen secret patterns cover the full spectrum of credential types:

| Pattern Label | Example Match | Category |
|---|---|---|
| Generic API Key | `api_key: "Abc123..."` | Credentials |
| Generic Secret / Token | `token = "eyJhbGci..."` | Credentials |
| Password in Code | `password: "Sup3rS3cr3t"` | Credentials |
| AWS Access Key ID | `AKIA0123456789ABCDEF` | Cloud |
| AWS Secret Access Key | `aws_secret = "abc123..."` | Cloud |
| Database Connection String | `mongodb://user:pass@host/db` | Infrastructure |
| Private Key Block | `-----BEGIN RSA PRIVATE KEY-----` | Cryptographic |
| JWT Token | `eyJ...eyJ...sig` | Auth Tokens |
| GitHub / GitLab Token | `ghp_abc123...` | Version Control |
| Slack Token | `xoxb-123-456-...` | SaaS |
| Stripe Key | `sk_live_abc123...` | Payments |
| Google API Key | `AIzaSyAbc123...` | Cloud |
| Basic Auth in URL | `https://user:pass@api.host/v1` | Credentials |
| Email Address (PII) | `user@company.com` | PII |
| Phone Number (PII) | `+1 (555) 867-5309` | PII |

Before a candidate reaches the AI, two deterministic pre-filters eliminate obvious noise:
- **Variable-only assignment guard** — skips lines like `const token = someOtherVar;`
- **Placeholder value guard** — skips values matching `test`, `demo`, `changeme`, `xxx`, `<YOUR_KEY>`, etc.

### Phase 2 — `extractContextBlock` (11-Line Window)

```
File: src/config/database.js  [ext: .js, name: database.js]
────────────────────────────────────────────────────────────
       1 | const mongoose = require('mongoose');
       2 |
       3 | const connectDB = async () => {
       4 |   try {
       5 |     const conn = await mongoose.connect(
>>>    6 |       'mongodb://admin:Sup3rS3cr3t@prod.cluster.mongodb.net/app',
       7 |       { useNewUrlParser: true }
       8 |     );
       9 |     console.log(`Connected: ${conn.connection.host}`);
      10 |   } catch (err) {
      11 |     process.exit(1);
```

The `extractContextBlock` function captures **5 lines above and 5 lines below** the matched line (11 lines total). The flagged line is annotated with `>>>` so Llama3 immediately knows which line triggered the regex. A file-context header (extension + basename) is prepended so the model can infer the programming language and file role.

### Phase 3 — Llama3 Deep Verification

The 11-line context block is submitted to Llama3 with the `DEEP_AUDIT_SYSTEM_PROMPT`, which instructs the model to:

1. **Confirm or discard** — Is this actually a secret, or an environment variable reference, a variable name, or a test value?
2. **Assign severity** — One of `CRITICAL`, `HIGH`, `MEDIUM`, or `LOW` based on the *execution context*, not just the file type
3. **Write a logic analysis** — One to two sentences explaining exactly why this finding is dangerous
4. **Generate remediation code** — The exact corrected line using `process.env.VAR_NAME` (Node.js), `os.environ.get("VAR_NAME")` (Python), or `System.getenv("VAR_NAME")` (Java)
5. **Detect PII** — `true` only for real-looking personal data (not `test@example.com` or `555-xxxx` placeholders)

The model responds in compact JSON:

```json
{
  "is_secret": true,
  "logic_analysis": "The database connection string embeds plaintext admin credentials directly inside mongoose.connect(), meaning any developer with repository access can obtain full production database credentials.",
  "severity": "CRITICAL",
  "remediation_code": "const conn = await mongoose.connect(process.env.MONGODB_URI, { useNewUrlParser: true });",
  "pii_detected": false
}
```

AI calls run at a concurrency of **2** (safe for single-threaded local Llama3) with a 30-second timeout per finding.

### Phase 4 — Dynamic Severity Scoring (Deterministic Override)

After the AI renders its verdict, `applyDeterministicSeverity` applies two hard rules that override the model's assessment:

**Rule 1 — Test File Cap:** If the file path contains `test`, `spec`, `mock`, `__fixtures__`, `__mocks__`, `fixtures`, or `examples`, severity is capped at `MEDIUM`. This prevents false CRITICAL alerts from test helpers.

**Rule 2 — Sensitive Function Escalation (overrides Rule 1):** If the 11-line context block contains a direct call to any of the following functions, severity is **unconditionally forced to `CRITICAL`**:

```
mongoose.connect  · new MongoClient  · pg.connect  · mysql.createConnection
redis.createClient  · new Sequelize  · knex({...})  · axios.post/get/put
fetch(  · createTransport  · new SES/S3/DynamoDB
```

This logic captures the scenario where a test helper directly calls a real production connector — the most dangerous class of test-file credential leak.

### Executive Summary Generation

After all findings are confirmed, `generateExecutiveSummary` runs two concurrent Llama3 calls:

1. **`EXECUTIVE_SUMMARY_SYSTEM_PROMPT`** — Produces a precise 3-sentence CTO briefing:
   - Sentence 1: Most critical finding + business impact (data breach, compliance violation)
   - Sentence 2: Top vulnerability categories + number of affected files
   - Sentence 3: Single most urgent remediation action for today

2. **`EXECUTIVE_BULLETS_SYSTEM_PROMPT`** — Produces 3 business-impact bullet points with strong action verbs (`Rotate`, `Revoke`, `Remediate`, `Expose`, `Leak`) — designed for non-technical executives

Both calls receive a **findings digest** (top 15 findings sorted by severity, with PII flags) and are capped to a 3,000-character context to prevent token overflow.

---

## 3. Interactive Security Chat

Every confirmed finding in the results table includes a **"Ask AI"** button that opens an inline chat panel powered by `FindingChatPanel.jsx`. This is not a generic chatbot — Llama3 receives the exact 11-line code context block of that specific finding as part of every request.

### SSE Streaming Architecture

The chat system uses **Server-Sent Events (SSE)** for real-time token streaming:

```
Client                     Backend (Express)          Ollama (Llama3)
  │                               │                         │
  │── POST /api/ai/chat ─────────►│                         │
  │   { contextBlock, userMsg }   │── stream: true ────────►│
  │                               │                         │
  │◄── Content-Type:              │◄── NDJSON stream ───────│
  │    text/event-stream ─────────│   (one token per line)  │
  │                               │                         │
  │◄── data: {"token":"The"} ─────│                         │
  │◄── data: {"token":" key"} ────│                         │
  │◄── data: {"token":" is"} ─────│                         │
  │◄── data: {"done":true} ───────│                         │
```

The backend (`aiController.js`) sets `Content-Type: text/event-stream`, disables nginx proxy buffering (`X-Accel-Buffering: no`), and pipes Ollama's NDJSON stream directly to the client. A client disconnect event (`req.on("close")`) destroys the Ollama request immediately to free GPU resources.

The frontend (`FindingChatPanel.jsx`) reads the stream using the native `ReadableStream` API with a `TextDecoder`, parsing `data:` SSE lines and appending tokens to the last assistant message in real-time — creating a typewriter effect.

### Chat Capabilities

The `CHAT_SYSTEM_PROMPT` configures Llama3 as a senior application security engineer who can:

- Explain the vulnerability in the context of the **specific code block**
- Describe a realistic attack scenario for **this exact finding**
- Provide **language-specific remediation** steps (not generic advice)
- Estimate a **CVSS v3.1 base score** on request
- Map the finding to **compliance frameworks** (GDPR, PCI-DSS, SOC 2)

Quick-question chips offer one-click prompts for the most common follow-ups:

| Chip | Purpose |
|---|---|
| "How could an attacker exploit this?" | Threat modeling |
| "What is the CVSS score for this finding?" | Risk quantification |
| "What compliance frameworks does this violate?" | Regulatory mapping |
| "Show me the corrected code." | Immediate remediation |

---

## 4. PDF Reporting Engine

`frontend/src/utils/reportGenerator.js` generates professional cybersecurity audit PDFs using **pdfmake** — a fully client-side PDF library with zero server dependencies and zero network requests. Roboto fonts are bundled in `vfs_fonts` and embedded directly into the PDF binary.

### Report Structure

**Page 1 — Cover Page** (dark navy `#020617` background)
- A.O Sentinel branding with neon-green (`#39ff14`) accent
- Scan metadata card: Researcher, Report Date, Target, Scan Type, Intensity, Active Detectors
- Severity summary cards (CRITICAL / HIGH / MEDIUM / LOW / INFO) with per-severity counts
- Proportional severity bar — visual split of the finding distribution
- Total findings count + risk badge (CRITICAL RISK / HIGH RISK / MEDIUM RISK / LOW RISK)
- Confidentiality notice

**Page 2 — Executive Briefing** (white background, rendered only when AI data is present)
- `▶ EXECUTIVE BRIEFING` heading with `✦ Deep AI Analysis by Ahmad Oglah Abuzaid` attribution
- AI badge: *"Business Impact Analysis — Generated by Llama3 — local AI model · no data leaves your machine"*
- Three numbered business-impact bullets (① ② ③) generated by Llama3
- Optional prose executive summary paragraph

**Page 3+ — Technical Findings Table** (white background, header repeats on each page)

For **File / Secret scans**:

| Column | Content |
|---|---|
| `#` | Finding number |
| `SECRET TYPE` | Credential category (bold) |
| `FILE` | Last 3 path segments |
| `CONTENT PREVIEW` | First 150 characters of the matched line (red text) |
| `REMEDIATION` | Type-specific expert guidance (green italic text) |

For **URL Active Probe scans**:

| Column | Content |
|---|---|
| `#` | Finding number |
| `TYPE / SEVERITY` | Severity label color-coded by level |
| `VULNERABILITY` | Vulnerability class name |
| `PAYLOAD / EVIDENCE` | Attack payload or response evidence |
| `REMEDIATION` | Specific remediation guidance |

All pages include a header bar (`A.O SENTINEL // SECTION TITLE · PAGE N`) and a confidential footer (`CONFIDENTIAL — Researcher: Ahmad Oglah Abuzaid`).

---

## 5. Technical Architecture

```
┌─────────────────────────────────────────────────────────────────┐
│                        BROWSER (port 3000)                       │
│  ┌─────────────┐  ┌──────────────┐  ┌────────────────────────┐  │
│  │  ScanInput  │  │  ScanConfig  │  │    ResultsTable.jsx     │  │
│  │  (File/URL) │  │  (Detectors/ │  │  Fragment Keys (stable) │  │
│  └──────┬──────┘  │   Intensity) │  │  AI Deep-Audit Panel    │  │
│         │         └──────────────┘  │  FindingChatPanel (SSE) │  │
│         │                           └────────────────────────┘  │
│  ┌──────▼──────────────────────────────────────────────────────┐ │
│  │                     App.jsx (React 19)                       │ │
│  │   axios POST → /api/scanner/run  or  /api/scanner/probe      │ │
│  │   fetch SSE  → /api/ai/chat                                  │ │
│  └─────────────────────────────────────────────────────────────┘ │
│  Vite 8 · Tailwind CSS v4 · Framer Motion · pdfmake · JetBrains  │
└──────────────────────────────┬──────────────────────────────────┘
                               │ HTTP (localhost)
┌──────────────────────────────▼──────────────────────────────────┐
│                    BACKEND (Express 5 · port 5000)               │
│                                                                  │
│  ┌─────────────────────────┐  ┌─────────────────────────────┐   │
│  │   /api/scanner/run      │  │   /api/ai/chat               │   │
│  │   scannerController.js  │  │   aiController.js            │   │
│  │   └► secretScanner.js   │  │   SSE text/event-stream      │   │
│  │      4-Phase AI Pipeline│  └──────────────┬──────────────┘   │
│  │                         │                 │                   │
│  │   /api/scanner/probe    │                 │                   │
│  │   └► urlFuzzer.js       │                 │                   │
│  │      17+ detectors      │                 │                   │
│  │                         │                 │                   │
│  │   /api/scanner/         │                 │                   │
│  │   fingerprint           │                 │                   │
│  │   Tech stack detection  │                 │                   │
│  └────────────┬────────────┘                 │                   │
└───────────────┼──────────────────────────────┼───────────────────┘
                │                              │
                └──────────────┬───────────────┘
                               │ HTTP (localhost:11434)
┌──────────────────────────────▼──────────────────────────────────┐
│                     OLLAMA (Llama3)                               │
│   /api/generate  (stream: false)  — Deep audit + exec summary    │
│   /api/generate  (stream: true)   — Interactive chat (SSE)       │
│   GPU-accelerated · 100% local · Zero egress                     │
└─────────────────────────────────────────────────────────────────┘
```

### Frontend — React 19 + Vite 8

The frontend runs on **React 19** with **Vite 8** and **Tailwind CSS v4** (delivered as a Vite plugin — no `tailwind.config.js` required). Animations are handled by **Framer Motion 12**.

The `ResultsTable.jsx` component uses a notable optimization: row keys are derived from a stable composite identity (`${finding.file}-${finding.line}-${finding.type}`) rather than array indices. This prevents React from remounting the entire chat panel when the AI enrichment fields are attached to a finding object post-scan, preserving the live chat state across state updates.

```jsx
// Stable key: never use array index — AI enrichment updates the object
// but the identity (file + line + type) never changes
const rowKey = finding.id ?? `${finding.file}-${finding.line}-${finding.type}`;

return (
  <Fragment key={rowKey}>
    <tr>...</tr>
    {isExpanded && hasAI && <tr>...</tr>}   {/* AI panel row */}
  </Fragment>
);
```

`React.Fragment` with a key wraps each finding's two rows (main row + expandable AI panel), ensuring the expanded state and open chat panel survive re-renders.

### Backend — Node.js + Express 5

| Route | Controller | Description |
|---|---|---|
| `POST /api/scanner/run` | `scannerController.runScan` | File/directory deep audit |
| `POST /api/scanner/probe` | `scannerController.runUrlScan` | Active URL vulnerability probe |
| `POST /api/scanner/fingerprint` | `scannerController.runFingerprint` | Tech stack detection |
| `POST /api/ai/chat` | `aiController.streamChat` | SSE streaming AI chat |

### Ollama / Llama3 Integration

| Parameter | File / Directory Audit | Chat |
|---|---|---|
| Endpoint | `http://localhost:11434/api/generate` | Same |
| Model | `llama3` | `llama3` |
| Stream | `false` | `true` (NDJSON) |
| Temperature | `0` (deterministic) | `0.15` (natural dialogue) |
| Max tokens | `380` (per finding) / `400` (summary) | `450` |
| Concurrency | 2 simultaneous findings | N/A (streaming) |
| Timeout | 30 seconds | 60 seconds |

---

## 6. Scan Capabilities

### File / Directory Scanner

Recursively walks a directory tree, automatically skipping:
`node_modules` · `.git` · `dist` · `build` · `.next` · `coverage` · `.cache` · `__pycache__` · `vendor`

Also skips binary files (`.png`, `.jpg`, `.pdf`, `.zip`, `.exe`, `.dll`) and minified bundles (`.min.js`, `.bundle.js`, `.chunk.js`, `.map`).

### URL Active Probe — 17 Detector Modules

| Detector | Vulnerability Class | OWASP |
|---|---|---|
| `authDetector` | Broken Authentication | A07 |
| `cachePoisoningDetector` | Web Cache Poisoning | A05 |
| `clickjackingDetector` | Clickjacking / Frame Protection | A05 |
| `commandInjectionDetector` | OS Command Injection | A03 |
| `componentDetector` | Vulnerable / Outdated Components | A06 |
| `csrfDetector` | Cross-Site Request Forgery | A01 |
| `deserializationDetector` | Insecure Deserialization | A08 |
| `fileUploadDetector` | Insecure File Upload | A04 |
| `idorDetector` | Insecure Direct Object Reference | A01 |
| `infoDisclosureDetector` | Sensitive Information Disclosure | A05 |
| `logicDetector` | Business Logic Vulnerability | A04 |
| `openRedirectDetector` | Open Redirect | A01 |
| `passwordResetDetector` | Weak Password Reset | A07 |
| `privilegeDetector` | Broken Access Control | A01 |
| `ssrfDetector` | Server-Side Request Forgery | A10 |
| `validationDetector` | Input Validation / Error Handling | A03 |
| `xxeDetector` | XML External Entity Injection | A05 |

### Smart Fingerprint Engine

Before launching a URL scan, A.O Sentinel can auto-detect the target tech stack from HTTP response headers and cookies, then suggest the most relevant detector subset:

| Detected Tech | Detection Signal | Suggested Detectors |
|---|---|---|
| WordPress | `X-Generator`, `wp-content` in `Link` header, `wordpress_*` cookie | File Upload, XSS, Path Traversal, Secret scanning |
| PHP | `X-Powered-By: PHP`, `PHPSESSID` cookie | File Upload, Path Traversal, Command Injection |
| Node.js | `X-Powered-By: Express` | SSRF, Open Redirect, JWT, GitHub Token |
| ASP.NET | `X-Powered-By: ASP.NET` | XSS, Path Traversal, Command Injection |
| Java | `JSESSIONID` cookie | SSRF, Command Injection, AWS credentials |
| Python / Django | `csrftoken`, `sessionid` cookies | SSRF, Command Injection, DB secrets |
| Laravel | `laravel_session` cookie | File Upload, Path Traversal, DB secrets |
| Nginx / Apache | `Server` header | Path Traversal, File Upload |

### Scan Intensities

| Mode | Behavior | Use Case |
|---|---|---|
| **Stealth** | Maximum delay between probes | Avoid WAF/IDS detection |
| **Balanced** | Moderate delay (default) | Standard security assessment |
| **Insane** | No delay — maximum speed | Internal networks / CTF |

---

## 7. Installation & Setup

### Prerequisites

| Requirement | Version | Notes |
|---|---|---|
| Node.js | ≥ 18.x | LTS recommended |
| npm | ≥ 9.x | Bundled with Node.js |
| Ollama | Latest | [ollama.ai](https://ollama.ai) |
| Llama3 model | `llama3` | ~4.7 GB download |

### Step 1 — Install Ollama & Pull Llama3

```bash
# Install Ollama (see https://ollama.ai for platform-specific instructions)
# Then pull the Llama3 model:
ollama pull llama3

# Verify Ollama is running and the model is available:
ollama list
```

### Step 2 — Clone & Install Dependencies

```bash
git clone https://github.com/AhmadOglah/ao-sentinel.git
cd "ao-sentinel"

# Install all dependencies (backend + frontend) in one command:
npm run install:all
```

### Step 3 — Start the Application

```bash
# Start both backend (port 5000) and frontend (port 3000) concurrently:
npm run dev
```

The terminal will show color-coded output from both processes:

```
[BACKEND]  A.O Sentinel server running on port 5000
[FRONTEND] ➜  Local:   http://localhost:3000/
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Step 4 — Verify Ollama Connection

Ensure Ollama is running before starting a scan:

```bash
ollama serve          # starts the Ollama server (if not already running as a service)
```

If Ollama is offline, the scanner gracefully falls back: findings are retained at `HIGH` severity with the note *"Ollama offline — finding retained by default."*

### Running Services Individually

```bash
npm run backend     # Node.js only (port 5000)
npm run frontend    # Vite dev server only (port 3000)
```

---

## 8. GPU Acceleration

A.O Sentinel's AI pipeline runs **100% on your local GPU** via Ollama. GPU acceleration provides a dramatic performance improvement over CPU-only inference, which is especially important when auditing large codebases with many findings.

### Enabling GPU Acceleration

**NVIDIA (CUDA):**
```bash
# Ollama auto-detects NVIDIA GPUs — no extra configuration needed.
# Verify GPU is being used:
ollama run llama3 "test"
# Check GPU utilization with:
nvidia-smi
```

**AMD (ROCm — Linux):**
```bash
# Ollama supports AMD GPUs via ROCm on Linux.
# Follow the Ollama ROCm setup guide at https://ollama.ai/blog/amd-preview
```

**Apple Silicon (Metal):**
```bash
# Ollama natively uses Metal on M1/M2/M3/M4 Macs — zero configuration.
```

### Performance Comparison

| Hardware | Llama3 Tokens/sec | ~Time per Finding | ~100 Findings |
|---|---|---|---|
| CPU only (8-core) | ~3–8 t/s | ~45–60 sec | ~90 min |
| NVIDIA RTX 3070 | ~40–60 t/s | ~5–8 sec | ~10 min |
| NVIDIA RTX 4090 | ~80–120 t/s | ~2–4 sec | ~5 min |
| Apple M2 Pro | ~25–40 t/s | ~8–12 sec | ~15 min |

> The AI concurrency is set to `2` in `secretScanner.js` to match Llama3's single-threaded nature. Increasing `AI_CONCURRENCY` beyond 2 on a CPU-only setup will cause timeouts.

---

## 9. Privacy & Ethics

### Zero Data Leakage — Guaranteed

A.O Sentinel was designed from the ground up with **zero-trust data handling**:

```
Your Code  ──►  A.O Sentinel  ──►  Llama3 (localhost:11434)
                                          │
                                    ┌─────▼─────┐
                                    │ YOUR GPU  │
                                    │ (offline) │
                                    └───────────┘
                    ✗ No OpenAI  ✗ No Anthropic  ✗ No cloud APIs
```

| What happens to your code? | Answer |
|---|---|
| Is any code sent to OpenAI / Claude / external APIs? | **Never.** All AI calls go to `localhost:11434` |
| Does the scanner need internet access? | **No.** After initial Ollama + model installation |
| Are scan results stored anywhere? | **No.** Results exist only in browser memory and the downloaded PDF |
| Can A.O Sentinel scan air-gapped environments? | **Yes.** Fully offline after setup |
| Is the PDF generated client-side? | **Yes.** pdfmake runs entirely in the browser — no server sees the report data |

### Why This Matters for Corporate Environments

For organizations like **Artl Studio** and enterprise clients with strict data classification policies:
- Source code is your most sensitive intellectual property
- Cloud-based scanners create legal and compliance exposure under GDPR, HIPAA, and PCI-DSS
- A.O Sentinel provides audit-grade security analysis with **the same privacy guarantees as a local IDE plugin**

### Responsible Disclosure

A.O Sentinel is intended for:
- Security auditing of **codebases and systems you own or have explicit written authorization to test**
- Internal security reviews and developer education
- CTF competitions and authorized penetration testing engagements

Unauthorized use against third-party systems is illegal and unethical.

---

## 10. API Reference

### POST `/api/scanner/run` — File / Directory Scan

**Request:**
```json
{
  "path": "/absolute/path/to/project",
  "enabledDetectors": ["secret-generic-api-key", "secret-password", "secret-db-connection"],
  "aiVerification": true
}
```

**Response:**
```json
{
  "scanType": "file",
  "scannedPath": "/absolute/path/to/project",
  "totalFindings": 7,
  "findings": [
    {
      "file": "/path/to/config.js",
      "line": 12,
      "type": "Database Connection String",
      "content": "mongodb://admin:secret@prod.host/db",
      "contextBlock": "File: config.js...\n>>> 12 | ...",
      "severity": "CRITICAL",
      "logic_analysis": "Credentials embedded in mongoose.connect() call...",
      "remediation_code": "mongoose.connect(process.env.MONGODB_URI)",
      "pii_detected": false
    }
  ],
  "severitySummary": { "critical": 2, "high": 3, "medium": 1, "low": 1 },
  "piiFindings": 1,
  "executiveSummary": "Three-sentence CTO briefing...",
  "executiveBullets": ["Rotate...", "Revoke...", "Remediate..."],
  "attribution": "Deep AI Analysis by Ahmad Oglah Abuzaid",
  "aiVerification": { "enabled": true, "confirmed": 7, "discarded": 3 }
}
```

### POST `/api/scanner/probe` — URL Active Probe

**Request:**
```json
{
  "url": "https://target.example.com",
  "enabledDetectors": ["header-scanner", "xss-probe", "ssrf", "file-upload"],
  "scanIntensity": "balanced"
}
```

### POST `/api/scanner/fingerprint` — Tech Stack Detection

**Request:**
```json
{ "url": "https://target.example.com" }
```

**Response:**
```json
{
  "tech": ["WordPress", "PHP", "Nginx"],
  "suggestedDetectors": ["header-scanner", "xss-probe", "file-upload", "path-traversal"],
  "httpStatus": 200
}
```

### POST `/api/ai/chat` — SSE Streaming Chat

**Request:**
```json
{
  "contextBlock": "File: config.js...\n>>> 12 | ...",
  "userMessage": "How could an attacker exploit this?"
}
```

**Response** (`Content-Type: text/event-stream`):
```
data: {"token":"An"}

data: {"token":" attacker"}

data: {"token":" with"}

data: {"done":true}
```

---

## 11. Project Structure

```
A.O Sentinel/
├── package.json              # Monorepo root: concurrently dev scripts
│
├── backend/
│   ├── index.js              # Express server (port 5000)
│   ├── package.json          # Backend dependencies
│   ├── Controller/
│   │   ├── scannerController.js  # File scan, URL probe, fingerprint handlers
│   │   └── aiController.js       # SSE streaming chat handler + CHAT_SYSTEM_PROMPT
│   ├── Routes/
│   │   ├── scannerRoutes.js      # /api/scanner/*
│   │   └── aiRoutes.js           # /api/ai/chat
│   └── Utils/
│       ├── secretScanner.js      # 4-phase AI pipeline + all system prompts
│       ├── urlFuzzer.js          # Active probe orchestrator
│       ├── probeHelpers.js       # Shared HTTP probing utilities
│       └── detectors/            # 17 vulnerability detector modules
│           ├── authDetector.js
│           ├── cachePoisoningDetector.js
│           ├── clickjackingDetector.js
│           ├── commandInjectionDetector.js
│           ├── componentDetector.js
│           ├── csrfDetector.js
│           ├── deserializationDetector.js
│           ├── fileUploadDetector.js
│           ├── idorDetector.js
│           ├── infoDisclosureDetector.js
│           ├── logicDetector.js
│           ├── openRedirectDetector.js
│           ├── passwordResetDetector.js
│           ├── privilegeDetector.js
│           ├── ssrfDetector.js
│           ├── validationDetector.js
│           └── xxeDetector.js
│
└── frontend/
    ├── index.html            # JetBrains Mono font, root mount
    ├── vite.config.js        # Vite 8 + React plugin + Tailwind v4 plugin
    ├── package.json          # Frontend dependencies
    └── src/
        ├── App.jsx               # Root component, scan orchestration
        ├── index.css             # Tailwind v4 + neon-green theme tokens
        ├── config/
        │   └── scanProfiles.js   # ALL_DETECTOR_IDS, preset configurations
        ├── components/
        │   ├── Header.jsx         # Navigation bar
        │   ├── ScanInput.jsx      # File/URL mode switch + scan trigger
        │   ├── ScanConfig.jsx     # Detector checkboxes + intensity selector
        │   ├── ScanningAnimation.jsx
        │   ├── ResultsTable.jsx   # Findings table, Fragment keys, AI panel
        │   ├── FindingChatPanel.jsx  # SSE streaming chat per finding
        │   ├── Statistics.jsx     # File scan summary + PDF export
        │   ├── StatusBar.jsx      # Bottom status bar
        │   ├── UrlResultsTable.jsx
        │   └── UrlStatistics.jsx  # URL scan summary + PDF export
        └── utils/
            └── reportGenerator.js  # pdfmake PDF engine (generateFileReport, generateUrlReport)
```

---

<div align="center">

---

```
██████╗ ███████╗██╗   ██╗███████╗██╗      ██████╗ ██████╗ ███████╗██████╗
██╔══██╗██╔════╝██║   ██║██╔════╝██║     ██╔═══██╗██╔══██╗██╔════╝██╔══██╗
██║  ██║█████╗  ██║   ██║█████╗  ██║     ██║   ██║██████╔╝█████╗  ██║  ██║
██║  ██║██╔══╝  ╚██╗ ██╔╝██╔══╝  ██║     ██║   ██║██╔═══╝ ██╔══╝  ██║  ██║
██████╔╝███████╗ ╚████╔╝ ███████╗███████╗╚██████╔╝██║     ███████╗██████╔╝
╚═════╝ ╚══════╝  ╚═══╝  ╚══════╝╚══════╝ ╚═════╝ ╚═╝     ╚══════╝╚═════╝
```

**Ahmad Oglah Abuzaid**
Computer Science · German Jordanian University
Security Researcher · Intern @ Artl Studio

*"Build tools that respect privacy, understand context, and give engineers the clarity they need to ship secure software."*

[![GitHub](https://img.shields.io/badge/GitHub-AhmadOglah-181717?style=flat-square&logo=github)](https://github.com/AhmadOglah)

---

*A.O Sentinel — Deep AI Analysis by Ahmad Oglah Abuzaid*
*© 2025 Ahmad Oglah Abuzaid · ISC License*

</div>
