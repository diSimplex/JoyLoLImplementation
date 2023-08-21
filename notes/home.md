title: The implementation of JoyLoL
tags: problems

We capture the implementation of a *process* based tool with which to explore computation (or *processes*).

## Problems

The current JoyLoL syntax (and semantics) captures deterministic ("stable") processes, but does not really capture parallelism (and in particular massive parallelism).

Processes capture the notion of indefinite computation in *time*. Massive Parallelism, captures the notion of indefinite computation in *space*.