# Ghost Orgy Website — Repository Rules (Authoritative)

This repository is the canonical source for the live Ghost Orgy website.

## 1. Branch discipline
- `main` = production (GitHub Pages)
- Experiments happen in feature branches, never directly on `main`

## 2. Stability outranks elegance
- No large reorganizations on `main` without a migration plan
- Do not break existing URLs/paths
- Prefer small, reversible commits

## 3. Assets
- Optimize images/video/audio before commit
- Use stable, human-readable filenames

## 4. History preservation
- No force-push to `main`
- No rewriting published commits

## 5. Deployment awareness
Every push to `main` may redeploy the site.
Treat commits as production changes.
