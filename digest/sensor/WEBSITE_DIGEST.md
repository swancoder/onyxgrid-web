# Onyx Grid — Technical Status Digest

## Current Readiness Level

**TRL 4** — Technology Readiness Level: Component/System Validation in Laboratory Environment

The Onyx Grid passive drone detection system is in active development. This is not a production-ready commercial product. Current focus is on core architecture validation and sensor integration on edge hardware.

---

## Recent Achievements

- **Edge Computing Architecture**: Distributed microservices framework designed for resource-constrained edge devices, eliminating traditional bottlenecks in real-time signal processing.
- **Multi-Sensor Integration**: Framework established to support simultaneous video and audio analysis with extensible design for additional sensor modalities.
- **Command & Control Integration**: Telemetry bridge implemented to enable communication with external management systems while maintaining internal isolation.

---

## Development Roadmap

### Near Term
- **RF Detection Integration**: Expanding detection capabilities to include radio frequency domain analysis.
- **Decentralized Mesh Networking**: Enabling peer-to-peer coordination between nodes for distributed deployment scenarios.

### Medium Term
- **Custom AI Models**: Developing and optimizing machine learning models tailored to edge hardware constraints.
- **Physical Hardware Engineering**: Designing enclosures, thermal management, and environmental hardening for field deployment.

---

## Project Context

Onyx Grid targets passive detection on edge AI hardware (Raspberry Pi 5 + Hailo-8L accelerator). The system is designed for high-reliability, low-latency inference without external cloud dependencies.

For technical specifications and architecture details, see `docs/SPECS.md` and `docs/adr/`.
