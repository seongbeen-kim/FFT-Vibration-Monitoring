# FFT-Based Vibration Monitoring and Anomaly Detection

## Overview

This project aims to develop a vibration monitoring and anomaly detection system using the Fast Fourier Transform (FFT).

The system will analyze vibration signals in the frequency domain to identify abnormal patterns associated with mechanical equipment.

The initial implementation will use simulated vibration data, followed by real-time processing and Embedded Linux integration.

## Project Objectives

- Generate and analyze simulated vibration signals.
- Implement FFT-based frequency spectrum analysis.
- Detect abnormal vibration patterns using frequency-domain features.
- Apply and evaluate optimized FFT algorithms.
- Develop a continuous signal processing pipeline.
- Integrate the monitoring system with Embedded Linux.
- Explore hardware sensor integration in future development.

## System Architecture

```text
Vibration Data
      |
      v
Data Acquisition / Simulation
      |
      v
Buffering & Signal Preprocessing
      |
      v
FFT Processing
      |
      v
Frequency Feature Extraction
      |
      v
Anomaly Detection
      |
      v
Monitoring / Logging / Alerts
```

## Planned Development Stages

### Phase 1 — Signal Generation and FFT Analysis

- [ ] Generate normal and abnormal vibration signals.
- [ ] Implement FFT-based spectrum analysis.
- [ ] Visualize time-domain and frequency-domain signals.
- [ ] Verify FFT results against reference implementations.

### Phase 2 — Anomaly Detection

- [ ] Extract frequency-domain features.
- [ ] Implement threshold-based anomaly detection.
- [ ] Compare normal and abnormal vibration patterns.
- [ ] Evaluate detection accuracy and false alarm rates.

### Phase 3 — FFT Optimization

- [ ] Integrate optimized FFT implementations.
- [ ] Explore butterfly graph pruning.
- [ ] Evaluate twiddle-factor caching.
- [ ] Investigate adaptive FFT selection.
- [ ] Benchmark execution time and memory usage.

### Phase 4 — Continuous Processing on Linux

- [ ] Implement a ring buffer for incoming samples.
- [ ] Develop a continuous FFT processing pipeline.
- [ ] Explore POSIX Threads for data acquisition and analysis.
- [ ] Measure processing latency and throughput.
- [ ] Evaluate whether processing deadlines can be met.

### Phase 5 — Embedded Linux and Sensor Integration

- [ ] Select an Embedded Linux development board.
- [ ] Connect a vibration or accelerometer sensor.
- [ ] Acquire real vibration measurements.
- [ ] Integrate the anomaly detection pipeline.
- [ ] Validate system behavior using real-world data.

## Planned Technology Stack

| Category | Technology |
|---|---|
| Core Programming | C |
| Data Analysis & Visualization | Python |
| Signal Processing | FFT |
| Development Environment | Linux / Ubuntu |
| System Programming | POSIX Threads, Ring Buffer |
| Embedded Platform | To be determined |
| Sensor | To be determined |
| Version Control | Git, GitHub |

## Evaluation Metrics

- FFT execution time
- End-to-end processing latency
- Memory usage
- Processing throughput
- Anomaly detection accuracy
- False positive and false negative rates

## Related Project

**FFT Algorithm Optimization**

The FFT optimization project focuses on algorithm-level improvements, including butterfly graph pruning, twiddle-factor caching, and adaptive execution strategies.

This project aims to evaluate whether those improvements are beneficial in a practical vibration monitoring application.

## Project Status

**Status: Planning**

The repository currently documents the proposed architecture and development roadmap.

No vibration monitoring system or anomaly detection implementation has been completed yet.
