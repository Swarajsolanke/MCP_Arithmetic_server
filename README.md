# 🧮 MCP Arithmetic Server

A basic Multi-Client Protocol (MCP) server that performs arithmetic operations such as addition, subtraction, multiplication, and division.

> ⚡ Built in Python using [`uv`](https://github.com/astral-sh/uv) (a fast modern Python package manager).  
> 🧪 Tested locally using **Claude Desktop** for interaction and verification.

---

## 🚀 Features

- Accepts requests from multiple clients (MCP-style interaction).
- Supports the following operations:
  - Addition
  - Subtraction
  - Multiplication
  - Division
- Supports both interactive/local testing (Claude Desktop) and CLI/API-based communication.
- Fast environment setup with `uv`.

---

## 🛠️ Tech Stack

- Python 3.8+
- `uv` – modern Python package manager
- Your choice of backend logic (e.g., socket server, FastAPI, etc.)
- Claude Desktop – for testing and simulation of client/server communication

---

## 📦 Installation

### Step 1: Install `uv` (if not already installed)

```bash
curl -Ls https://astral.sh/uv/install.sh | sh
