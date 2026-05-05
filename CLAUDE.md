# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Purpose

Workshop-prep folder for a teacher-training session:

- **Title**: AI與閱讀力 (AI and Reading Literacy)
- **Date**: 2026-05-07
- **Audience**: 高雄市輔導團 (Kaohsiung City advisory team)
- **Context**: part of 115 精進計畫 (MOE 115 teacher-advancement plan)

This is not a code repository — it holds source documents and will accumulate presentation/handout drafts.

## Agenda (from `115精進計畫課表.docx`)

Theme: **AI應用在閱讀輔助力**. Sole speaker is the user (臺南一中 顏永進老師).

| 時間 | 時長 | 內容 |
|---|---|---|
| 9:20–9:30 | — | 報到、長官致詞 |
| 9:30–10:20 | 50 min（1節） | 如何善用 AI 工具提升學生閱讀理解力 |
| 10:20–10:40 | — | 休息 |
| 10:40–12:10 | 90 min（2節） | 從理論到實踐：設計結合 AI 的閱讀教學活動 |
| 12:10–12:30 | — | 綜合座談 |

Total speaking time: ~140 min across two blocks (theory-leaning first, practice-leaning second).

## Files

- `index.org` — working notes / outline for the session (Emacs org-mode)
- `115精進計畫課表.docx` — official course schedule from the sponsoring program
- `1740128678094.jpg` — reference image supplied with the schedule
- `~$*.docx` — Word lock files; ignore and never commit/edit

## Working conventions

- Outline lives in `index.org`; expand it there before generating slides or handouts.
- When the user asks for slides, ask which tool to use (reveal.js / Keynote / PPT skills are all available) — don't assume.
- Keep Traditional Chinese (zh-TW) for all learner-facing material unless asked otherwise.
- Don't edit `.docx` files directly; treat them as read-only source material and produce new artifacts alongside.
