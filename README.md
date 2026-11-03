```
$ whoami
```

Hey, I'm Benjamin 👋

Software engineer based in Vancouver, Canada. I enjoy building products, distributed systems, and low-level infrastructure, with a particular interest in writing and profiling high-performance Rust, TypeScript, Go, and Swift.

By day, I lead technical solutions and scoping for Lazer Crypto, where I've tech-led engagements with Coinbase, Axiom, and others. Previously, I worked as an individual contributor on projects for Dapper Labs, LayerZero, Lightspark, and more.

By night, I run Afternoon Foundry, a small engineering side-project studio in Vancouver. I always wanted a space where friends could get together, hack on interesting projects, and build things. Turns out, you can just do things.

```
$ ls ~/projects
```

### [Hera](https://herastack.com)
**Graphics stack and application framework for Linux · Rust, Vulkan, DRM/KMS, React Native**

A comprehensive graphics stack for Linux, built in Rust. Hera combines a high-performance compositor, Vulkan renderer, scene graph protocol, reactive UI framework, and React Native integration.

| Component | Description |
|---|---|
| `hera::composer` | Secure, high-performance compositor supporting isolated and privileged clients, custom surface managers, and configurable input sources. |
| `hera::renderer` | Vulkan renderer leveraging dynamic rendering, instanced drawing, advanced shader effects, adaptive refresh rates, and direct DRM/KMS integration. |
| `hera::protocol` | Scene graph construction and modification, input dispatch, and application-to-system communication. |
| `hera::kit` | Reactive UI framework with Attribute Graph-inspired dependency tracking and constraint-based HStack, VStack, ZStack, and Grid layouts. |
| `hera-rn-host` | React Native host and integration library built around the New Architecture and Fabric renderer. |

### [Rivet](https://rivet.rs)
**Capability-based blockchain runtime · Rust, WebAssembly**

A resource-oriented, capability-based programming model and blockchain runtime, designed around deterministic execution, explicit resource ownership, and secure smart contract execution.

| Component | Description |
|---|---|
| `rivet::core` | Canonical types, identities, storage keys, hashing, codecs, and error definitions. |
| `rivet::stdlib` | `no_std` smart contract SDK with typed resource, capability, storage, and host ABI bindings. |
| `rivet::execution` | Deterministic execution engine with gas metering, journaling, host dispatch, and WASM integration. |
| `rivet::runtime` | Capability enforcement, handle linearity, typed storage, and account/object state validation. |
| `rivet::harness` | Integration testing framework for runtime, host ABI, and end-to-end WASM contract execution. |
