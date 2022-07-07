# Download
```bash
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/S8M1T/local_manifests/RMX3031/twelve.xml --create-dirs
```

# Sync
```bash
repo sync -j$(nproc --all) --force-sync
```
