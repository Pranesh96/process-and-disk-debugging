## Day 8 – Disk and Filesystem Debugging

First commands I run:
- df -h
- df -i
- du -h --max-depth=1

Key realizations:
- Disk space and inodes are different
- Logs are the biggest disk risk
- Deleted files may not free space

Production mindset:
- Investigate before deleting
- Restart processes holding deleted files
