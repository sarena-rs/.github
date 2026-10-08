# Welcome to Sarena!

Sarena is an open-source dataplane/CNI built on eBPF🐝, written in Rust🦀 with Aya. It is in early development.

## Projects

- **sarena**: the Kubernetes part. It provides the CNI plugin and programs the dataplane from Kubernetes resources.
- **sarena-data-plane**: a lean eBPF dataplane that does not depend on Kubernetes. A control plane (Kubernetes, BGP, or something else) programs it.
- **gladia-ebpf**: a framework for testing eBPF programs (TCX) by running them through the real kernel verifier. It works in any Aya project.

## Maintainer

Created and maintained by [Erwin Kok](https://github.com/erwin-kok).
I write about the design and what I learn along the way at [erwinkok.org](https://erwinkok.org).
