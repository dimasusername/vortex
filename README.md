# Limit Order Book & Matching Engine

**Codename:** `vortex`

## Purpose

Build a high-performance limit order book (LOB) with a price-time priority
matching engine. This is the central nervous system of any trading platform.

## Constraints

- **Language**: C++17 minimum. C++20 features permitted where they improve
clarity or correctness (concepts, ranges).
- **Dependencies**: Zero runtime dependencies. Standard library only.
- **Build system**: CMake. The project must build cleanly with
`-Wall -Wextra -Wpedantic -Werror`.
- **Platform**: Linux x86_64, little-endian, `__builtin_expect` and similar
compiler intrinsics where justified.
