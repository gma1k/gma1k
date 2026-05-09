# Ghassan Malke

Platform Engineer & SRE who works from the kernel up.

I specialize in eBPF-powered tooling, Kubernetes internals, and low-level Linux observability.
Most of my work lives at the intersection of kernel space and production reliability,
building the kind of diagnostics that tell you *why* something is broken, not just *that* it is.

---

## What I'm building

### [`podtrace`](https://github.com/gma1k/podtrace) — eBPF-driven diagnostics for Kubernetes
Full-stack observability for Kubernetes pods — from kernel events to HTTP, DNS, gRPC,
databases, and distributed traces. Zero instrumentation required.

- Attaches eBPF programs directly to pod containers at runtime
- Traces TCP/UDP, filesystem, memory, CPU, TLS, Redis, Kafka, Memcached, gRPC, FastCGI and more
- Kubernetes operator with `PodTrace` / `PodTraceSession` / `TracerConfig` CRDs
- Distributed tracing via OTLP, Jaeger, Datadog, Zipkin, Splunk
- Real-time alerting, Prometheus metrics, Grafana dashboard
- Available via `kubectl krew install podtrace` and OperatorHub

---

## Other projects

- [`snake-ebpf`](https://github.com/gma1k/snake-ebpf) — Where I learned eBPF.
  A terminal Snake game where kernel events (execve, context switches, file ops)
  influence game speed and food spawning in real time. Silly idea, serious learning.
- [`k8s`](https://github.com/gma1k/k8s) — Kubernetes automation tasks and workflows.
- [`useful-scripts`](https://github.com/gma1k/useful-scripts) — Day-to-day ops automation.

---

## Focus areas

- **eBPF & Linux kernel:** kprobes, uprobes, BPF maps, CO-RE, BTF, ring buffers
- **Kubernetes:** operators, CRDs, Helm, GitOps, cluster reliability
- **Observability:** metrics, traces, logs, low-level diagnostics
- **Platform Engineering:** resilient systems, delivery automation, SRE practices
- **AI in Engineering Operations:** applying AI to engineering operations and software delivery workflows

---

## Tech Stack

[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://github.com/gma1k)
[![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)](https://github.com/gma1k)
[![eBPF](https://img.shields.io/badge/eBPF-FF6B6B?style=for-the-badge&logo=linux&logoColor=white)](https://github.com/gma1k)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://github.com/gma1k)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)](https://github.com/gma1k)
[![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)](https://github.com/gma1k)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://github.com/gma1k)
[![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)](https://github.com/gma1k)
[![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)](https://github.com/gma1k)
[![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)](https://github.com/gma1k)
[![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)](https://github.com/gma1k)
[![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)](https://github.com/gma1k)
[![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)](https://github.com/gma1k)
[![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=for-the-badge&logo=opentelemetry&logoColor=white)](https://github.com/gma1k)

---

## Connect

[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:ghassan+github@malke.nl)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat-square&logo=linkedin&labelColor=blue)](https://www.linkedin.com/in/gmalk/)
[![Meetup](https://img.shields.io/badge/Meetup-red?style=flat-square&logo=meetup&labelColor=red)](https://www.meetup.com/members/398144352/)
