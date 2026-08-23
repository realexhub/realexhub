Systems engineer. Linux isolation, sandboxing, and low-level runtimes.

### kern

I build [**kern**](https://github.com/getkern/kern): a rootless, daemonless container
and resource runtime in one 1.59 MB static binary. A bare box starts in ~2.3 ms, one
from an OCI image in ~3.6 ms, against ~293 ms for `docker run` on the same machine.
Isolation is the kernel's: namespaces, cgroups v2, seccomp.

```

Every number above is measured on hardware I can name, and the method is in
[BENCHMARKS.md](https://github.com/getkern/kern/blob/main/BENCHMARKS.md). What kern
does **not** do yet is written down too, in
[OPEN_ITEMS.md](https://github.com/getkern/kern/blob/main/OPEN_ITEMS.md).

- Site: [getkern.dev](https://getkern.dev)
- Mail: hello@getkern.dev
- X: [@realexweb](https://x.com/realexweb)
