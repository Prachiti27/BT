# Blockchain in Go

A simple blockchain implementation written in Go to understand the core concepts behind blockchain technology.

## Run Locally

```bash
git clone <repository-url>
cd BT
go mod tidy
go run main.go
```

Create a `.env` file:

```env
ADDR=8080
```

The server will start on:

```text
http://localhost:8080
```

## API

### Get Blockchain

```http
GET /
```

### Add Block

```http
POST /
Content-Type: application/json
```

Example:

```json
{
  "BPM": 75
}
```

## Purpose

This project is primarily for learning how blocks, hashes, chain validation, and a basic blockchain API work together in Go.