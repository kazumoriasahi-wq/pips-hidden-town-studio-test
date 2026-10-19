# 20-chapter verification — 2026-10-19

## Automated checks

node build-chapters.cjs and node test.cjs pass. Validated 20 distinct original JPEG hashes, five unique difference IDs per chapter, all 100 target centers, ellipse bounds, bilingual clues, referenced assets, legacy save migration, independent chapter reset, 20-chapter completion, hosted chapter20 cloud save without browser local storage, and an in-memory future chapter21 append/restore. Future chapter21 was removed after the test; it is not a placeholder in the game.

## Browser interaction checks

Local HTTP server, real rendered UI and pointer actions: all 20 chapters selected through the four guide pages, all 100 difference targets clicked, all chapters reached 5/5 with the keepsake button available. Alternated original/changed panels by chapter groups. Verified final chapter keepsake has no nonexistent next chapter. Reload restored 20/20 complete. Resetting chapter20 reduced the count to 19/20 while other chapters retained completion. Additional selective resets and final repaired bird/seaweed/sack targets were checked after visual edits. Legacy completed/partial local records remained readable.

Checked two-step clue text/location reveal, linked zoom scroll (both panels settled at identical left22/top108), English/Japanese UI, sound control, 390x844 and 320x740 layouts without horizontal overflow (body375/305 pixels respectively), desktop chapter guide, and zero captured browser error logs during local play. This is browser validation, not a physical iPhone test or audible music-quality certification.

## Visual QA

Reviewed all 100 original/changed detail pairs in enlarged contact sheets. Reworked ignored or ambiguous generated changes, widened masks where necessary to include complete changed objects, and feathered patch edges. Final additional changes include a missing greenhouse bird, a missing tidepool leaf branch and a rectangular-to-oval sack patch. Different chapters use different paintings, settings and compositions. Generic change categories such as shape/count/markings recur on different props; identical scenes are not reused.

All rendered pairs share the original scene outside five local patch masks, so incidental changes elsewhere in the generative edit do not become extra answers. Minor painting texture differences inside those masks can remain; this is not a pixel-identical manual illustration workflow.

## Release scope

Only pips-hidden-town-studio-test is updated. Existing nine games and the older PIP release are untouched. Pre-expansion three-chapter ZIP retained locally. Pages deployment and public smoke test are checked separately in the release record. The Playables adapter is retained and tested with a mock SDK; official hosted QA/acceptance is still required.

## Five additional chapters — 2026-10-19

All25 chapters/125 target centers, bilingual clues and assets pass automated checks. Compared the existing20-chapter runtime: first17 extra chapter records are identical, as are level.js, engine.js, game.js, music.js, platform.js and style.css. Mock hosted save still works; future chapter26 append and restore pass. All25 new difference crops visually inspected using actual feathered masks; suitcase and hammock masks widened to eliminate partial remnants.

Actual browser pointer clicks found all five targets in each new chapter21–25, alternating original/changed pictures; all five reached5/5 and the last keepsake omitted the next-chapter button. Reload restored new completion records. Resetting only chapter25 retained chapter21–24 completions and old records. Bilingual hints, two-step reveal and linked-zoom views checked. No captured browser errors. Responsive layout engine unchanged; physical iPhone verification of these new chapters remains for the owner.
