# Contributing

Thanks for your interest in improving PostmortemForge.

## Ground rules

1. One logical change per pull request.
2. Run the test suite before pushing:
   `pip install -e . && pip install pytest && pytest -q`
3. Keep changes small and reviewable; describe what and why.

## Repository layout

- src/postmortemforge/ - sources, clock alignment, correlation, drafting
- 	ests/ - the test suite (run with pytest)
- samples/ - bundled evidence exports used by the tests and examples
- docs/ - design notes and the timeline format
