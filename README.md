# Idempotent-DotNet

A .NET idempotency framework for safely handling retries across HTTP APIs and distributed systems.
This repository contains the full source code for the **Idempotent** libraries, including core abstractions, persistence providers, and ASP.NET Core integration.

---

## Packages

| Package | Description |
|------|-------------|
| 📦 **Idempotent.Core** | Core idempotency model, workflows, and persistence abstractions |
| 💾 **Idempotent.InMemory** | In-memory store (development & testing) |
| 🗄 **Idempotent.Redis** | Redis-backed distributed store |
| 🛢 **Idempotent.SqlServer** | SQL Server persistence |
| ☁️ **Idempotent.DynamoDb** | DynamoDB persistence |
| 🌐 **Idempotent.AspNetCore** | ASP.NET Core middleware and integration |

---

## Documentation

📘 **Full documentation, guides, and API reference are available here:**

👉 [**Idempotent-DotNet**](https://idempotent-labs.github.io/idempotent-dotnet/index.html)

The documentation includes:
- Quick start setup
- Complete API reference (DocFX-generated)
