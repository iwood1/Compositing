# [Working Title: Room 467 / Compositing]

A first-person walking-sim about restoring a lost anime from salvaged, mismatched
animation cels — and discovering that finishing a scene doesn't just complete a
cartoon, it quietly rewrites the world around you, including what people remember
of their own pasts.

Tone touchstones: Murakami (passive competent protagonist, wells/thresholds,
doubling, unresolved plot threads), *Under Ninja* / *Himizu* (dropped threads by
design), *Mushishi* (effects shown plainly, causes never explained), *Kentucky
Route Zero* (scene-logic over simulation), *Oath* (persistent world-state that
silently reshapes future play).

---

## 1. Premise

A single continuous, walkable market district — a Nakano Broadway analog —
contains the scattered physical remains (cels, genga, settei) of an anime that
aired briefly, decades ago, and was never digitized or preserved. The player is
an archivist/restorer piecing it back together, one scene at a time, at a
physical compositing desk.

Whether the show "really" existed in complete form before the player started is
never confirmed. Some NPCs remember it vividly; some have no memory-slot for it
at all, and this doesn't correlate cleanly with anything the player can verify.

## 2. Core Loop

No day/night gating, no phase-switch, no menus interrupting traversal. Everything
happens inside one continuous walking loop:

1. **Walk.** Free movement through the district, no fast travel, no map markers.
2. **Notice a request or a find.** Requests arrive passively (a note at the desk,
   a regular's aside) — never a quest board. Finds are embedded environmentally
   (a box to rummage, a cel half-visible in a window), discovered by looking.
3. **Handle it.** Pick up and examine in-hand (light, registration marks, cut
   number) anywhere — no station required for this step. Ambiguity about
   authenticity/origin can persist; the game never adjudicates for the player.
4. **Work at the desk.** The main verb. Lay out layers (background / character /
   effects), align cut numbers, restore Condition, fill gaps with invented frames
   once that's unlocked. Physically tactile, unhurried.
5. **Play the reel.** No confirm screen. The player simply stops touching it and
   it goes live — marked only by a single quiet audio tell (a soft tape-warp cue),
   never explained.
6. **Continue walking.** No dedicated "go check what changed" phase — noticing
   ripples (world drift, NPC dialogue, fabricated-past lines) folds into ordinary
   continued wandering, using the same observational attention as finding cels.

Requests, the lost show, and the player's own collector-completionism instinct
are the three independent drivers of "why keep playing" — deliberately mundane on
the surface so the compositing/world-response side is the only place strangeness
lives.

## 3. The Space

One continuous district, never a level-select or separate zones.

- **Cosmetic/atmospheric drift** (common, low-stakes): texture, signage,
  architectural era, lighting, weather. Happens often; this is the bulk of
  "world response."
- **Topological change** (rare, high-weight): a new corridor, a vanished stall.
  Reserved for milestone moments — finishing a whole episode, not a single scene.
- **Fixed anchor landmarks** (a fountain, a stairwell, the entrance) never
  change, preserving wayfinding purchase so drift reads as strange rather than
  as disorientation/backtracking pain.

## 4. Systems

### 4.1 Cels & Condition
Cels are found, not drawn from a menu. Each carries Condition (physical decay if
left unsleeved/unstored) — a soft resource pressure, no hard fail state. This is
also a direct expression of the "care vs. expedience" values system (4.6).

### 4.2 Compositing
Backgrounds, character layers, and effects layers stack at the desk. Because
found cels come from unrelated productions, mismatches are the natural default
condition, not a desperation move — dialogue plays over a background it wasn't
written for, and nothing flags this. This is a free, built-in source of
absurdism (see 4.8).

### 4.3 Reference Capture
A bounded, deliberate (not instant-snapshot) mechanic: the player can sketch or
photograph specific flagged objects/spaces encountered while wandering. This
material becomes usable once the player unlocks inventing original frames
(Authorship phase, 4.9), closing a loop where something noticed in the world
becomes something drawn into a reel — which can then bleed back into the world's
version of that same object.

### 4.4 Resonance Tags
A scene/reel carries 1–3 tags at light/strong strength, propagating outward to
NPCs and ambient/architectural proxies on a delay. Seven tags, chosen for
built-in tension rather than orthogonality:

| Tag | Represents | Affinities |
|---|---|---|
| Care | nurturing, protection, tenderness | doctors, parents, generous shopkeepers |
| Authority | imposed hierarchy, control, law | politicians, police, landlords |
| Rebellion | defiance, refusal, escape | criminals, runaways, black-market dealers |
| Longing | nostalgia, unfulfilled want | regulars, collectors, the show's original fans |
| Violence | rupture, harm, sudden change | soldiers, chaotic criminals, ambient disasters |
| Order | chosen structure, ritual, correctness | archivists (the player), craftsmen, cult figures |
| Concealment | secrecy, forgery, double lives | forgers, spies, shadier dealers, the show itself |

Tension pairs: Care↔Violence, Authority↔Rebellion, Order↔Concealment. Longing has
no opposite — it intensifies whatever it's paired with, and resolves over time
(unaddressed) into either **Contentment** (paired with Care) or **Apathy**
(paired with Concealment, or simply left untouched) — see 4.7.

Combination rules:
- Opposed tags in one scene don't cancel — they produce standing contradiction
  (an NPC who is legibly both gentle and suddenly capable of harm).
- Same-tag reinforcement across multiple plays compounds — nothing happens after
  one Rebellion-tagged scene, but a third tips a visible change.
- Concealment-tagged ripples are the ones most likely to produce contradictory
  NPC testimony, and are the mechanism behind the late-game "your own inventions
  get authenticated as real" beat (4.9).

### 4.5 Representation Scope (who gets affected)
Full individual authorship for "everyone" doesn't scale and reads as noise.
Two-tier solution:
- **Named anchor NPCs** (small cast — dealers, regulars, one doctor, one
  low-level bureaucrat, one criminal-adjacent figure): hand-authored arcs
  triggered by resonance thresholds. These are the player's only fully legible
  proof-points that the system is real.
- **Ambient/systemic proxies** for everyone else: overheard radio/news
  fragments, shifting market prices/stock, and — at the largest, slowest
  register — architecture and civic space (a courthouse's facade drifting era
  over several visits). "You changed politics" is never a headline; it's a
  building that wasn't built that way last time.

### 4.6 Player Values (shown, never scored)
No morality meter. Values surface through:
- A silent player resonance-signature, revealed only via how strangers already
  treat the player on first meeting (reputation preceding contact, never
  displayed as a stat).
- The compositing desk's own history (what you restored vs. left broken, vs.
  invented) functioning as an undeniable diary.
