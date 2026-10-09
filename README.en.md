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

Both tracks are fully planned. E0 introductions and E1 modeling/state/time lessons are published in Chinese; E2–E7 remain in development. Planning, source review, syntax checks and executed validation have distinct statuses.

## Choose an engine

| Repository | Reading focus | Published scope |
|---|---|---|
| [MuJoCo Atlas](https://github.com/huangkiki/mujoco-atlas) | MJCF, model/data ownership, actuation, constraints and integration | E0 introduction + [E1 modeling, state and time](https://github.com/huangkiki/mujoco-atlas/blob/main/docs/modeling-and-frames.md) + [E2 control and robotics](https://github.com/huangkiki/mujoco-atlas/blob/main/docs/actuation-and-control.md) |
| [SuperDex Atlas](https://github.com/huangkiki/superdex-atlas) | Physics/Robotics boundaries, Scene/Actor, contact geometry and implicit solving | E0 introduction + [E1 modeling, state and time](https://github.com/huangkiki/superdex-atlas/blob/main/docs/modeling-state-time.md) + [E2 control and robotics](https://github.com/huangkiki/superdex-atlas/blob/main/docs/control-robotics.md) |
| [Genesis Atlas](https://github.com/huangkiki/genesis-atlas) | Scene/Entity, multiphysics, batched state and differentiability boundaries | E0 introduction + [E1 modeling, state and time](https://github.com/huangkiki/genesis-atlas/blob/main/docs/modeling-state-time.md) + [E2 control and robotics](https://github.com/huangkiki/genesis-atlas/blob/main/docs/control-robotics-tasks.md) |
| [Newton Atlas](https://github.com/huangkiki/newton-atlas) | ModelBuilder/State/Control, Warp arrays and solver-specific support | E0 introduction + [E1 modeling, state and time](https://github.com/huangkiki/newton-atlas/blob/main/docs/modeling-state-time.md) |
| [PhysX Atlas](https://github.com/huangkiki/physx-atlas) | Native C++ SDK, articulations, PGS/TGS and host integrations | E0 introduction + [E1 modeling, state and time](https://github.com/huangkiki/physx-atlas/blob/main/docs/modeling-state-time.md) |
| [Drake Atlas](https://github.com/huangkiki/drake-atlas) | Systems/Diagram/Context, MultibodyPlant, SceneGraph, contact and optimization | E0 introduction + [E1 modeling, state and time](https://github.com/huangkiki/drake-atlas/blob/main/docs/modeling-state-time.md) |

Read [the learning paths](docs/learning-paths.md) for the complete unit map and [the foundations](docs/foundations.md) for shared questions about frames, inertia, state, time, contact and observations. Detailed content is currently Chinese; this English entry reports the same scope.

## Follow development and evidence

[GitHub Projects](https://github.com/users/huangkiki/projects/2) manages the cross-repository queue. Engine-specific changes belong in their engine repository; navigation and shared terminology belong here. [Contributing](CONTRIBUTING.md) explains the review contract.

This phase focuses on understanding the engines. It does not add simulation campaigns, benchmarks, training or a new scoring system. Experimental lessons will reuse [DexLab](https://github.com/huangkiki/Dexlab), retaining each report's version, workload and evidence boundaries. A source-reading baseline is distinct from a tested binary or historical host version.

Original material: [Apache-2.0](LICENSE). Upstream software and assets retain their own licenses. [Attribution](THIRD_PARTY.md).
