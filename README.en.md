<div align="center">

<img src="assets/hero.svg" alt="Sim Atlas: six engines, two learning tracks, from native APIs to physics and source code" width="100%">

**Learn to use simulation engines—and explain how they work.**

[中文](README.md) · [Learning paths](docs/learning-paths.md) · [Shared foundations](docs/foundations.md) · [Project tracker](https://github.com/users/huangkiki/projects/2) · [Experimental cases](docs/dexlab.md)

</div>

Sim Atlas is an independent community learning series for **MuJoCo, SuperDex, Genesis, Newton Physics, PhysX and Drake**. This repository is the course home. Each engine repository owns its detailed lessons, native examples, pinned source references and version records.

## Choose a track

| Applications · A0–A9 | Physics and source · B0–B7 |
|---|---|
| Objects and setup, modeling, state and time, control, robotics, sensing, batching and data. | Dynamics and data structures, stepping, contact, solvers, integration, force observation and extensions. |
| Start with programming basics and use the shared concept map as needed. | Start with linear algebra and rigid-body mechanics, after the engine's A0–A4 foundations. |

Both tracks are fully planned. All six engines have Chinese lessons on modeling, state, control, robotics, contact, solvers, sensing, rendering, batching and data. MuJoCo, SuperDex and Genesis also have extension and differentiation lessons. Installation lessons and the integrated track review remain in development. See [delivery progress](docs/progress.md#delivery-progress) for stage details; source review, syntax checks and executed validation have distinct statuses.

## Choose an engine

| Repository | Reading focus | Course entry |
|---|---|---|
| [MuJoCo Atlas](https://github.com/huangkiki/mujoco-atlas) | MJCF, model/data ownership, actuation, constraints and integration | [Curriculum](https://github.com/huangkiki/mujoco-atlas/blob/main/docs/curriculum.md) · [Callbacks and plugins](https://github.com/huangkiki/mujoco-atlas/blob/main/docs/extensions-and-callbacks.md) |
| [SuperDex Atlas](https://github.com/huangkiki/superdex-atlas) | Physics/Robotics boundaries, Scene/Actor, contact geometry and implicit solving | [Curriculum](https://github.com/huangkiki/superdex-atlas/blob/main/docs/curriculum.md) · [Materials and differentiation](https://github.com/huangkiki/superdex-atlas/blob/main/docs/extensions-boundaries.md) |
| [Genesis Atlas](https://github.com/huangkiki/genesis-atlas) | Scene/Entity, multiphysics, batched state and differentiability boundaries | [Curriculum](https://github.com/huangkiki/genesis-atlas/blob/main/docs/curriculum.md) · [Multiphysics and differentiation](https://github.com/huangkiki/genesis-atlas/blob/main/docs/extensions-boundaries.md) |
| [Newton Atlas](https://github.com/huangkiki/newton-atlas) | ModelBuilder/State/Control, Warp arrays and solver-specific support | [Curriculum](https://github.com/huangkiki/newton-atlas/blob/main/docs/curriculum.md) · [Batching and data](https://github.com/huangkiki/newton-atlas/blob/main/docs/batch-learning-data.md) |
| [PhysX Atlas](https://github.com/huangkiki/physx-atlas) | Native C++ SDK, articulations, PGS/TGS and host integrations | [Curriculum](https://github.com/huangkiki/physx-atlas/blob/main/docs/curriculum.md) · [Batching and data](https://github.com/huangkiki/physx-atlas/blob/main/docs/batch-learning-data.md) |
| [Drake Atlas](https://github.com/huangkiki/drake-atlas) | Systems/Diagram/Context, MultibodyPlant, SceneGraph, contact and optimization | [Curriculum](https://github.com/huangkiki/drake-atlas/blob/main/docs/curriculum.md) · [Environment lifecycle](https://github.com/huangkiki/drake-atlas/blob/main/docs/batch-lifecycle.md) |

Read [the learning paths](docs/learning-paths.md) for the complete unit map and [the foundations](docs/foundations.md) for shared questions about frames, inertia, state, time, contact and observations. Detailed content is currently Chinese; this English entry reports the same scope.

## Follow development and evidence

[Delivery progress](docs/progress.md#delivery-progress) records published coverage. [GitHub Projects](https://github.com/users/huangkiki/projects/2) manages the cross-repository queue. Engine-specific changes belong in their engine repository; navigation and shared terminology belong here. [Contributing](CONTRIBUTING.md) explains the review contract.

This phase focuses on understanding the engines. It does not add simulation campaigns, benchmarks, training or a new scoring system. Experimental lessons will reuse [DexLab](https://github.com/huangkiki/Dexlab), retaining each report's version, workload and evidence boundaries. A source-reading baseline is distinct from a tested binary or historical host version.

Original material: [Apache-2.0](LICENSE). Upstream software and assets retain their own licenses. [Attribution](THIRD_PARTY.md).
