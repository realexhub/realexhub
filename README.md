Systems engineer. Operating systems, runtimes, isolation.

## kern

I build **kern**: a rootless, daemonless container and resource runtime in one **1.52 MB** static binary. A bare box starts in **~2.3 ms**, one from an OCI image in **~3.5 ms**, against **~297 ms** for `docker run` on the same machine. Isolation is the kernel's: namespaces, cgroups v2, seccomp.

```sh
curl -fsSL https://raw.githubusercontent.com/getkern/kern/main/install.sh | sh
```

Every number above is measured on hardware I can name, and the method is in [BENCHMARKS.md](https://github.com/getkern/kern/blob/main/BENCHMARKS.md). What kern does **not** do yet is written down too, in [OPEN_ITEMS.md](https://github.com/getkern/kern/blob/main/OPEN_ITEMS.md).

- Site: [getkern.dev](https://getkern.dev)
- Mail: [hello@getkern.dev](mailto:hello@getkern.dev)
- X: [@realexweb](https://x.com/realexweb)
