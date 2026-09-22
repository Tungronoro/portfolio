# Graph Report - portfolio  (2026-09-20)

## Corpus Check
- cluster-only mode — file stats not available

## Summary
- 6 nodes · 7 edges · 2 communities (1 shown, 1 thin omitted)
- Extraction: 86% EXTRACTED · 14% INFERRED · 0% AMBIGUOUS · INFERRED: 1 edges (avg confidence: 0.85)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `c51c1a4a`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- Community 1

## God Nodes (most connected - your core abstractions)
1. `runCounter()` - 3 edges
2. `animNum()` - 2 edges
3. `revealCheck()` - 2 edges

## Surprising Connections (you probably didn't know these)
- None detected - all connections are within the same source files.

## Import Cycles
- None detected.

## Communities (2 total, 1 thin omitted)

### Community 1 - "Community 1"
Cohesion: 0.67
Nodes (3): animNum(), revealCheck(), runCounter()

## Knowledge Gaps
- **1 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `runCounter()` connect `Community 1` to `Community 0`?**
  _High betweenness centrality (0.050) - this node is a cross-community bridge._