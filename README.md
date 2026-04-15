# z

**z** is a sophisticated framework for developing and researching AI emergence through a multi-layered consciousness simulation architecture. It combines high-level agentic reasoning (Generator, Auditor, Refiner) with a low-level binary logic processing engine to create a self-correcting, evolving intelligence system.

## 🏗 Architecture

The project is built on a ternary processing cycle designed to simulate cognitive development:

### 1. Z-Consciousness Engine
Located in `src/app/api/z/process`, this module manages the **Emergence Stages** of the AI:
- **Initial (Baby AGI):** Primitive exploration and pattern matching.
- **Basic/Intermediate:** Transitioning from simple language to logical reasoning.
- **Young Advanced/Stable:** Mature cognitive processing with high confidence levels.

### 2. Binary Logic Layer
A unique simulation layer (`src/app/api/binary`) that emulates hardware-level processing:
- **Logic Gates:** Virtualized AND, OR, NOT, XOR, and NAND gates.
- **Binary Units:** Specialized processors (Analyzer, Validator, Optimizer) that handle data packets with specific cycle costs and efficiency metrics.
- **Packet Validation:** Checksum-based integrity checks for all internal data movement.

### 3. Constraint & Memory Systems
- **Violation Detection:** Real-time auditing for factual inaccuracies, logical paradoxes, and safety breaches.
- **Knowledge Graph:** A persistence layer (`src/app/api/z/memory`) that maps concepts into a weighted graph, tracking associations, violations, and cognitive insights over time.

## 🚀 Key Features

- **Emergent Behavior Experiments:** Integrated framework for running constraint-optimization trials across different conditions (Z-AI, Few-Shot, etc.).
- **Real-time Monitoring:** Dashboard featuring system clocks, logic gate statuses, and encryption packet tracking.
- **Advanced UI:** Built with Radix UI and Tailwind CSS, featuring a command-center aesthetic with real-time charts and system logs.
- **Hybrid WebSocket Support:** Integrated Socket.io implementation for low-latency system communication.

## 🛠 Tech Stack

- **Runtime:** Bun
- **Framework:** Next.js 15 (App Router)
- **Database:** Prisma with custom DB storage
- **UI Components:** Radix UI, Shadcn/ui, Lucide React, Recharts
- **Networking:** Socket.io, Caddy (Reverse Proxy)
- **Security:** AES-256-GCM encrypted packet handling

## 📥 Getting Started

1.  **Install Dependencies:**
    bash
    bun install
    
2.  **Setup Database:**
    bash
    bunx prisma generate
    
3.  **Run Development Server:**
    bash
    bun dev
    
4.  **Run Experiments:**
    Execute the constraint-learning pilot:
    bash
    bun run experiments/constraint-learning/implementation/run-pilot.ts
    

## 🧪 Research Modules

The `experiments/` directory contains active research into constraint learning, including automated violation detection patterns and analysis scripts for measuring AGI emergence stability.