# Lab 3 – SIEM Detection Engineering

## Goal
Build and tune detections to maximize detection accuracy while minimizing noise.

## What
- Started with a broad (noisy) detection hypothesis to ensure coverage.
- Identified noise sources and tuned using: higher-confidence indicators, thresholds, allowlists, and throttling.
- Converted raw matches into an actionable alert format (severity + recommended next step).
- Highlight “actionable alerts”: who/what/where/why + what to do next.

## SPL files
- `spl/siem-naive-detection.spl`
- `spl/siem-tuned-detection.spl`

## Evidence (screenshots)
- `screenshots/lab3_naive_detection.png`
- `screenshots/lab3_tuned_detection.png`
