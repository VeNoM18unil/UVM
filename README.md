# GPDMA (General Purpose Direct Memory Access) IP Verification
### Description
A General-Purpose Direct Memory Access (GP DMA) controller is a specialized hardware component commonly used in digital systems and microcontroller designs to efficiently facilitate data transfers between various peripherals, memory locations, or other devices within a computing system. GP DMA controllers are designed to offload data transfer tasks from the Central Processing Unit (CPU) or controller, thereby improving system performance and reducing CPU overhead.

### DMA Module
1. DMA FSM
2. DMA Buffer
3. Control & Status Registers

## Folder Structure
SPU/ <br>
├── RTL/             RTL design files <br>
└── VERIFICATION/ <br>
    ├── UVM/           # UVM testbench components <br>
    │   ├── env/           # Environment components (scoreboard, monitors, etc.) <br>
    │   ├── sequences/     # UVM sequences and stimuli <br>
    │   ├── spu_agent/     # Agent for SPU interface <br>
    │   ├── test/          # UVM tests <br>
    │   ├── top/           # Top-level UVM testbench <br>
    │   └── package/       # UVM package/type definitions <br>
    └── SIM/           # Simulation directory (scripts, makefiles, log outputs) <br>
