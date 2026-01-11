# container-tests
Run container testsuites

Implement a unified way to run and collect logs from the testsuites available in the following container packages:

- [aardvark-dns](https://github.com/containers/aardvark-dns)
- [buildah](https://github.com/containers/buildah)
- [conmon](https://github.com/containers/conmon)
- [containerd](https://github.com/containerd/containerd)
- [docker-buildx](https://github.com/docker/cli)
- [docker-cli](https://github.com/docker/cli)
- [docker-compose](https://github.com/docker/compose)
- [docker-py](https://github.com/docker/docker-py)
- [moby](https://github.com/moby/moby)
- [netavark](https://github.com/containers/netavark)
- [podman](https://github.com/containers/podman)
- [rootlesskit](https://github.com/rootless-containers/rootlesskit)
- [runc](https://github.com/opencontainers/runc)
- [skopeo](https://github.com/containers/skopeo)
- [umoci](https://github.com/opencontainers/umoci)

The output will be Junit XML which is the industry standard for test log collection.

## To do / Roadmap

- Migrate the existing [openQA code](https://github.com/os-autoinst/os-autoinst-distri-opensuse/edit/master/tests/containers/README.md) here.
- Distro-agnostic mechanism to backport upstream test fixes to the package version currently available.
- Distro-agnostic mechanism to specify a list of expected failures to ignore.
- Just clone and run.  No need to package it as RPM.
- Customer & user-centric UI.
