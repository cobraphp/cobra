# cobraPHP

**The pragmatic, lean PHP framework for real-world solutions.**

🌐 https://cobraphp.dev  
📺 https://youtube.com/@tech-jeweler  

---

## What is cobraPHP?

cobraPHP is a lightweight PHP framework focused on simplicity, consistency and real-world usability.

It is designed for developers who want to build working systems — not fight framework complexity.

---

## Why cobraPHP?

cobraPHP started from practical experience:

- appreciation for the simplicity of CodeIgniter 3 + HMVC
- need to work with modern PHP versions
- frustration with heavy dependency chains and complexity

cobraPHP brings back a more direct way of building software:

- lean instead of bloated  
- structured, but not over-engineered  
- flexible without forcing tools  

---

## Core Ideas

- **Pragmatic** – solve real problems  
- **Lean** – minimal overhead  
- **Consistent** – easy to understand  
- **Optional complexity** – nothing forced  

---

## Key Capabilities

- HMVC-inspired modular structure  
- Optional Composer usage (not required)  
- Works with or without database  
- Built-in SQLite bootstrap (auto-created)  
- RedBeanPHP ORM integration  
- Multi-datastore architecture  
- REST API layer (`CApi`)  
- CLI support for jobs and automation  
- Auto-documentation system  
- HTTP client included  
- Global helper functions (`cb_*`)  

---

## Dynamic Datastore Switching

cobraPHP is built with integration scenarios in mind.

An application can work with multiple datastores at the same time and even switch between them during runtime.

This enables use cases such as:

- migrating data between systems
- synchronizing different data sources
- transforming data between incompatible systems
- building integration layers between APIs and databases

A datastore is not limited to a database. It can represent:

- SQL databases (SQLite, MySQL, PostgreSQL)
- file-based storage (CSV or similar concepts)
- external systems accessed via HTTP APIs

This allows cobraPHP to act as a **bridge between systems**, not just a backend.

---

## One Application – Multiple Execution Modes

cobraPHP automatically adapts to how it is invoked.

The same application can run as:

- a web application (user interaction)
- a REST API (system integration)
- a CLI process (cron jobs, background tasks)

This makes it possible to build systems that:

- are configured and operated via UI
- execute automated jobs in the background
- exchange data with external systems via APIs

All within a single, consistent codebase.

---

## Modular UI Composition (HMVC)

cobraPHP uses an HMVC-inspired approach to build interfaces.

- components are organized in modules
- views can be composed dynamically
- different templates can be used per context

This allows flexible UI construction without losing structure.

---

## Datastore Concept

cobraPHP does not think only in databases.

A datastore can be:

- SQLite, MySQL, PostgreSQL  
- CSV or file-based storage  
- external APIs via HTTP  

This enables flexible integration scenarios beyond classical database usage.

---

## Who is it for?

- developers building internal tools  
- integration-heavy environments  
- pragmatic engineers  
- teams with limited time for framework overhead  

---

## Status

⚠️ cobraPHP is currently under active development.

This repository focuses on:

- concept
- architecture
- philosophy

---

## Learn more

👉 See official page for more 

---

## Vision

cobraPHP does not try to compete with other frameworks.

It aims to help developers bring solutions to life — quickly, consistently and pragmatically.
