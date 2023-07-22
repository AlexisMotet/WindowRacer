# Zero Lookahead? Zero Problem. The Window Racer Algorithm

This is an implementation of the Window Racer algorithm for optimistic parallel discrete-event simulation.

As an example model, the repository contains the PHold benchmark model extended by events with near-zero delay.

## Quickstart

```
cmake . -DCMAKE_BUILD_TYPE=Release
./window_racer 1
```

## Associated publication:

*Philipp Andelfinger, Till Köster, and Adelinde Uhrmacher. 2023. Zero Lookahead? Zero Problem. The Window Racer Algorithm. In Proceedings of the 2023 ACM SIGSIM Conference on Principles of Advanced Discrete Simulation (SIGSIM-PADS '23). Association for Computing Machinery, New York, NY, USA, 1–11. https://doi.org/10.1145/3573900.3591115*
