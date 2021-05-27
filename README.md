# ipfs-backup
This is a backup tool to save data to IPFS network. backup data is encrypted.

### Requirements
* Ubuntu 20.04 ~
* Node.js

### Usage
**initialize**

~/.ipfs-backup-key is the key for saving data and restoring.
```bash
ipfs-backup init
```

**save data**
```bash
ipfs-backup save /path/to/dir
```

**restore**
```bash
cd /path/to/dir
ipfs-backup restore <CID>
```

### License
MIT License
