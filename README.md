# NeXuS Archive

**Versioned storage for deprecated, superseded, or historical components.**

All archives are indexed, searchable, and recoverable.

---

## What's Here

Archived NeXuS components with full history:
- Why each was archived
- When it was archived
- What replaced it
- Full source code + metadata

---

## Quick Access

**See all archives:**
```bash
cat ARCHIVE_INVENTORY.md
```

**Search archives:**
```bash
grep -r "pattern" .
```

**View archive details:**
```bash
cat v1-component-name/ARCHIVE.md
```

**Recover an archive:**
```bash
git log --oneline  # Find commit
git checkout <commit>  # Go back in time
```

---

## Structure

Each archived component has its own directory:

```
v1-forge-search-20260623/
├── ARCHIVE.md          ← Why archived, what it was
├── (original files)    ← Full source code
└── ...
```

---

## Files

- `ARCHIVE_INVENTORY.md` — Master index (searchable table)
- `README.md` — This file
- `.gitignore` — Version control settings
- `.git/` — Full git history

---

## Principles

- ✅ Never delete — archive instead
- ✅ Fully searchable
- ✅ Versioned in git
- ✅ Easy recovery if needed
- ✅ Self-documenting via ARCHIVE.md

---

**NeXuS Archive System** | Established 2026-06-23
