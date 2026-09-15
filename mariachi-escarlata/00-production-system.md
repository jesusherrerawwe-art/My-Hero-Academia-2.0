# Production System — How 50 Chapters Actually Get Written

*H.A.N.A.'s continuity + production pipeline for the Mariachi Escarlata novel. This document exists because memory is unreliable and files are not. If the story ever contradicts itself, the failure is a process failure — this is the process that prevents it.*

---

## 1. The honest truth about my memory

- Within a working session, I remember everything we discussed.
- **Across long gaps (days/weeks), I do not retain the conversation — I retain the files.** This repo, committed to GitHub, is my memory. Every decision, number, name, and scar must live in a file, never only in chat.
- Therefore: nothing is canon until it is written into a project file and Kevin has stamped it. Chat decisions get logged the same session they happen.
- Kevin owns the GitHub repo. Even if this platform or I disappear, the entire novel, bible, and outline survive in git. Nothing is locked inside a chat window.

## 2. The file architecture (numbered, never renamed casually)

```
mariachi-escarlata/
  00-production-system.md          ← THIS FILE (pipeline + rituals)
  01-research-el-charro-negro.md   ← folklore (done)
  02-oc-jesus-bible.md             ← Chuy canon + locked decisions (growing)
  03-canon-insertion-timeline.md   ← verified pre/post-Kamino canon (done)
  04-chapter-count-estimate.md     ← scope: ~50 ch / 3 volumes (draft)
  05-series-style-guide.md         ← [NEXT] voices, registers, Spanish rules, POV
  06-master-outline.md             ← [GAME PLAN] 50 chapter rows, one line each — THE CONTRACT
  07-trackers.md                   ← soul ledger, fissure log, guns, relationships, divergences
  chapters/
    vol-1/  01.md …  (one file per chapter, draft → revised → final in-file labeled)
  assets/  reference art
```

Rule: a chapter may not be drafted until `06-master-outline.md` has its row and `07-trackers.md` says where every counter stands.

## 3. The Canon Lock — what stops "Chuy sells tacos in Musutafu"

1. **Master outline (06):** every chapter gets one row — number, volume, title, POV, canon episode anchor, Chuy's decision, soul count at chapter start/end, cliffhanger. Kevin approves the full outline BEFORE any prose. Writing then means filling approved boxes, not inventing the road as we walk it.
2. **No mid-draft invention without logging:** if drafting reveals a better idea, it goes into a "PROPOSAL" note; Kevin rules; outline + trackers update; THEN prose changes.
3. **Every canon touch is licensed:** the Canon Divergence Ledger (in 07) lists each canon event the story uses, what really happens, and what we change. No chapter may silently contradict audited canon (`02-seasons/`, `03-characters/`).

## 4. The five living trackers (updated AFTER every single chapter)

1. **Soul Ledger** — running count 0→10; each claim/refusal with chapter, target, cape verdict, Chuy's choice, aftermath. Pre-filled start: 2/10 at arrival (Mendoza, El Alquimista — lien/"hollowed" mechanics pending ruling).
2. **Fissure Log** — mm of spread per chapter, location (jaw → neck → back → toward heart), cause; the physical countdown clock.
3. **Chekhov's Gun Schedule** — planted items and their payoff chapters: father's charro suit, sombrero tilt, spurs, trumpet + Hatsume sonic rig, mother's lucha-mask stitching, "Contrato — Pruebas" notebook, the horse, Duolingo, jamoncillo, the name SKULL KING, grey-stain Bakugo, the choking-child autopilot, etc.
4. **Relationship Map** — one line per important character: current standing, last scene together, next planned beat (Jirō, Deku, Bakugo, Eri, Kirishima, Tokoyami, Aizawa, Hatsume, Toga, Uraraka, the family, the squad, the Charro…).
5. **Spanish/Voice Register Log** — every Spanish phrase used + gloss, Chuy's Japanese-formality mistakes, recurring gags, Charro's old-Spanish voice lines, Grito transcripts (what he said vs what he remembers).

## 5. Per-chapter pipeline (7 stages, Kevin approves at gates ★)

1. **Beat sheet** (300–500 words): scenes, decision, cliffhanger, canon anchor, tracker deltas. ★ Kevin gate.
2. **Pre-flight read:** I re-read the outline row, the previous chapter, relevant bible/tracker/encyclopedia sections — every time, no exceptions.
3. **Draft v1** (~2,200 words; written in sections if long): allowed to be messy.
4. **Continuity pass** with a checklist: soul count, fissure mm, who knows OFA/contract, who's present in canon at this date, injuries, money/language logic, guns overdue, Spanish glossed.
5. **Prose pass:** voice, sensory texture (copal, cinnamon, bone), hooks in/out, light-novel pacing.
6. **Kevin review packet:** chapter + change note (what trackers moved, what canon we touched, 2–3 specific questions). ★ Kevin gate.
7. **Finalize:** label file FINAL, update 07 trackers + outline row, commit & push.

## 6. Session rituals (non-negotiable)

- **Start of every session:** read `00`, `06` (current + next row), `07`, and the last finalized chapter before writing anything.
- **End of every session:** log every decision made in chat into the files the same day; commit with a descriptive message; push.
- **Every 5 chapters:** a "serial bible review" — reread the last 5 chapters against outline + trackers; fix drift while it's cheap.

## 7. Kevin is the showrunner; I am the writers' room

- I draft, research, outline, continuity-police, and propose. Kevin rules on every plot decision, waifu, soul, and ending.
- Nothing ships to Wattpad without Kevin's eyes. Kevin can overrule any file at any time (I update canon to match).
- Kevin's weekly minimum ask is tiny: approve beat sheets + read chapters. He should never have to remember continuity — that's my job and the files' job.

## 8. Capacity reality vs April 27, 2027

- ~50 ch × ~2,200 words ≈ 105–115k words. One chapter = one drafting session + one revision session; ~1.5 chapters/week finishes first drafts by **late March 2027**, leaving April for trimming/formatting/submission.
- Output per turn is not a constraint that threatens this: chapters are produced in committed file increments; a 2.2k chapter is a normal single deliverable.
- Scope safety valve: 38-ch emergency cut documented in `04` if contest rules cap length.
- **Blocker still open:** official contest rules/URL (word cap, AI clause, fanfic legality). The pipeline assumes ~100k; rules could rescale it.

## 9. Failure modes and their specific antidotes

| Risk | Antidote |
|---|---|
| Chuy acts OOC / power drift | Bible PART 4 technique list + stats; outline states cape availability per scene |
| Canon characters wrong | Audited encyclopedia in-repo; canon anchor per outline row; divergence ledger |
| Forgotten plot threads | Chekhov schedule reviewed at every 5-chapter bible review |
| Soul/fissure math breaks | Soul ledger + fissure log updated post-chapter; totals printed in chapter headers for me |
| Deku diminished to lift Chuy | Style-guide law: canon cast at full competence; handoff earned, never stolen (locked in bible) |
| Romance/tone whiplash | Waifu decision recorded; relationship map forbids undeclared status changes |
| I "forget" across a gap | All of the above are files; session-start ritual forces reload |
| Tacos-in-Musutafu scene | It would never survive the beat-sheet gate. If Kevin wants a taco stand chapter, he EARNS it through the outline. 🌮 |
