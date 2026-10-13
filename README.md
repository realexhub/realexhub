Hard problems, fast systems. Operating systems, runtimes, isolation. I build kern.

## kern

A rootless, daemonless container and resource runtime in one static binary. Isolation is the
kernel's: namespaces, cgroups v2, seccomp. It reads the Docker images and compose files you already
have, and runs the same way on a desktop and on an ARM board.

```sh
curl -fsSL https://raw.githubusercontent.com/getkern/kern/main/install.sh | sh
