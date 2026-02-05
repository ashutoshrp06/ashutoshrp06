## Building systems that count nanoseconds and money

MSc AI at Edinburgh | Ex-Juniper Networks (3 years in real-time telemetry)

Currently writing C++ that doesn't make traders cry

I spend most of my time making computers go fast. Three years at Juniper taught me that network telemetry systems either work in microseconds or they don't work at all. Now I'm at Edinburgh learning how to make them think while they're at it.

**What I actually do**

Systems that process data faster than most people process their morning coffee. Built real-time telemetry infrastructure serving production networks. Currently exploring how AI and low-latency systems can coexist without one killing the other.

**Languages I speak fluently**

C++ when performance matters, Python when sanity matters, C when both are optional. Also SQL, Go, and whatever else the problem demands.

**Things I've shipped**

- Real-time network telemetry processing millions of events per second (Juniper Networks)
- Limit order book simulator because sometimes you need to understand how money moves
- Samantha, an OS assistant that reached hackathon finals by making terminals less hostile
- Distributed sparse matrix engine because some problems are too big for one machine

Currently targeting quant dev roles where microseconds matter and the coffee is probably excellent.

**Find me elsewhere**

[LinkedIn](https://linkedin.com/in/ashutoshpatil3) | Currently in Edinburgh, occasionally in reality


# Limit Order Book Simulator

What happens when you need to understand market microstructure but don't have access to a real exchange. Built in C++ because anything else would miss the point.

## What it does

Simulates order book dynamics with the kind of performance that matters when you're thinking about trading systems. Price-time priority matching, realistic latency modeling, and the ability to replay historical data without setting your laptop on fire.

## Why C++

Because when you're simulating millions of orders, garbage collection is not your friend. Lock-free data structures and cache-aware algorithms make this run faster than you'd expect.

## Technical bits

- Custom memory allocator for order management
- Lock-free order matching engine
- Microsecond-precision event handling
- Support for multiple matching algorithms

Built this to understand how market makers actually work. Turns out they care a lot about queue position.


# Samantha

Terminals are great until you need to do something you haven't memorized. This teaches your OS to speak in something other than exit codes.

## What it actually does

Intelligent terminal assistant that understands natural language and translates it into system operations. Won a place in hackathon finals by making file management less painful than it usually is.

## Architecture

Three-tier system because sometimes simple doesn't scale. Python for the AI layer using LangGraph, Go for filesystem operations where performance matters, and a coordination layer that keeps them from fighting.

## Technical highlights

- Hybrid Python-Go architecture for speed where it matters
- LangGraph for agentic reasoning about user intent
- Async filesystem operations in Go
- Natural language to shell command translation

Because life's too short to remember every flag for every command.


