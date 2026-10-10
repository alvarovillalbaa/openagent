---
title: "AFS root product document migration"
description: "Repository evidence for the preserved product document rename."
keywords: ["AFS", "provenance"]
hidden: true
---

# AFS root product document migration

The isolated checkout pulled `origin main` before edits. The root `VISION.md`
moved byte-for-byte to `PRODUCT.md`, which owns the existing product direction.
README and CONTRIBUTING point to that owner. Root catalogs record navigation,
source provenance and limits. The original content remains recoverable at
baseline `1cf544ffbc69746568b6357d49ed76a95c371009`.

Checks: exact original/final blob comparison, all renamed-root consumers,
security CODEOWNERS scope, new local links and `git diff --check`. The official
Mintlify skill was read for the documentation boundary; this artifact remains
repository evidence outside the existing website navigation. Generated
translations, runtime workspace templates, security policy, dependencies,
application logic and website configuration retain their existing owners.

The isolated clone has no node_modules. Repository-wide `pnpm check`, hosted
documentation validation and application tests were not verified.
