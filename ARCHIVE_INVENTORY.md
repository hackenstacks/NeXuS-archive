# Archive Inventory

Master index of all archived NeXuS components. See `ARCHIVE.md` in each directory for full details.

---

## Archives

| Directory | Date Archived | Original Path | Component Type | Reason | Replacement |
|-----------|---------------|---------------|-----------------|--------|-------------|
| `v1-forge-search-20260623/` | 2026-06-23 | `/NeXuS/forge-search-app/` | Search Tool | Superseded by consolidated nxs-search | `/NeXuS/nxs-search/` |

---

## How to Use

**Search all archives:**
```bash
grep -r "keyword" /home/user/NeXuS/archive/
```

**View archive metadata:**
```bash
cat /home/user/NeXuS/archive/v1-forge-search-20260623/ARCHIVE.md
```

**List contents:**
```bash
ls -la /home/user/NeXuS/archive/v1-forge-search-20260623/
```

**See git history:**
```bash
cd /home/user/NeXuS/archive
git log --oneline
```

---

**Last Updated:** 2026-06-23
