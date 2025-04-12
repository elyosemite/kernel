# BNSD - Brazilian Northeast Software Distribution

[![Build Status](https://img.shields.io/github/actions/workflow/status/yourusername/bnsd/build.yml?style=flat-square)](https://github.com/yourusername/bnsd/actions)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg?style=flat-square)](https://www.gnu.org/licenses/gpl-3.0)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://makeapullrequest.com)

**An educational operating system designed to teach computer science students worldwide about OS development, inspired by the rich culture of Brazil's Northeast region.**

---

## About BNSD

BNSD is a didactic operating system kernel and userspace environment built from scratch, focusing on:
- **Education**: Clear code structure with extensive documentation
- **Cultural Representation**: Incorporates Brazilian Northeast symbols and metaphors
- **Simplicity**: Small codebase optimized for learning (not production use)
- **Community-Driven**: Encourages global student contributions

**Explicit Non-Goals**  
- Not a competitor to Linux/Windows  
- Not optimized for high performance  
- Not recommended for mission-critical systems  

---

## Key Features

### Kernel Features
- Modular monolithic design (Linux-inspired)
- Preemptive multitasking
- Virtual memory management
- Device driver framework
- Ext2-inspired simple filesystem (BNFS)

### Educational Tools
- Interactive kernel debugger
- Step-by-step build tutorials
- Architecture diagrams
- Cultural explanations in code comments
- QEMU-ready configurations
---

## Installation

### Prerequisites
- x86_64 system (or QEMU virtual machine)
- GCC cross-compiler
- NASM assembler
- GNU Make
- QEMU (for emulation)

### Quick Start
```bash
# Clone repository
git clone https://github.com/yourusername/bnsd.git
cd bnsd

# Build system
make all

# Run in QEMU
make run
