# DISCOVERY - organvm/alchemia-ingestvm

**Verdict:** VALUE FOUND -> promote into the ranked tier.  
**Date:** 2026-07-01 (auto-discovery)

## Value Thesis

`alchemia-ingestvm` is the estate's reusable ingestion, provenance, and aesthetic-propagation organ: a real Python CLI package that can crawl scattered source material, fingerprint and deduplicate it, enrich it from manifests and sidecars, classify it against `registry-v2.json`, plan or execute repo deployment through GitHub, write provenance registries, and synthesize taste-aware creative briefs from a cascading `taste.yaml` -> organ-aesthetic chain. Its highest latent value is not just internal cleanup; it is a productizable "corpus-to-governed-repos" continuity kit for AI-native studios, schools, nonprofits, or operators who already have valuable work trapped in chats, notes, screenshots, bookmarks, docs, and half-formed repos. The revenue path is a migration/onboarding service and later packaged local-first tool: point Alchemia at a messy working corpus, produce classified artifacts, deployment manifests, provenance records, and brand/aesthetic prompt packs, then let downstream organs build from an auditable source of truth. The rest of the estate can use this immediately as the intake front door for dark material and as the shared aesthetic contract for generated content; the single best first task is to add a contract-checked `alchemia discover --source-dir ... --dry-run` command that runs intake, absorb, deployment planning, provenance preview, and creative-brief synthesis into one reviewable report without touching remote repos.

## What It Already Does

- Provides the `alchemia` CLI with `intake`, `absorb`, `alchemize`, `status`, `review`, `capture`, `sync`, `synthesize`, and Google Docs auth/status commands.
- Crawls source directories with SHA-256 fingerprints, duplicate detection, manifest enrichment, and `.meta.json` sidecar enrichment.
- Classifies files through a priority chain: direct repo match, name variants, staging directories, special containers, manifest category, content keywords, then pending review.
- Plans and executes GitHub Contents API deployments, including batch deployment, docx conversion routing, archived-repo skipping, and provenance registry generation.
- Maintains the aesthetic nervous system through `taste.yaml`, organ aesthetic YAML files, creative briefs, prompt-injection blocks, bookmark capture, Apple Notes export, Google Docs sync, Gemini transcript parsing, and a macOS screenshot watcher.

## Single Best Concrete First Task

Add a contract-checked `alchemia discover --source-dir ... --dry-run` command that writes a single discovery report containing inventory counts, duplicate groups, classification confidence by rule, pending-review items, deployment-plan summary, provenance preview, and generated aesthetic prompt packs. It should be pure dry-run by default, covered by focused CLI tests, and safe to run in any repo before credentials or remote write access exist.
