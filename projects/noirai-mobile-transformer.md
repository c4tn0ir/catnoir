# NoirAI — Mobile Transformer Systems

Sanitized public engineering note.

## Goal

Explore transformer-class workloads on constrained mobile hardware while keeping memory use, runtime behavior, and performance measurable.

## Work performed

- Built native **C++ / JNI** training and inference experiments.
- Worked with an approximately **100.7M-parameter transformer**.
- Estimated RAM feasibility before larger runs.
- Measured CPU affinity and thread behavior.
- Compared compiler/runtime choices.
- Investigated runtime bottlenecks visible from the application side.
- Used repeatable microbenchmarks to separate compute limits from scheduling, memory, and runtime overhead.

## Technologies

C/C++ · JNI · Android/Linux runtime concepts · Python tooling · performance profiling · local AI/ML runtimes
