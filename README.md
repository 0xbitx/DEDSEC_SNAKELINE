
<p align="center">
<img src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExdjUwczU2Y3hwaTBwMjMwb25tc2J5b203bzk5c3F4MHFudDJuenBucCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/26BRwuIcSGcxGNaEM/giphy.gif", width="400", height="400">
</p>

<h1 align="center">SNAKELINE</h1>
<h4 align="center">A utility that transforms complex Python-based malware into compact one-liner commands</h4>

### DESCRIPTION
SNAKELINE is a specialized obfuscation and transformation tool designed for security research and penetration testing. It converts complex Python malware code into single-line commands, enabling stealthier payload delivery and execution in restricted environments where traditional multi-line scripts may be blocked or detected.

### Key Features:
- **Memory-Only Execution**: Payloads execute directly in memory without touching the disk, leaving no forensic traces
- **Zero-Width Character Obfuscation**: Uses invisible Unicode characters to hide code logic while maintaining functionality
- **One-Liner Transformation**: Converts multi-line Python scripts into single command-line executables
- **Payload Self-Removal**: time-based auto-destruction (e.g., 1 hour) for complete trace eradication
- **Zero-Dependency Architecture**: Pure Python implementation with no external library requirements
  
### Use Cases:
- Security research and malware analysis
- Penetration testing and red team operations
- Evasion technique development
- Educational purposes in cybersecurity

### INSTALLATION
    git clone https://github.com/0xbitx/DEDSEC_SNAKELINE.git
    cd DEDSEC_SNAKELINE
    pip3 install tabulate
    chmod +x dedsec_snakeline
    ./dedsec_snakeline
    
### TESTED ON FOLLOWING
* Kali Linux 
* Parrot OS 
  
## Legal Disclaimer

This tool is intended for educational and security research purposes only. Unauthorized usage may be illegal in your jurisdiction. The author is not responsible for any misuse of this tool.
