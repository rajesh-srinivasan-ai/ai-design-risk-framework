# ADRF-01: Non-Explanatory Metrics

## Summary

Non-Explanatory Metrics occur when AI systems expose user-facing metrics without providing sufficient context to understand what the metric represents, why it changed, how it can be influenced, or what action should be taken.

Users may be able to observe the metric without being able to meaningfully interpret it or make informed decisions based on it.

---

## Risk Statement

AI metrics exist to support decisions.

Non-Explanatory Metrics expose signals without providing sufficient meaning or context to support informed decision-making.

---

## Pattern Evidence

The following evidence artifacts contributed to the discovery and refinement of ADRF-01.

- PE-001 – The 78% AI Story
- PE-002 – The 78% Enterprise AI Story
- PE-003 – The Day The Answers Ran Out
- PE-004 – Front Door Risk
- PE-005 – The Feedback Loop Is Broken
  
---

## Risk Pattern

An AI system exposes a metric to users, but sufficient explanatory context is not provided.

This creates a gap between signal and decision.

```text
Metric Exposed
↓
Insufficient Meaning or Context
↓
No Reliable Interpretation
↓
No Informed Decision
↓
Risk Emerges


