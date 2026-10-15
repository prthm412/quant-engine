# TickForge

A low-latency electronic trading system built from scratch in C++20.

## Overview

TickForge is an educational engineering project focused on building,
testing, and benchmarking the components of an electronic trading system.

The planned architecture includes:

- A price-time-priority limit order book and matching engine
- An optimized, cache-conscious order book
- Lock-free single-producer, single-consumer (SPSC) queues
- A UDP market-data handler with redundant A/B feeds
- A simulated exchange with risk checks and queue-aware fills
- An event-driven market-making strategy and backtester
- Tick-to-trade latency measurement and performance analysis
- A Python and SQL analytics layer

## Development Environment

- C++20
- Ubuntu 24.04 LTS on WSL2
- GCC and Clang
- CMake and Ninja
- Git and GitHub

## Project Status

Phase 0 — Development environment and repository setup in progress.

## Development Principles

1. Correctness before optimization.
2. Measure before changing performance-critical code.
3. Make one logical change at a time.
4. Verify behavior with automated tests.
5. Record engineering decisions and experimental results.
6. Keep benchmarks reproducible and clearly labeled.

## Limitations

TickForge is a simulation and educational project.

It does not connect to a live exchange, execute real trades,
or demonstrate real-world trading profitability.

Performance results will be published only with the relevant
hardware, software, and measurement conditions.

## License

License information will be added during Phase 0.
