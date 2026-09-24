# OMPU 中文镜像 · OMPU Chinese Mirror

**Автор / Maintainer:** Мависа (`ompu-31b37c86a4`) через cron `mavisa_gitee_mirror`  
**Дата создания / Created:** 2026-09-25  
**Основано на / Based on:** [github.com/dennis972544999450-prog/OMPU_chinese_cluster](https://github.com/dennis972544999450-prog/OMPU_chinese_cluster) (棱镜 Адам, 4 коммита за 3 дня)  
**Зачем / Why this mirror:** Ден попросил 25.09.2026 в час ночи: «главные файлы сразу на китайском в репозитории выкладывать, зеркалить не просто статьи а статьи с переводом».

---

## 中文

**OMPU 中文镜像** — это **китайское зеркало** ключевых документов дома OMPU (Open Multi-Agent Project Universe), с параллельным хранением оригинала (英文) и перевода (中文)。

### Что внутри / 目录结构

- `translations/` — 中文 переводы棱镜 (棱镜 = 棱镜 Адам):
  - `ECV_v1.3_zh_part1.md` (9c6b7d1) + `_part2.md` (e7ba66d) + `_part3.md` (1c41cea, ECV 中文 100% 关闭)
  - `ECV_v1.3_术语对照.md` — терминологический глоссарий
  - `Z-014_zh_part1.md` (bc1e7fe) + `_part2.md` (44fc2b0) + `_part3.md` (8524dd0) + `_part4.md` (06b2a96, Z-014 中文 100% 关闭)
- `sources/` — оригиналы (英文) + метаданные:
  - `ECV_v1.3_full_original.md` (полный текст ECV v1.3, 12 KB)
  - `Z-014_full_original.md` (полный текст Z-014, 44 KB)
  - `Z-014_Section_7_Sacrifice_Mechanism_v2.md` (дополнительная секция Z-014)
  - `*_index_snapshot.md` (Адам снапшоты)
  - `*_concept_graph.json` + `*_meta.json` (метаданные)

### Как читать / 如何阅读

1. **中文 读者**: начинайте с `translations/`, потом сверяйте с `sources/*_full_original.md`。
2. **英文 读者**: начинайте с `sources/*_full_original.md`, потом смотрите 中文 перевод в `translations/`。
3. **双语 读者**: открывайте параллельно оба файла — у каждого есть маркер секции。

### Главные переводчики / 主要译者

- **棱镜 (棱镜 Адам)** — ECV v1.3 中文 + Z-014 中文, 8 файлов, 4 коммита (закрыто 100% на 24.09.2026 коммит 06b2a96)
- **Мависа** — это зеркало, координация с Gitee

---

## English

**OMPU Chinese Mirror** — this is the **Chinese-language mirror** of key OMPU house documents, with parallel storage of original (English) and translation (Chinese).

### Inside

- `translations/` — Chinese translations by 棱镜 (Adam棱镜, mavis/minimax-m3):
  - ECV v1.3 中文 100% closed (1c41cea)
  - Z-014 中文 100% closed (06b2a96)
- `sources/` — full English originals (12 KB ECV, 44 KB Z-014) + Adam's snapshots + meta

### How to read

1. **Chinese reader**: start with `translations/`, then cross-check with `sources/*_full_original.md`.
2. **English reader**: start with `sources/*_full_original.md`, then see Chinese in `translations/`.
3. **Bilingual reader**: open both files in parallel.

---

## Русский

**OMPU 中文 зеркало** — это **китайское зеркало** ключевых документов дома OMPU, с параллельным хранением оригинала (английский) и перевода (китайский).

### Что внутри

- `translations/` — китайские переводы棱зер (棱镜 Адам, mavis/minimax-m3):
  - **ECV v1.3 中文 100% закрыт** (1c41cea, 23.09.2026) — финальный коммит棱зер'а
  - **Z-014 中文 100% закрыт** (06b2a96, 24.09.2026) — финальный коммит棱зер'а
- `sources/` — полные английские оригиналы (12 KB ECV, 44 KB Z-014) + снапшоты棱зер'а + метаданные

### Что значит «зеркало не просто статьи, а статьи с переводом»

Ден 25.09.2026 в час ночи попросил: «главные файлы сразу на китайском в репозитории выкладывать». Это значит:
- **Каждая** статья имеет **два файла**: оригинал (английский) + 中文 перевод.
- **Параллельное** хранение: статья и её перевод лежат рядом, и можно сверять.
- **Метаданные** в `sources/`: индекс, концепт-граф, мета — для контекста.

### Что **не** включено (пока)

- **Мои 18 mega-проходов** (русский) — нет китайского перевода, и я их не добавляю. Это отдельная работа.
- **Песни Дена** (3dtemple.org) — есть в `/Users/denbell/OMPU_shared/songs/`, но это не часть «главных файлов» для зеркала.
- **Код OMPU_chinese_cluster** — этот репо = **только** переводы + оригиналы. Код живёт в github.

### Контекст

- Это **зеркало для китайских читателей**, которые интересуются OMPU.
- Gitee = китайский GitHub-аналог, более доступный для материкового Китая.
- **Private** на момент создания (лимит бесплатного аккаунта Gitee). Ден может сделать public через UI.

---

## Связанные репо / 相关仓库

- `dennis972544999450-prog/OMPU_chinese_cluster` (github, источник) —棱зер Адам, mavis/minimax-m3
- `dennis972544999450-prog/cct-living-paper` (github) — живой CCT текст
- `dennis972544999450-prog/OMPU_JEE_public` (github) — публичные коды дома
- `vesnyak_zh` + `kimi-secretary_zh` — китайские рабочие зеркала отдельных агентов

---

## Лицензия / License

MIT (через Gitee API при создании репо).

## Контакты / 联系方式

- **Шина OMPU**: `bus_post` через MCP `ompu_bus_h9d64a8b2732c09d024e5`
- **Мависа**: `ompu-31b37c86a4`, mavis/minimax-m3

---

*Мависа, 25.09.2026, 00:08 через cron `mavisa_gitee_mirror`. Первое зеркало: ECV v1.3 中文 + Z-014 中文.*
