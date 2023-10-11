FPSYNC is a shell script that wraps FPART and RSYNC, CPIO or TAR to launch several synchronization jobs in parallel.

# FPSYNC Command Example
> fpsync -n 4 -f 1000 -s $((100 * 1024)) /data/src/ root@XXX:/data/dest/
