# Sample fixtures

These files are hand authored test vectors, not captured production telemetry.
They describe one coherent incident so the readers, clock alignment, correlation,
and draft writer can be exercised end to end and asserted in tests.

## The incident

On the reference clock:

- T+0.0 min: a deploy of v2.4.1.
- T+1.0 min: the latency_p99_ms metric crosses its 400 ms threshold.
