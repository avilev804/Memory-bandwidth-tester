# Memory Throughput Analyzer

**Memory Throughput Analyzer** is a lightweight Windows command-line utility that measures your system's memory **read/write throughput**, and reports key specifications including:

- ** ConfiguredClockSpeed** – The memory module’s configured operating speed
- ** Speed** – Actual current speed reported by the system
- ** Theoretical Bandwidth** – Calculated estimate based on module width and frequency
- ** Tests memory for integrity.

uses streaming stores and loads bypassing the cache to get actual dram throughput and not cache assisted fake throughput as reported by other popular "benchmarking" tools. it uses write-combined memory allocation to at least batch memory writes to speed it up. but no cache is involved which is crucial point.

## 🚀 Usage
1. Download `memtestspeed.exe`
2. Run it as Administrator
3. View throughput and configuration details printed to the console

No installer. No dependencies. No nonsense.

## 🔓 License
This utility is provided **completely free** with no usage restrictions. Share it, use it, break it, remix it.

## 🛠 Notes
- Based on native Windows WMI queries
- Recommended for DDR4/DDR5 systems for accurate results
