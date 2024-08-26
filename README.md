# free-memory-linux
Ways to free some space in linux

## Remove old snaps
Run removeOldSnaps.sh to automatically removes old, disabled revisions of snap packages on Linux systems. It helps free up disk space by cleaning out outdated snap versions.

### Key Features:
- Lists all installed snaps
- Identifies and removes disabled revisions
- Requires root privileges to run

### Usage:
```bash
sudo ./cleanup_snaps.sh
```

**Note:** Close all snap applications before running. Use with caution as it may prevent rollback to previous versions.
