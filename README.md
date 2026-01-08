# Idempotent-DotNet

Idempotent.Net is a modular .NET library for implementing **idempotent operations** in distributed systems.

It provides a small, well-defined core and multiple storage providers so applications can safely handle retries, duplicate requests, and at-least-once delivery without introducing side effects.

---

## 🧩 Packages

Each of the below packages can be used independently where appropriate.

#### Abstractions & Contracts

- 📦 **Idempotent.Core**

#### Stores

- 💾 **Idempotent.InMemory**
- 🗄 **Idempotent.Redis**
- 🛢 **Idempotent.SqlServer**
- ☁️ **Idempotent.DynamoDb**

#### Integration

- 🌐 **Idempotent.AspNetCore**

---

## 📘 Documentation

It provides below for each package:
- Brief Overview
- Quick Start Guide
- Complete API Reference (DocFX-generated)

To get started, click [**here**](https://idempotent-labs.github.io/idempotent-dotnet/index.html).
