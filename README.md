# ICFP Programming Contest 2026 — offline mirror

A static mirror of `https://icfpcontest2026.com/`, captured on
**2026-07-27, 08:38–09:00 UTC**, while the contest was still running
(it ended 12:00 UTC the same day). Served at <https://tarstars.github.io/>.

**The standings here are NOT the final results.** They were captured
before the 10:00 UTC scoreboard freeze, with ~3.5 hours of contest left.

What works: the problem statements and public test data for all 20
problems, per-problem and overall standings (pre-freeze), the textbook,
rules, grading and language reference pages, and the in-browser littleman
editor with its WebAssembly VM. Sign-in, submitting and the dashboard
needed the live server and are inert.

## Unofficial community exercises

Post-contest additions are kept separate from the captured archive and are
clearly labelled as unofficial:

- [Fibonacci](/problems/fibonacci/) — a small one-man exercise with a
  [worked solution and execution trace](/community/fibonacci/).
- [Array Sum](/problems/array-sum/) — consume a length-prefixed list as a
  stream and compute its sum without storing the array.

## Analysis: Team Unagi's approach

A detailed engineering study of team Unagi's published repository —
their per-problem approaches, contest operation and machinery, compared
with ours — is at [`/unagi-analysis/`](/unagi-analysis/)
([PDF](/unagi-analysis/unagi-icfpc2026-analysis.pdf)). Sources and
research notes live in
[tarstars/icfpc2026-claude](https://github.com/tarstars/icfpc2026-claude)
under `reports/unagi-analysis/`.

The raw captured JSON (API responses, per-problem standings, our team
wheezards' submission records) is browsable under [`/archive/`](/archive/).

Provenance — how the capture was made, request log, and the build script
that produced this tree — lives in
[tarstars/icfpc2026-claude](https://github.com/tarstars/icfpc2026-claude)
under `archive/site-snapshot/` (`RESTORE.md`, `fetch-log.csv`,
`build_pages.py`). All content belongs to the ICFP Contest 2026 organizers;
this is a community archive of a site that would otherwise disappear.
