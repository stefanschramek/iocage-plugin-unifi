# iocage-plugin-unifi

## Post install steps
### Mount storage for persistence
```
iocage fstab -a jail_name /mnt/pool-1/apps/unifi/data /usr/local/share/java/unifi/data nullfs rw 0 0
iocage fstab -a jail_name /mnt/pool-1/apps/unifi/logs /usr/local/share/java/unifi/logs nullfs rw 0 0
```
