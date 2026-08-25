Systems engineer. Operating systems, runtimes, isolation.

## kern

A rootless, daemonless container and resource runtime in **one 1.52 MB static binary**.

| | kern | docker run |
|---|---|---|
| bare box | **~2.3 ms** | |
| from an OCI image | **~3.5 ms** | ~297 ms |

Isolation is the kernel's: namespaces, cgroups v2, seccomp.

```sh
curl -fsSL https://raw.githubusercontent.com/getkern/kern/main/install.sh | sh
