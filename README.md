# Linux-to-the-Extreme
In this project we are literally going to build Linux from the ground up.

## Project Structure
```bash
Linux-to-the-Extreme/
│── arch/                     
│   ├── x86_64/                # x86_64 Bootloader & Kernel
│   │   ├── bootloader.asm  
│   │   ├── kernel.c         
│   │   ├── Makefile          
│   ├── arm64/                 # ARM64 Bootloader & Kernel
│   │   ├── bootloader.S    
│   │   ├── kernel.c        
│   │   ├── Makefile         
│── build/                     # Compiled binaries
│── docs/                      # Documentation
│── scripts/                   # Helper scripts (build automation, debugging)
│── tools/                     # Custom tools (e.g., disk image creation)
│── shared/                    # Code shared across architectures
│── Makefile                   # Top-level build system
│── README.md
│── LICENSE
```
