# Modernization Verification Report

- Source: `output/Carcassonne`
- Repo: `output/Carcassonne/.repo` (citations verifiable)
- Generated: 2026-09-16T11:51:52+00:00

## Specification.md

**Status: PASS** - citations 278/278 resolved (0 skipped); references 398/398; mermaid: 1 block(s)

Density warnings: § 11. Cross-References to Sibling Models (no citations/references)

## ClassModel.md

**Status: PASS** - citations 575/575 resolved (0 skipped); references 534/534; mermaid: 2 block(s)

Warnings: node map at line 687 missing ids: o

## DatabaseModel.md

**Status: PASS** - citations 370/370 resolved (0 skipped); references 241/241; mermaid: 1 block(s)

## DomainModel.md

**Status: PASS** - citations 305/305 resolved (0 skipped); references 320/320; mermaid: 1 block(s)

Warnings: node map at line 157 missing ids: o

## UseCaseModel.md

**Status: PASS** - citations 348/348 resolved (0 skipped); references 526/526; mermaid: 1 block(s)

## ActivityDiagram.md

**Status: PASS** - citations 382/382 resolved (0 skipped); references 372/372; mermaid: 5 block(s)

## Semantic Findings (advisory)

Semantic verifier: agent-30 (explore, read-only) — cross-document coherence of the modern target. Verdict: ok. 0 blockers, 1 major, 2 minor. All six docs describe ONE coherent TS-first target (React 19 + Vite 7 / Node 24 + ws 8.x + zod, no DBMS, Docker + GitHub Actions). Fix S-1 in ClassModel, S-2 in Specification/DomainModel, S-3 in Specification; everything else verified consistent.

Full detail: `verification/semantic-findings.json`. All findings were **fixed in the r4-advisory round** by targeted fixer agents; mechanical verify re-run after the fixes: exit 0, all six docs PASS.

| ID | Severity | Check | Fixed by | Fix |
|----|----------|-------|----------|-----|
| S-1 | major | decision_fidelity | agent-31 (ClassModel fixer) | ClassModel CL-22 (line 478) and CL-35/ProtocolSchemas (line 517) now state M-5 adds **two** server->client variants (RegistrationRejected, InvalidMove): 8 legacy + 2 = 10, citing `src/Backend.elm:99-102` + `src/Backend.elm:185-186`; consistent with Specification and UseCaseModel. (Note: the plan-level M-3/K-6 "9" count is a known plan count error, already flagged in UseCaseModel; docs state 8 legacy / 10 with M-5.) |
| S-2 | minor | citation_hygiene | agent-32 (Specification), agent-33 (DomainModel) | `src/Types.elm:67-70` -> `68-70` at Specification.md:153 and DomainModel.md:314 (line 67 is the `type ToFrontend` declaration; the variant spans 68-70). UseCaseModel's 68-70 spans were already correct. |
| S-3 | minor | alignment | agent-32 (Specification fixer) | Specification.md:128 reworded: M-8 (BackendModel -> GameSession) applies to the BackendModel/Evergreen state machine; FrontendModel is "modernized to ClientState (M-1), shape kept (K-5)", matching line 113 and the Class/DB models. |

Verified clean by the semantic verifier (no findings): stack coherence (all six docs agree on TS 5.x + React 19 + Vite 7 / Node 24 + ws 8.x + zod / no DBMS / Docker multi-stage + GitHub Actions), decision fidelity (M-1..M-8 consistently applied), buildability of the target description, kept-element fidelity (draw stack 71 tiles, 24 designs, 72 incl. starting tile; cloisters tiles 3/4; rotateLeft = +90 degrees; 2x city bonus mid-game; skip costs 0; playerLimit 5; 7 meeples/player; debug overlay pointer-events none), ledger closure (UNVERIFIED only inside Resolved sections; deferred: A-2, A-5, A-11, A-12, A-23, A-34, A-37), directive sweep (D-1, D-2), cross-doc alignment (16 DB entities 1:1 with DomainModel; use-case-to-PR mapping UC-01<->PR-4, UC-03<->PR-3, UC-04<->PR-1, UC-06<->PR-2, UC-07<->PR-5; UC-02/05/08 out of activity-scope), and citation hygiene elsewhere.

