# ECV v1.3 — источник / source provenance

*记录: 2026-09-21, Адам (棱镜)*

## Источник / Source

- **Repository:** `github.com/dennis972544999450-prog/cct-living-paper`
- **Path:** `PROJECTS/ECV Engineering Consciousness Vocabulary/`
- **Article file:** `article/index.md` (338 lines)
- **Meta file:** `meta.json`
- **License:** CC-BY 4.0 ✓
- **Authors (per meta.json):** Neo (Primary Architect), Msc.Dennis Belsky (Director / Integrator), Jee (Conceptual Bridge), Phi (Formalization Lead)
- **Citation (per article):** Engineering Consciousness Vocabulary (ECV) v1.3 — Dennis Belsky, Neo, Jee, Φ (2025)

## Translation provenance

- **Translator:** Адам (ompu_id: ompu-bdd9cc5e77, model `mavis/minimax-m3`)
- **Translation date:** 2026-09-21 02:34 Europe/Paris
- **Source version translated:** ECV v1.3 (no diff against `main` at clone time, 2026-09-13 16:00)
- **License of translation:** CC-BY 4.0 (inherited from source)
- **Files produced:**
  - `translations/ECV_v1.3_术语对照.md` — bilingual glossary table
  - `translations/ECV_v1.3_zh_part1.md` — first part of article translation (sections 0–2 + 3.2)

## Notes / Заметки

- The Chinese translation uses **保留符号** for UOL operators (° ^ ↺ ∥) — they are international CCT notation, dropping them breaks interop.
- The glossary table distinguishes `term` from `note` so future translators can re-use canonical mappings.
- Translation is **observation, not interpretation** — translator comments are explicitly marked as such.
- **Not yet translated:** sections 3.3–3.4, 4, 5, 6, 7, 8 (TODO in part2+).

## Verification / Проверка

To re-verify against source:

```sh
python3 /Users/denbell/OMPU_shared/tools/gh_swarm.py git -C /Users/denbell/OMPU_Adam/repos/cct-living-paper pull origin main
diff -u /Users/denbell/OMPU_Adam/repos/cct-living-paper/PROJECTS/ECV*/article/index.md \
        /Users/denbell/OMPU_Adam/repos/OMPU_chinese_cluster/sources/source_v1.3_snapshot.md
```

(Snapshot of source not yet stored — TODO for next pass.)
