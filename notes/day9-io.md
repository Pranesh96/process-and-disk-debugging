## Day 9 – IO and Wait States

Key indicators:
- %wa in top
- %util in iostat
- await latency

Important realizations:
- High load does not mean high CPU
- IO wait blocks everything
- Disk can bottleneck CPU

Production mindset:
- Identify IO pressure before scaling CPU
