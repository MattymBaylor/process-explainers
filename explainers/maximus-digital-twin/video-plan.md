# MAXIMUS — A Digital Twin, End to End · Video Companion Plan

Silent video version of the interactive 3D explainer. Brand language throughout:
**true black `#000000` ground · dark glass panels (`#0d0d0d` → `#151515` → `#1f1f1f` elevation ladder) · GMS blue `#00d4ff` as the single hero glow · red `#c05b4d` reserved for the fail-closed branch · Poppins/Lora type · GMS emblem watermark bottom-right.** No green except two success beats (send confirmation, absorbed memory). Slow, deliberate camera; the finale is the flywheel ring closing over the full board.

Target: ~90 s master cut (10 scenes × 7–10 s), 16:9, 24 fps, silent-first with optional sound cues below.

**Framing rule — the whole board, always.** Every shot keeps the ENTIRE board in frame with margin so the viewer never loses where they are in the process: the active panel reads through glow and light, never through zoom. There are no push-ins and no close-ups anywhere in the film. Scene 1 opens on the tilted establishing view and glides to a straight-on full-board frame; every later scene holds that frame, moving only in subtle lateral/vertical drifts. Scenes 1 and 10 are always full-board.

---

## Scene plan

| # | Scene | Duration | Camera | On screen |
|---|---|---|---|---|
| 1 | The body plan | 10 s | Opens on the tilted ~20° establishing view, then glides to a straight-on full-board frame | Five glass zones labeled: BRAIN (Claude, highest slab), NERVOUS SYSTEM (LangGraph), HANDS (connector layer), MEMORY (Qdrant + markdown), SPINE (Postgres, wide slab at the base). Everything idle, faint white edge glow only. |
| 2 | Mail arrives | 8 s | Ease left in a wide frame — Gmail panel prominent left-of-center, nervous system and spine still visible | A blue comet enters from off-frame into "Gmail In"; a thin blue thread simultaneously drops down the left side and lights the spine slab — the checkpoint. Caption: *"webhook → ingest · checkpoint written"*. |
| 3 | Classify | 9 s | Rise slightly, staying wide — Classify and the brain slab both in frame with the neighboring columns | Blue particles run Gmail → Classify, then arc UP into the Claude panel, which blooms. A "Band 2" chip lights on the center display. Caption: *"no judgment in the graph — judgment lives only in the brain"*. |
| 4 | Memory recall | 8 s | Sweep right in a wide frame — memory column prominent, center display and nervous column still visible | A blue arc crosses the whole board from Classify to the Qdrant cylinder panel; a hub-note card and three linked-thread bars materialize on the center display. |
| 5 | Voice tier — fail closed | 9 s | Wide full-board hold, the left half brightest; the red branch reads through its own red glow — no push-in | Five tier chips A–E; C fills blue. Then the ONLY red element of the film: a short red tube snaps from Voice Tier to the Approval Queue shield panel, pulsing red. Caption: *"unplaceable → approval queue · never guess"*. |
| 6 | Draft | 8 s | Glide down, staying wide — Draft prominent with Claude above and the memory column in frame | Blue threads converge on Draft from above (Claude/Opus) and from the right (memory hits); text bars type themselves onto a glass letter on the center display. "Opus · voice" chip. |
| 7 | Nothing sends | 8 s | Settle lower-center in a wide frame — queue prominent, spine and memory column visible | The draft slides into a queue list and stops. One question card flips up: **"Send or hold? — S / H"**. All particle motion freezes for a beat — stillness is the message. |
| 8 | He answers S — one door out | 9 s | Follow the resume thread down to the spine, then left to Egress with the look only — wide throughout, the whole board in frame, its left half brightest | An "S" chip lights; a blue pulse rises from the spine slab (resume from checkpoint), runs Brief → Egress. The Egress panel is drawn as a single glowing doorway — the only opening in a solid wall. The message comet exits through it and off-frame. Green "sent" micro-chip (success beat #1). |
| 9 | Overnight digestion | 9 s | Drift right and down, lights dimmed to night — the whole board in frame, memory column brightest | The moon-marked Consolidate panel wakes; five pills cascade — split → filter → dedupe → link → embed — and a stream of small note-cards flows into the markdown stack and the Qdrant cylinder, which glow soft green as they absorb (success beat #2). Caption: *"markdown is truth · Qdrant is the index"*. |
| 10 | The flywheel (closing shot) | 12 s | Full-board frame throughout, the Claude panel glowing; a slow slight widening as the ring ignites | "3 weeks later" title card. One small mention-card touches the board — and the entire history lights along a single closed blue loop circling all five zones, particles orbiting it continuously. The frame eases a touch wider until the loop reads as one glowing ring around the organism. Hold 3 s. GMS emblem resolves bottom-right. |

---

## Generation prompts

### Veo (video clips, one per scene)

Shared style block — prepend to every prompt:

> Cinematic 3D motion graphics, true black void background, floating dark glass UI panels with rounded corners and faint hairline edges, subtle depth-of-field, slow deliberate camera, single electric-blue glow accent (#00d4ff) with additive bloom, drifting micro-dust particles, premium fintech-keynote aesthetic, no text other than specified captions, 16:9, photorealistic render quality. WIDE FRAMING: the ENTIRE board of panels stays in frame with margin at all times — the active panel is emphasized by glow and light, never by zooming; the camera NEVER pushes in, moving only in subtle lateral or vertical drifts.

1. **Body plan:** "A tilted board of five dark glass slabs at different elevations arranged like an organism — a small high slab at top labeled BRAIN, a tall central column NERVOUS SYSTEM, left column HANDS, right column MEMORY, one wide low slab at the base labeled SPINE; the camera glides slowly from the tilted establishing angle to a straight-on view with the whole board filling the frame with margin. Panels idle, lit only by faint white edge glow and a dim grid floor far below."
2. **Mail arrives:** "Wide shot of the full five-zone board; a glowing blue comet streaks in from the left edge and lands on a dark glass panel with an envelope icon at the board's left; on impact a thin blue filament drops down the board and ignites the long low slab at the base; a soft ripple of blue light crosses the slab while the rest of the board stays visible and dim. Caption fades in: 'checkpoint written'."
3. **Classify:** "Wide view holding the whole board; blue light particles travel along a thin tube from an envelope panel to a branching-node panel, then arc steeply upward into an elevated glass panel with a brain icon that blooms with blue light; a small chip reading 'Band 2' illuminates on the central glass display; the surrounding dim columns stay in frame for context."
4. **Memory recall:** "Camera sweeps gently right, keeping the whole board in frame, as a long blue arc of particles crosses the dark board and enters a glass panel bearing a database-cylinder icon in the right column; a contact card and three small linked bars assemble themselves from light on the central display; the left columns remain visible and dim."
5. **Fail closed:** "Wide shot of the full board, its left half lit and the other zones dim in frame; on the central display five glass chips labeled A B C D E appear and the middle one fills electric blue. Then, with the camera holding the same wide full-board frame, a short tube of deep red light (#c05b4d) snaps on, connecting a sliders-marked panel to a shield-marked panel that pulses red — the only red in an otherwise blue-and-black frame, read entirely through its own glow. Caption: 'never guess'."
6. **Draft:** "Wide framing with the whole board visible; two thin blue filaments converge from the elevated brain panel above and from the right-hand memory column onto a glass panel with a pen icon; on the central glass display, lines of text draw themselves as glowing bars inside a letter layout; a chip reading 'Opus' glows blue; neighboring panels stay dim but present."
7. **Nothing sends:** "Wide shot holding the board; a glowing document slides into a vertical queue on a lower glass panel and halts; every moving particle in the frame freezes; a single card flips up on the central display reading 'Send or hold? — S / H'; two seconds of total stillness with the whole dim board in frame."
8. **One door out:** "Wide framing keeping the whole board in view, its left half and the base slab brightest; a chip reading 'S' lights; a pulse of blue rises from the wide base slab and travels through a queue panel to a panel rendered as a single glowing arched doorway in a solid dark wall; a comet of light exits through the doorway and off-frame; a tiny sage-green 'sent' chip blinks once; the rest of the board stays dim in frame."
9. **Overnight digestion:** "Night scene, all panels dimmed, the full board held in a wide frame; a crescent-moon panel in the right column wakes and five pill-shaped stages cascade down the central display — split, filter, dedupe, link, embed — as a stream of tiny note cards flows into a document stack and a database cylinder that absorb them with a soft sage-green glow."
10. **Flywheel finale:** "The entire five-zone board held in frame, a single elevated brain panel glowing; a small card touches the board and a single continuous ring of electric-blue light ignites around all five zones, particles orbiting it endlessly; the camera eases only slightly wider until the ring reads as a halo around the whole machine; hold on the closed loop."

### Nano Banana (stills — title card, poster, thumbnails)

1. **Title card:** "Minimal title frame on pure black: the words 'MAXIMUS — a digital twin, end to end' in white Poppins, small electric-blue underline glow (#00d4ff), tiny white geometric emblem bottom-right, faint dark glass panel bokeh in the background."
2. **Poster / thumbnail:** "Isometric board of dark glass panels on true black arranged as five zones with one elevated brain panel glowing electric blue, one thin red branch visible on the left, a blue ring of light circling the whole board, cinematic bloom, no text."
3. **Scene-5 insert still:** "Five dark glass chips labeled A–E, center chip filled electric blue, a red-bordered warning strip below reading 'unplaceable → approval queue', dark UI aesthetic, black background."
4. **Finale still:** "A closed loop of glowing blue light encircling a tilted board of dark glass panels seen from high and far, tiny particles along the loop, black void, single word caption 'flywheel' in white Poppins lower third."

---

## Sound cues (optional layer — video works silent)

| Scene | Cue |
|---|---|
| 1 | Low room-tone drone fades in; one soft sub swell as the five zones resolve |
| 2 | Single glass "ping" on comet impact; muted low thud when the spine lights (checkpoint) |
| 3 | Rising shimmer as particles climb to the brain; soft synth blip on the "Band 2" chip |
| 4 | Airy whoosh left-to-right; three quick ticks as the linked threads populate |
| 5 | Warm blue tone for Tier C — then a dry, damped buzzer (short, not alarming) as the red branch snaps on; silence after |
| 6 | Soft pen-on-glass scratches syncing with the text bars |
| 7 | All ambience ducks to near-silence; one suspended note held under the "Send or hold?" card |
| 8 | Confident key-press click on "S"; deep whoosh as the comet exits the door; tiny bell for the green "sent" chip |
| 9 | Slow nocturnal pad; five gentle descending notes, one per pipeline stage |
| 10 | Full swell: the drone from scene 1 returns one octave up, loops seamlessly as the ring closes; hard cut to silence on the emblem |

---

**Continuity rules:** one hero accent (blue) per frame; red appears in scene 5 only; green only on the two success beats; camera never flies backward — cuts snap; the whole board in every frame — no push-ins, no close-ups, attention steered by light only, and scenes 1 and 10 are always full-board; keep the GMS emblem watermark in the final 3 s of every cut-down.
