## Day 7 – Memory Debugging

Important truth:
- High memory usage is normal
- Low available memory is dangerous

Commands I trust:
- free -m
- ps aux --sort=-%mem
- vmstat
- dmesg

Observations from my system:
- Chrome used up the most RAM, however there was enough avilable storage
- Swap was empty and was not in active use

Production mindset:
- Never clear cache blindly
- Always check OOM logs
