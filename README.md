# ipfs-backup
This is a backup tool to save data to IPFS network. backup data is encrypted.

### Usage
**initialize**

~/.ipfs-backup-key is the key for saving data and restoring.
```bash
ipfs-backup init
```

**save data**
```bash
cd /path/to/dir
ipfs-backup save
# copy the cid.
```

**restore**
```bash
cd /path/to/dir
ipfs-backup restore <CID>
```

### License
MIT License
