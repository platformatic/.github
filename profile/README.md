# Hi 👋 Welcome to Platformatic!

We build open source tools that change how teams run Node.js in production. Keep the frameworks you already use, run them faster, and operate them at scale without a rewrite.

## ⚡ Watt — the Node.js Application Server

[**Watt**](https://github.com/platformatic/platformatic) takes any Node.js application, written in any framework, and runs it as a worker thread so you can ship faster and scale smarter in any containerized environment.

- **Use the whole machine, not one core.** Run your frontend, APIs, and AI agents as individually scalable threads in a single runtime. Up to 2-3x the throughput on the same hardware.
- **Bring your stack.** Next.js, Astro, Remix, NestJS, Express, Fastify, and plain Node.js run as they are. No proprietary framework, no migration.
- **Call services by name.** Inter-thread calls skip the network stack, so frequently co-located services (BFFs, microfrontends) stop paying for HTTP between themselves.
- **Observability on by default.** Structured logs, Prometheus metrics, OpenTelemetry traces, health checks, and CPU/memory flame graphs, all out of the box.
- **Self-healing at scale.** Watt heals and scales worker threads in seconds, keeping latency low even at p95 and above.

```bash
npx wattpm create
```

## 🧠 Intelligent Command Center (ICC)

[**ICC**](https://github.com/platformatic/intelligent-command-center) is the open source control plane for running Watt at scale. It's how you operate a fleet across Kubernetes and ECS from one place.

- **Predictive autoscaling** that scales ahead of the spike instead of reacting after it, recovering a large share of typical over-provisioning.
- **Signals that actually predict saturation** — Event Loop Utilization and heap usage, not just CPU.
- **Distributed HTTP and Next.js caching** with tag-based invalidation coordinated across the fleet.
- **Performance profiling, flame graphs, and audit logging** for every workload.

Watt fills the pod. ICC counts the pods. Vertical efficiency meets horizontal prediction.

## 🦊 @platformatic/kafka

[**@platformatic/kafka**](https://github.com/platformatic/kafka) is a modern, high-performance Apache Kafka client written entirely in TypeScript, with no native dependencies.

- Optimized to minimize event loop overhead.
- Streaming, callback, and promise-based consumption.
- Pluggable serialization plus Confluent Schema Registry support (AVRO, Protobuf, JSON Schema).
- Supports Apache Kafka 3.5.0 through 4.2.0.

## 👬 Community

- [Discord](https://discord.com/channels/1011258196905689118/1011258204371554307) for feedback, questions, learning resources, and masterclasses
- [Contributor code of conduct](https://github.com/platformatic/.github/blob/main/CODE_OF_CONDUCT.md)

## 📚 Useful resources

- [Documentation](https://docs.platformatic.dev)
- [Quick Start guide](https://docs.platformatic.dev/docs/getting-started/quick-start)
- [Blog](https://blog.platformatic.dev)
- [Masterclasses](https://www.youtube.com/playlist?list=PL_x4nRdxj60K2j9l_SflmqmaTA2XVBuqc)
- [Benchmarks & reports](https://www.platformatichq.com/)

---

<div align="center">

*Fastify™ & Node.js® are trademarks of the OpenJS Foundation.*

</div>
