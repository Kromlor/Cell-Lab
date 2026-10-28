# Cell Lab

An interactive plant and animal cell learning app (Grade 7, LS1-2). Open `index.html` in a browser; keep `app.js` and both cell images beside it.

## v1.2 (2026-10-27)
- Students enter their first name + last initial and their teacher's email at the start (email is checked and remembered on that device).
- New **05 · Send report** tab: opens a filled-in Gmail message to the teacher (backups: email app, copy). The report covers both cells (parts placed, wrong drops and clues per part, resets) and the first-try Quick check answers, plus time spent.
- Warns about unfinished work but still lets students send. "New student" clears the computer and keeps the teacher email.
- Nothing is stored online; data stays in the browser until the student presses Send.

## v1.1 (2026-10-26)
- Build mode now shows the full animal or plant cell picture as the background. Students drag each part onto its spot; every spot is an identical dashed circle (no letters or numbers), wrong drops just say try again, and a correct drop adds a check and the part's name tag. The A–L clue list is gone; "Show a clue" gives the part's job.
- Restored the full animal and plant cell pictures (the earlier uploads were cut off). Pixels unchanged, just losslessly compressed.
- Numbered/lettered targets now sit on the right parts of each picture (e.g., plant cytoplasm and cytoskeleton were on a mitochondrion and a chloroplast; animal ribosome and cytoplasm targets overlapped).
- Build mode: "Show a clue" gives a hint instead of the exact answer; Read aloud reads the clue list instead of the answer; a correct match says so and moves to the next part; already-finished targets say so.
- Screen readers can now reach the targets (the cell drawing was marked as a plain image).
- Visible keyboard focus on targets, part names no longer cut off on phones, teacher guide wording fixed, speech stops when you switch tabs.
