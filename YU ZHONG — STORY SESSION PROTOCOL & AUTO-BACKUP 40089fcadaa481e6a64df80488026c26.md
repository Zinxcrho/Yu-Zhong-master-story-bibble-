# YU ZHONG — STORY SESSION PROTOCOL & AUTO-BACKUP

## PERINGATAN ISOLASI SUMBER — WAJIB

**Jangan mencampuradukkan file lama, proyek lain, draft, arsip, atau cerita terdahulu dengan kanon aktif Yu Zhong.** Satu-satunya sumber kanon utama adalah **YU ZHONG — MASTER STORY BIBLE & ABSOLUTE CREATOR SYSTEM**, ditambah status timeline aktif dan catatan peristiwa yang secara eksplisit dikonfirmasi dalam proyek Yu Zhong.

- Jangan mengimpor nama, karakter, plot, lokasi, aturan, kekuatan, sistem, kronologi, atau keputusan dari file lama kecuali pengguna secara eksplisit meminta penggabungan.
- Bab lama yang ditandai usang hanya arsip historis; bukan titik lanjut cerita.
- Rancangan yang berada di Trash, template, sandbox, dan dokumen proyek lain bukan kanon aktif Main Story.
- Jika ada perbedaan, hentikan asumsi, ikuti Master Story Bible dan instruksi terbaru pengguna, lalu laporkan konflik. Jangan menyatukan sumber secara diam-diam.
- Sebelum memulai sesi, pastikan judul dan timeline dokumen yang dibaca benar-benar milik proyek Yu Zhong.

---

**Purpose:** Make Notion the source of truth before every story session and the durable save destination after each completed chapter.

## Important limitation

This protocol defines the required workflow. It does not by itself create a background trigger that runs on every ChatGPT message. In an ordinary chat, the assistant must execute the read/checkpoint/write steps using the connected Notion tools. For stronger automation, use a supported Custom Agent/workflow with Notion access and event/manual triggers, or a dedicated integration. Never claim a backup succeeded until the write is confirmed.

## A. Mandatory pre-session read

Before writing any in-world prose:

1. Fetch **YU ZHONG — MASTER STORY BIBLE & ABSOLUTE CREATOR SYSTEM**.
2. Fetch **LIVING WORLD CONTROL CENTER**.
3. Fetch the active timeline state: **09 — CURRENT STORY STATE — MAIN CANON** for MAIN-001, or the appropriate Sandbox Save State for SBX-001.
4. Fetch the latest confirmed Chapter Ledger entry and relevant timeline/consequence entries.
5. Fetch relevant character, knowledge, relationship, inventory, cultivation/ability, location, faction, world-clock, saga/mystery records only as needed for the intended scene.
6. Check the Consistency Review Log for unresolved high-severity findings.
7. Compare the latest explicit user instruction against stored state. If conflicting, follow the latest explicit user instruction for user-controlled decisions and flag persistent Notion conflicts rather than silently inventing a resolution.

## B. Canon rules

- Master Story Bible and latest explicit user instructions govern.
- Main Story and Sandbox are isolated; never copy events, inventory, relationships, knowledge, or consequences across timelines without explicit approval.
- Drafts, rumors, proposed outlines, and archived chapters are not active canon by default.
- Do not infer an event from a baseline checkpoint.
- Yu Zhong's voluntary actions, words, thoughts, emotions, intentions, choices, and power use are controlled by the user.
- NPC knowledge and reactions must be supported by plausible evidence and information paths.
- Do not advance time, location, inventory, relationship, cultivation stage, or active mission without story evidence or an explicit user decision.
- The official cultivation stages are **Awal, Menengah, Akhir, Puncak** unless the governing Bible is explicitly revised.
- If the user says “lanjut”, resume from the latest verified state and do not restart or retcon prior canon.

## C. During the story

- Track only confirmed events.
- Preserve exact dialogue and consequential decisions where needed.
- If the user pauses mid-scene, do not mark the chapter complete; keep a session checkpoint clearly labelled **IN PROGRESS**, not canonically closed.
- Do not create a new chapter number merely because the chat conversation changed.

