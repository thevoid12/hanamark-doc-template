---
created_on: 2024-12-26
---

# Installation

Hanamark is distributed as a single binary with no dependencies.

## Download Binary (Recommended)

Download the pre-built binary for your platform from the [GitHub Releases](https://github.com/thevoid12/hanamark/releases) page.

| Platform | Download |
|----------|----------|
| macOS (Intel) | `hanamark-darwin-amd64` |
| macOS (Apple Silicon) | `hanamark-darwin-arm64` |
| Linux (64-bit) | `hanamark-linux-amd64` |
| Windows (64-bit) | `hanamark-windows-amd64.exe` |

### Setup

```bash
# Download and make executable (macOS/Linux)
chmod +x hanamark-darwin-arm64
mv hanamark-darwin-arm64 hanamark

# Verify installation
./hanamark -version
```

> **No dependencies required** - the binary is self-contained.

## Build from Source

Only needed if you want to build from source or contribute to development.

### Prerequisites

- Go 1.20 or higher

### Build Steps

```bash
# Clone repository
git clone https://github.com/thevoid12/hanamark.git
cd hanamark

# Build binary
go build -o hanamark .
```

Or using Make:

```bash
make build
```

## Verify Installation

```bash
./hanamark -version
```

This should display the current version of Hanamark.
