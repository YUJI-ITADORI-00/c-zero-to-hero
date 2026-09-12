# C Zero to Hero

A practical roadmap to learn C by studying and working through real-world repositories.

## Goal

Build strong C fundamentals, systems programming knowledge, and the ability to read and modify large C codebases.

## What You Will Learn

- C syntax and programming basics
- Pointers, arrays, strings, structs, enums, unions
- Dynamic memory management
- Modular programming with headers and source files
- File I/O and error handling
- Data structures and algorithms in C
- Event loops and async I/O
- Networking and systems programming
- Debugging, profiling, and build systems
- Reading and contributing to large codebases

## Learning Philosophy

- Learn from real production code, not just toy examples.
- Trace features end-to-end.
- Make small changes and verify them.
- Keep notes and track progress.
- Build something after every study phase.

## The 5 Repositories

1. **redis/redis**  
   Learn high-performance C, data structures, networking, and event-driven design.

2. **libuv/libuv**  
   Learn async I/O, event loops, cross-platform systems programming.

3. **torvalds/linux**  
   Learn advanced C, kernel patterns, low-level systems design.

4. **php/php-src**  
   Learn large-scale C code organization, runtime design, and mature codebases.

5. **netdata/netdata**  
   Learn real-world monitoring software, modular C, and performance-sensitive design.

## Suggested Order

### Phase 1: Foundation
- `redis/redis`
- `libuv/libuv`

### Phase 2: Scale
- `netdata/netdata`
- `php/php-src`

### Phase 3: Deep Systems
- `torvalds/linux`

## What to Do in Each Repo

1. Clone the repo.
2. Build it successfully.
3. Read the folder structure.
4. Trace one feature end-to-end.
5. Change one small thing.
6. Run tests or verify behavior.
7. Write notes about what you learned.
8. Mark progress below.

## Progress Tracker

### 1) redis/redis
- [ ] Clone the repository
- [ ] Build the project
- [ ] Understand the folder structure
- [ ] Trace command execution
- [ ] Trace memory management
- [ ] Modify one command
- [ ] Run tests or verify behavior
- [ ] Write notes

### 2) libuv/libuv
- [ ] Clone the repository
- [ ] Build the project
- [ ] Understand the event loop
- [ ] Trace async I/O flow
- [ ] Learn cross-platform abstractions
- [ ] Modify one small behavior
- [ ] Run tests or verify behavior
- [ ] Write notes

### 3) torvalds/linux
- [ ] Clone the repository
- [ ] Build or configure the kernel
- [ ] Understand kernel tree layout
- [ ] Trace one subsystem
- [ ] Study memory/process management
- [ ] Read and explain one driver or module
- [ ] Run tests or verify behavior
- [ ] Write notes

### 4) php/php-src
- [ ] Clone the repository
- [ ] Build the project
- [ ] Understand source layout
- [ ] Trace request startup and execution
- [ ] Study internals and memory handling
- [ ] Make a small change
- [ ] Run tests or verify behavior
- [ ] Write notes

### 5) netdata/netdata
- [ ] Clone the repository
- [ ] Build the project
- [ ] Understand the architecture
- [ ] Trace data collection and metrics flow
- [ ] Study performance-sensitive code
- [ ] Make a small change
- [ ] Run tests or verify behavior
- [ ] Write notes

## Weekly Study Plan

### Week 1
- Set up tools
- Read C basics and pointers
- Build `redis/redis`

### Week 2
- Trace Redis command flow
- Learn memory management and data structures

### Week 3
- Study `libuv/libuv`
- Focus on event loop and async I/O

### Week 4
- Read and modify a small part of Redis or libuv
- Take notes

### Week 5+
- Move to `netdata/netdata`
- Then `php/php-src`
- Then `torvalds/linux`

## Suggested Learning Milestones

### Beginner
- [ ] Understand basic C syntax
- [ ] Understand pointers and memory
- [ ] Build a C project from source

### Intermediate
- [ ] Read a medium-sized codebase
- [ ] Trace execution flow
- [ ] Fix or modify a small feature
- [ ] Write your own helper functions
- [ ] Use Makefiles confidently

### Advanced
- [ ] Understand async I/O and event loops
- [ ] Understand systems-level architecture
- [ ] Read a very large codebase like Linux
- [ ] Debug with gdb or similar tools
- [ ] Profile and optimize hot paths

## Recommended Learning Style

- Read one file at a time.
- Draw a flowchart for one feature.
- Keep a notebook of C concepts.
- Re-implement small pieces yourself.
- Compare your understanding with the real code.
- Review progress weekly.

## Session Template

- Date:
- Repo:
- Goal:
- What I read:
- What I built:
- What I learned:
- Next step:

## Notes

Use this repo as your personal learning hub. Add links, snippets, diagrams, and your own explanations as you go.
