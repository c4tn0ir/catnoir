# catnoir

**systems · runtimes · infrastructure**

Building and debugging software across Linux, native runtimes, networking, Android/Qualcomm, and constrained ML systems.

## Focus

- **Systems engineering** — Linux services, networking, diagnostics, automation
- **Native runtimes** — C/C++, JNI, ABI/runtime boundaries, performance profiling
- **Android / Qualcomm** — QNN, HTP, Hexagon, package/process/runtime analysis
- **AI infrastructure** — local model runtimes, benchmarking, constrained-device experiments

## Selected work

### [NoirAI — mobile transformer systems](./projects/noirai-mobile-transformer.md)
Native C++/JNI experiments around an approximately 100.7M-parameter transformer, with memory, CPU-affinity, compiler, threading, and runtime profiling.

### [Linux systems debugging & automation](./projects/linux-systems-debugging.md)
A reproducible workflow for debugging multi-node Linux services across systemd, networking, DNS, APIs, listeners, and configuration.

### [Android / Qualcomm runtime research](./projects/android-qualcomm-runtime.md)
Mapping and analysis of Android-native runtime components around Qualcomm QNN / HTP / Hexagon, JNI boundaries, packages, processes, binaries, and ABI behavior.

## Stack

`Linux` · `C` · `C++` · `Python` · `Go` · `Bash` · `TCP/IP` · `systemd` · `REST APIs` · `JNI` · `Android` · `Performance Profiling`

## Principles

- reproduce before patching
- measure before optimizing
- verify the effective runtime state, not just configuration files
- automate regression checks after fixing the root cause
- keep credentials, infrastructure identifiers, and private operational data out of public repositories
