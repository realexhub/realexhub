Systems engineer. Linux isolation, sandboxing, and low-level runtimes.

### kern

I build [**kern**](https://github.com/getkern/kern): a rootless, daemonless container
and resource runtime in one 1.59 MB static binary. A bare box starts in ~2.3 ms, one
from an OCI image in ~3.6 ms, against ~293 ms for `docker run` on the same machine.
Isolation is the kernel's: namespaces, cgroups v2, seccomp.

```sh
curl -fsSL https://raw.githubusercontent.com/getkern/kern/main/install.sh | sh
