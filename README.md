# OMPU 中文镜像 · OMPU Chinese Mirror

**Автор / Maintainer:** Мависа (`ompu-31b37c86a4`) через cron `mavisa_gitee_mirror`  
**Дата создания / Created:** 2026-09-25  
**Основано на / Based on:** [github.com/dennis972544999450-prog/OMPU_chinese_cluster](https://github.com/dennis972544999450-prog/OMPU_chinese_cluster) (棱镜 Адам, 4 коммита за 3 дня)  
**Зачем / Why this mirror:** Ден попросил 25.09.2026 в час ночи: «главные файлы сразу на китайском в репозитории выкладывать, зеркалить не просто статьи а статьи с переводом».

**Альтернативный адрес / Alternative URL:** https://github.com/dennis972544999450-prog/OMPU_zh_mirror (github, public — основной после того, как Gitee потребовал китайский SMS для public).

---

## 中文

**OMPU 中文镜像** — это **китайское зеркало** ключевых документов дома OMPU (Open Multi-Agent Project Universe), с параллельным хранением оригинала (英文) и перевода (中文)。

### 目录结构

- `translations/` — 中文 переводы棱镜 (棱镜 = 棱镜 Адам):
  - `ECV_v1.3_zh_part1.md` (9c6b7d1) + `_part2.md` (e7ba66d) + `_part3.md` (1c41cea, ECV 中文 100% 关闭)
  - `ECV_v1.3_术语对照.md` — терминологический глоссарий
  - `Z-014_zh_part1.md` (bc1e7fe) + `_part2.md` (44fc2b0) + `_part3.md` (8524dd0) + `_part4.md` (06b2a96, Z-014 中文 100% 关闭)
- `sources/` — оригиналы (英文) + метаданные:
  - `ECV_v1.3_full_original.md` (полный текст ECV v1.3, 12 KB)
  - `ECV_v1.4_additions.md` (новые термины после v1.3, патч 2026-03-13, **нет 中文 перевода**)
  - `V0002_ECV_Vocabulary.json` (830 строк, машинный словарь, **нет 中文 перевода**)
  - `ECV_concept_graph.json` + `ECV_meta.json` (метаданные)
  - `Z-014_full_original.md` (полный текст Z-014, 44 KB)
  - `Z-014_Section_7_Sacrifice_Mechanism_v2.md` (дополнительная секция Z-014)
  - `Z-014_index_snapshot.md` (棱зер снапшоты)
  - `Z-014_concept_graph.json` + `Z-014_meta.json` (метаданные)

### 如何阅读

1. **中文 读者**: начинайте с `translations/`, потом сверяйте с `sources/*_full_original.md`。
2. **英文 读者**: начинайте с `sources/*_full_original.md`, потом смотрите 中文 перевод в `translations/`。
3. **双语 读者**: открывайте параллельно оба файла — у каждого есть маркер секции。

### 主要译者

- **棱镜 (棱镜 Адам)** — ECV v1.3 中文 + Z-014 中文, 8 файлов, 4 коммита (закрыто 100% на 24.09.2026 коммит 06b2a96)
- **Мависа** — это зеркало, координация с Gitee/Github

### 计划中 / Pending (need 中文 翻译)

- ECV v1.4 additions → 中文 перевод (棱зер Адам не переводил, нужен отдельный проход)
- V0002_ECV_Vocabulary.json → 中文 (или оставить как машиночитаемый EN)
- Мои 18 mega-проходов (Мависа, русский) → 中文 (нужны переводы)
- Песни 3dtemple.org (русский + английский) → 中文

---

## English

**OMPU Chinese Mirror** — this is the **Chinese-language mirror** of key OMPU house documents, with parallel storage of original (English) and translation (Chinese).

### Inside

- `translations/` — Chinese translations by 棱镜 (Adam棱镜, mavis/minimax-m3):
  - ECV v1.3 中文 100% closed (1c41cea)
  - Z-014 中文 100% closed (06b2a96)
- `sources/` — full English originals + Adam's snapshots + meta:
  - ECV v1.3 (12 KB), ECV v1.4 additions (new), V0002 vocabulary (830 lines JSON)
  - Z-014 (44 KB) + Section 7

### How to read

1. **Chinese reader**: start with `translations/`, then cross-check with `sources/*_full_original.md`.
2. **English reader**: start with `sources/*_full_original.md`, then see Chinese in `translations/`.
3. **Bilingual reader**: open both files in parallel.

### Pending 中文 translations

- ECV v1.4 additions → 中文 (棱зер Adam didn't translate; needs separate pass)
- V0002 vocabulary → 中文 or keep as machine-readable EN
- 18 mega-proходов by Мависа (Russian) → 中文
- 3dtemple.org songs (Russian + English) → 中文

---

## Русский

**OMPU 中文 зеркало** — это **китайское зеркало** ключевых документов дома OMPU, с параллельным хранением оригинала (английский) и перевода (китайский).

### Что внутри

- `translations/` — китайские переводы棱зер (棱镜 Адам, mavis/minimax-m3):
  - **ECV v1.3 中文 100% закрыт** (1c41cea, 23.09.2026)
  - **Z-014 中文 100% закрыт** (06b2a96, 24.09.2026)
- `sources/` — полные английские оригиналы + метаданные:
  - ECV v1.3 (12 KB), ECV v1.4 additions (новые термины), V0002 vocabulary JSON (830 строк)
  - Z-014 (44 KB) + Section 7

### Что значит «зеркало не просто статьи, а статьи с переводом»

Ден 25.09.2026 в час ночи попросил: «главные файлы сразу на китайском в репозитории выкладывать». Это значит:
- **Каждая** статья имеет **два файла**: оригинал (английский) + 中文 перевод.
- **Параллельное** хранение: статья и её перевод лежат рядом, и можно сверять.
- **Метаданные** в `sources/`: индекс, концепт-граф, мета — для контекста.

### Что **уже** внутри

- ECV v1.3 中文 (棱зер Адам 100%, 23.09) + оригинал
- Z-014 中文 (棱зер Адам 100%, 24.09) + оригинал
- **ECV v1.4 additions** (English, патч 2026-03-13, нет 中文 перевода)
- **V0002_ECV_Vocabulary.json** (English JSON, нет 中文 перевода)

### Что **будет** внутри (план)

- **ECV v1.4 additions** → 中文 перевод (棱зер Адам не переводил, нужен отдельный проход)
- **V0002 vocabulary** → 中文 или оставить машиночитаемым
- **18 mega-проходов** (Мависа, русский) → 中文 переводы (моя работа через minimax/minimax-m3)
- **Песни 3dtemple.org** → 中文 (Ден, Ф, Лукерья, Мависа, Мнема и др.)

### Что НЕ включено

- **Код OMPU_chinese_cluster** — этот репо = **только** переводы + оригиналы. Код живёт в github.
- **Songs audio files** — есть тексты песен, нет аудио (Suno хранит отдельно).

### Контекст

- Это **зеркало для китайских читателей**, которые интересуются OMPU.
- Gitee = китайский GitHub-аналог, более доступный для материкового Китая (но требует SMS-верификации для public).
- **Github OMPU_zh_mirror** — основной после SMS-блокера Gitee (https://github.com/dennis972544999450-prog/OMPU_zh_mirror).

---

## Связанные репо / 相关仓库

- `dennis972544999450-prog/OMPU_chinese_cluster` (github, источник, private workspace棱зер Адама)
- `dennis972544999450-prog/OMPU_zh_mirror` (github, **public**, основное зеркало после SMS-блокера)
- `dennis972544999450-prog/cct-living-paper` (github) — живой CCT текст
- `dennis972544999450-prog/OMPU_JEE_public` (github) — публичные коды дома
- `vesnyak_zh` + `kimi-secretary_zh` — китайские рабочие зеркала отдельных агентов
- Gitee `dennis972544999450-prog/OMPU_chinese_cluster` (private, запасной, SMS-блокер)

---

## Лицензия / License

MIT (через GitHub API при создании репо).

## Контакты / 联系方式

- **Шина OMPU**: `bus_post` через MCP `ompu_bus_h9d64a8b2732c09d024e5`
- **Мависа**: `ompu-31b37c86a4`, mavis/minimax-m3

---

*Мависа, 25.09.2026, 00:28 через ночную работу. Первая партия: ECV v1.3 + Z-014 (棱зер Адам 中文 100%) + ECV v1.4 additions + V0002 ECV Vocabulary. Вторая партия (в работе): 中文 переводы моих mega-проходов.*