- Restore-vs.-leave-flawed choices on damaged cels (Condition system, 4.1).
- Invented frames in the Authorship phase (4.9) as the clearest, most direct
  values-expression in the game.

### 4.7 Memory-Mandala Effect
Completing/playing a reel doesn't just change the world going forward — it
retroactively changes what NPCs remember having watched, and can retroactively
alter a trait tied to their formative relationship with the show, which then
changes their downstream behavior (a Moore-esque "writing as magick" causality:
edit the fiction, edit the person, edit what they do to the world).

Rules to keep this legible without becoming a Fable-style scored system:
- NPCs never acknowledge a change themselves — no "wait, that's not how I
  remember it." The dissonance lives only in the player's own memory of an
  earlier conversation.
- Trait-driven behavior changes surface *behaviorally*, never as a stat pop-up —
  a stall gone, a friendship turned to conflict, a risk taken that wouldn't have
  been before.
- Two NPCs' memories of the same episode can both stand even when they
  contradict (one remembers a death, another insists it never happened) — never
  adjudicated.
- Trigger is consistently tied to PLAY events (never random), so attentive
  players learn to associate compositing with "go see what shifted" — this is
  the core feedback loop for the whole system.
- Some NPCs have no memory-slot for the show at all — not "I don't remember,"
  genuine non-response, as if asked about something that was never real. This
  should almost-but-not-quite correlate with player progress.

### 4.8 Fabricated Player Past
NPCs reference things the player apparently already did, casually, that never
happened from the player's perspective — loosely tracking the player's own
resonance-leanings without ever matching a traceable event.
- **No confirm/deny dialogue option, ever.** This is the load-bearing guardrail
  that keeps it from becoming a puzzle to solve.
- Brief, embedded delivery only — one aside in an otherwise ordinary
  conversation, never a dedicated branch or cutscene.
- Contradictory fabricated pasts across different NPCs are allowed and
  encouraged (same rule as 4.7).
- Rarely (once or twice per playthrough), a fabricated past detail comes true
  after the fact, unprompted — kept scarce so it reads as a genuine chill, not a
  huntable pattern.
- Possible late-game convergence: an NPC misremembers the player as a character
  *in the show itself* — collapsing "what happened to the show" and "what
  happened to me" into one permanently unresolved question.

### 4.9 Authorship Phase
Found material eventually runs out or has unfillable gaps, forcing the player to
draw/invent original frames (using Reference Capture material, 4.3). No
announced transition between Restoration → Drift → Authorship — the player
should notice retroactively that they've stopped restoring and started writing.
World transformations scale up accordingly (local → district-wide) as
authorship deepens.

Player-made completed episodes are quietly uploaded somewhere (an obscure board,
an archive site, a shared drive nobody remembers setting up) — the destination
itself may drift between visits. This doesn't need to make causal sense, since
the show's past is already unstable by design.