## D. Mandatory post-chapter backup

When the user confirms a chapter is complete, or clearly asks to close/save the chapter:

1. Prepare a concise chapter record: chapter ID/number, timeline ID, title, location/time if established, participants, events, decisions, consequences, and unresolved threads.
2. Create or update the corresponding **04 — Chapter Ledger** record.
3. Update the appropriate timeline-specific Current Story State / Sandbox Save State: last confirmed chapter, time, location, Yu Zhong status, present NPCs, inventory, relationships, active missions/mysteries, pending responses, and next-scene hook. Only populate fields supported by events.
4. Update related ledgers only when a real change occurred: timeline/consequence, character knowledge, inventory/transactions, NPC emotions/relationships, world clock, saga/mystery, rumor/information, political/faction, location, economy, law/culture, ecology, cultivation/ability.
5. Add a **Consistency Review Log** record for contradictions, unresolved decisions, or changes to prior canon.
6. Update the Control Center's latest checkpoint pointer and link the chapter/save record if that page structure supports it.
7. Fetch the saved page(s) again and verify the write. Report the actual Notion links and any failed step. Never claim success based only on a generated summary.
8. Do not alter old chapters to match new events. Use an explicit correction/retcon entry only if the user authorizes it.

## E. Backup status labels

- **IN PROGRESS:** scene/chapter still open; temporary checkpoint only.
- **READY TO SAVE:** user indicates chapter closure; structured record prepared.
- **SAVED & VERIFIED:** Notion write completed and read back successfully.
- **SAVE FAILED / PARTIAL:** one or more Notion writes failed; list exactly what is and is not saved.
- **CONFLICT — USER DECISION NEEDED:** incompatible canon records or unclear timeline; do not invent a resolution.

## F. Reusable start command

“YU ZHONG — START SESSION. Read the Master Story Bible, Living World Control Center, the selected timeline's current state, latest chapter, and relevant ledgers from Notion. Run a continuity check first. Tell me the exact last confirmed point in 3–6 bullets, flag unresolved conflicts, then wait for my story action. Do not write in-world events until I act.”

## G. Reusable end-of-chapter command

“YU ZHONG — CLOSE CHAPTER AND BACKUP. Treat only events confirmed in this session as canon. Update the Chapter Ledger, timeline-specific current state/save state, and only the relevant consequence/knowledge/inventory/relationship/world ledgers. Add a consistency review record if needed. Read back every changed Notion page and verify the backup. Return the chapter ID, saved links, changes made, unresolved threads, and backup status. If a write fails, report it explicitly.”

## H. Quick command for a new ChatGPT conversation

“Use Notion as the source of truth for Yu Zhong. Follow the page **YU ZHONG — STORY SESSION PROTOCOL & AUTO-BACKUP**. Before continuing, read the Master Story Bible, Control Center, current timeline state, latest confirmed chapter, and relevant ledgers. After each chapter I explicitly close, save and verify the chapter and state in Notion. Never claim automatic/background sync unless an actual supported workflow is configured.”

## Current known checkpoint (2026-10-21)

- MAIN-001: chapter 0; story not started.
- Yu Zhong: Abadi Sejati (Realm 13), stage not specified, as recorded in Main Story State.
- Proposed new Qinghe story outline/checkpoint and older index/manifest were found in Trash during audit; they have not been restored and must not be treated as active canon.

## Auto-backup — SBX-001 session sync 2026-10-22

After each story turn, preserve the latest user-authorized actions and the pending scene in `10 — SANDBOX SAVE STATE — ISOLATED TIMELINE` and the Sandbox Session Ledger. The latest state is in the appended “SBX-001 — Sinkronisasi sesi terbaru” section of the Master Story Bible and Sandbox Save State. Keep this timeline isolated from Main Story. Do not teleport Yu Zhong to a sound source unless explicitly ordered; do not control Yu Zhong's actions, dialogue, or thoughts; NPCs must not be treated as omniscient; unresolved clues remain unverified.