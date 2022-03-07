# Changelog

All notable changes to this project are documented here. The format follows
Keep a Changelog, and this project adheres to semantic versioning.

## [0.1.0] - 2026-09-02

### Added

- Readers for three offline export kinds: application logs, a metric series with
  a declared threshold, and a deploy record. Each event carries its source file
  and line span.
- Clock alignment against a declared reference clock, with per source offset and
  linear skew anchored at a chosen instant.
- Windowed correlation between deploys, metric breach intervals, and log error
  bursts, plus rollback to recovery detection.
- An ordered timeline model measured in minutes from the first event.
- A postmortem draft writer where every statement cites the exact source span it
  came from, and ungrounded statements are omitted.
- CLI subcommands: ingest, timeline, draft, version.
- Sample incident fixtures with deliberately offset clocks, and a test suite
  asserting the alignment.

<!-- draft note 809 -->