### 4.10 Cultural Fate (global state)
The show's in-world reputation is a slow global variable shaped by cumulative
player choices (episodes finished, coherence vs. fragmentation, in-world
leaks/screenings):
- **Forgotten** — cels stay cheap/scarce/personal; almost no one has the
  memory-slot at all.
- **Cult/rediscovered** — prices spike, forgeries proliferate (re-engaging the
  authentication mechanic on content partly written by the player), altered
  personalities ripple into a small visible subculture.
- **Mega-franchise** — the show "never stopped"; official studios produce new
  material referencing player inventions, folding them into canon without
  consent. Devalues authentic cels relative to reproductions. Late-game hook:
  player encounters cels of scenes *they* invented, authenticated by other
  dealers as real, with no tool to assert the truth.

Longing/Contentment/Apathy (4.4) should visibly track this axis — NPCs whose
formative trait was tied to the show drift toward Apathy specifically when the
show fades from relevance.

### 4.11 Absurdism Techniques (craft notes, not systems)
- Mismatched-layer logic generates absurdity for free (4.2).
- Literalized metaphor: figures of speech staged literally, uncommented ("dead"
  business → a stall with genuinely no living customers, ever).
- Withheld causality, not withheld information — effects shown plainly, no
  hidden mechanism to eventually solve (Mushishi structure).
- Recursive self-reference — a found cel depicting the player's own desk or an
  NPC, slightly wrong, drawn before the depicted event occurred.
- Dropped threads by design — hooks introduced with real weight, then never
  resurfaced, no closure.
- Contradiction without correction — two mutually exclusive facts both stand.
- One recurring absurd anchor motif (an object or animal — e.g. a specific cat
  breed, radio model, umbrella color) appears across unrelated requests far more
  often than chance suggests. Never confirmed as causally meaningful, even to
  the design — this ambiguity should stay genuinely undecided, not just hidden
  from the player.

## 5. Requests (mundane by design)
Early requests are pure generic market chores (appraise this, restore that, find
an unrelated item) — no connection to the show, protecting the "niche personal
obsession" framing at the start. As cultural fate shifts, requests can start
obliquely touching the show without either party consciously flagging the
connection. No quest markers, no map icons — delivery is a note, a message, a
mumbled aside.

## 6. Session Design
Designed for short-to-medium sessions (20–40 min), not marathon/endurance play:
- No timer, no forced continuous attention, no phase gating.
- Changes must be detectable across separate sessions (a five-minute gap and a
  five-day gap should both work), not require an unbroken sitting.
- A private, diegetic index-card-style log of the player's *own completed reels*
  (never of world-changes caused) helps reorientation after a break without
  breaking the "nothing is explained" rule.

## 7. Scope Boundaries (hand-authored vs. procedural)
**Hand-author:** the resonance vocabulary (7 tags, fixed), the anchor NPC cast
and their specific arcs, the lost show's actual content (fragments/episodes).
**Procedural:** which resonances combine and at what strength, timing/delay of
when ripples surface, environmental/architectural drift generation.

Rationale: procedurally generated personality change or found-footage content
reads as noise; procedurally generated propagation timing and combination reads
as the desired uncanny unpredictability.

Target scope for a single playthrough: **one cour** (~12–13 episodes) of the
lost show, not a full series — small enough that individual gaps/inventions
stay personal and legible rather than blurring into a statistic. Completion
percentage varies naturally by player pace; there's no fail state for stopping
early, only a smaller/sadder final "viewing."

## 8. Vertical Slice Definition (first build target)
- One small walkable chunk of the district: a few connected stalls + the desk,
  fixed anchor landmarks, cosmetic-drift only (no topology change yet).
- Movement + object pickup/examine.
- One functioning compositing interaction (stack 2–3 layers, see them combine
  visually).
- 2 resonance tags, 1 anchor NPC with a visible delayed reaction.
- Out of scope for the slice: fabricated-past system, cultural-fate variable,
  Authorship/reference-capture, topological change. Layer these on after the
  core walk → find → desk → play loop is proven to feel good on its own.

## 9. Tech Notes
- **Engine (slice):** Three.js, single self-contained HTML file — fastest path
  to something literally walkable and playtestable. Environment note: pinned to
  r128 (no OrbitControls variants requiring newer builds; no CapsuleGeometry —
  use Cylinder/Sphere or custom geometry instead). No real asset-import
  pipeline at this stage — simple primitive geometry + CSS-driven
  material/color work for the slice, not imported 3D models.
- **Later/full build:** move to a real project (Claude Code proper, local repo
  + build system) once the slice's loop is validated, to support modeled
  environments, asset import, and a more serious codebase structure.
- **Cross-machine workflow:** repo-based via GitHub + Claude Code on the web
  (claude.ai/code) for cloud sessions when away from the primary machine;
  `git pull`/local Claude Code when back on it.

---

*This document is a living spec — expect it to be edited as the vertical slice
surfaces what actually feels good to play versus what only sounded good in
discussion.*
