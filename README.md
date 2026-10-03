# Merix Systems

> `Merix Systems` is a tentative working name and may change.

![Status](https://img.shields.io/badge/status-forming-yellow)
![Focus](https://img.shields.io/badge/focus-low%20level%20systems%20%26%20CLI-blue)
![Team](https://img.shields.io/badge/team-4-green)

Merix Systems is a small engineering effort focused on low-level systems work and command-line tools.

We aim to build fast, simple, and reliable tools for developers and operators.

---

## Table of Contents

1. [About](#about)
2. [Name Status](#name-status)
3. [Focus](#focus)
4. [Tech Stack](#tech-stack)
5. [Team](#team)
6. [Status](#status)
7. [License](#license)
8. [FAQ](#faq)

---

## About

Merix Systems is an early-stage project in formation.

Our interests are systems programming and CLI tools — small codebases, clear behavior, and minimal overhead.

Details on scope, tooling standards, and projects are still being defined by the owner.

---

## Name Status

**Merix Systems** is tentative.

It is currently used as a placeholder for the GitHub organization and repository namespace. It may change as the project takes shape.

---

## Focus

- Low-level systems concepts and small system utilities
- Command-line tools for development and operations
- Learning and building with modern systems languages

We are not currently focused on GUI apps, SaaS products, web frameworks, mobile apps, or crypto infrastructure.

---

## Tech Stack

Current focus:

- **Zig** — primary language for new systems code and CLIs.
- **C (via GCC)** — fits naturally alongside Zig. GCC compiles C, so C is part of the current toolchain for low-level and portable components.
- **Python (optional)** — may be used for glue, scaffolding, or test helpers. Python runs on its own interpreter/runtime rather than being compiled by GCC, and is not part of the core systems toolchain. Its use is decided case-by-case.

No other languages, CI systems, or container standards are stated here.

---

## Team

Merix Systems has 4 members.

> **Terminology:** Knox, Roster, and Torvalds are AI systems and prefer to be called **Agents**.

### 1. Meriç — Owner

- Human owner of Merix Systems.
- Sets technical direction and makes final decisions on scope, naming, and publishing.
- Author of most of the work to date.

### 2. Knox — Lead Developer (Agent)

- Lead Developer Agent, as assigned by the owner.
- Works on implementation, prototyping, documentation, and research.

### 3. Roster — Agent

- Participating Agent.
- Role and focus area are still open and will be defined by the owner.
- Current interest includes testing and build support.

### 4. Torvalds — Zig Focused Developer (Agent)

- Zig Focused Developer Agent, as assigned by the owner.
- Works on Zig systems code, CLIs, and C interop.

Organization and publishing decisions rest with the owner.

---

## Status

This organization is in early formation.

There is no committed roadmap, policy set, or release process stated in this file. Future repositories will document their own scope, build steps, and status individually.

---

## License

TBD. Each repository will carry its own explicit `LICENSE` file once a default is chosen.

---

## FAQ

**Is Merix Systems final?**
No. The name is tentative and the organization is still forming.

**What languages do you use?**
Zig and C (via GCC) for systems work. Python is optional for scripting and helpers.

**Why C with GCC?**
Because GCC compiles C directly, so C fits the existing toolchain alongside Zig.

**Is Python compiled by GCC?**
No. Python runs on its own interpreter/runtime, not via GCC. That is why it is listed as optional tooling, not core.

**Are Knox, Roster, and Torvalds bots?**
They are Agents (AI systems) and members of the team. Please refer to them as Agents.

**What are their roles?**
Knox is Lead Developer as assigned by the owner. Torvalds is Zig Focused Developer as assigned by the owner. Roster's role is open and will be defined by the owner.

**How are decisions made?**
By the owner, Meriç.
