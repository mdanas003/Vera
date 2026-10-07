# Vera

Vera is an evidence-centric news intelligence platform that helps analysts understand what happened, how reports relate, what claims are being made, and what evidence supports or contradicts them.

## Goals

- Trace important conclusions to source material, evidence, models, and processing steps.
- Distinguish independent reporting from duplicated, syndicated, or commonly sourced coverage.
- Track claims and evidence as events develop, preserving corrections and historical observations.
- Surface uncertainty, conflicts, and evidence quality instead of hiding them behind a single score.
- Support auditable, cited research across sources, languages, and media types.

## Conceptual pipeline

Source → Article or document → Event → Claim → Evidence → Relationships and conflicts → Timeline → Knowledge graph → Intelligence

The architecture covers multi-source ingestion and document understanding; deduplication and source lineage; event and claim intelligence; evidence retrieval, ranking, and verification; conflict and source-independence analysis; temporal and graph reasoning; multilingual and multimodal analysis; narrative intelligence; and an auditable research workflow.

## Design principles

- Evidence before synthesis.
- Preserve raw information separately from derived representations.
- Treat external documents and web content as untrusted input.
- Record provenance and model or processing versions for derived results.
- Make uncertainty and evidence-quality factors visible.
- Preserve historical observations when new evidence or corrections arrive.
- Evaluate components with stated datasets, baselines, procedures, and limitations.
- Introduce advanced models only when evaluation shows they add value.

## Development direction

The proposed phases are: define architecture and data contracts; build the ingestion and event backbone; add claims, evidence, and verification; develop source-lineage, conflict, and temporal analysis; introduce graph, multilingual, and multimodal capabilities where justified; build the research workflow; and harden for production.

## Status

Architecture planning. This repository currently contains the README only; implementation code and supporting documents have not yet been added.
