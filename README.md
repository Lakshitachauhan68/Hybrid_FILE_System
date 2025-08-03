
# Hybrid File System

**🗓️ Project Dates:** March 2025 – April 2025  
**⚙️ Tech:** C · simulated disk in memory · basic OS file‑system simulations

## Quick Description

This project simulates a very small operating‑system‑style file system that blends two allocation styles:

- A **central FAT table** that links data blocks in chain form (great for small files)  
- Per‑file **inode structures** (with direct and indirect pointers) for efficient handling of larger files

That makes it easy to see how a system can transition from simple FAT-based files to more scalable inode-based files based on file size.
