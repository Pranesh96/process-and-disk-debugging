## Day 10 – Incident Investigation & RCA

Incident summary:
- Time window: 02:00–02:30
- Symptom: System reported as slow

Evidence collected:
- uptime showed normal load
- CPU idle > 80%
- Memory available > 40%
- Disk usage below 70%
- No IO wait spikes observed

Findings:
- CPU: normal, not saturated
- Memory: sufficient, no swap pressure
- Disk: adequate free space and inodes
- IO: no significant wait

Root cause:
- No system-level resource exhaustion detected
- Slowness likely application-level or external dependency

Corrective action:
- No system changes required
- Recommend application log review

Preventive measures:
- Add application-level monitoring
- Correlate system metrics with app metrics

Key lesson:
- Always prove system health before blaming infrastructure
