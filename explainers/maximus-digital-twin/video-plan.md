# MAXIMUS — A Digital Twin, End to End · Video Companion Plan

Silent video version of the interactive 3D explainer. Brand language throughout:
**true black `#000000` ground · dark glass panels (`#0d0d0d` → `#151515` → `#1f1f1f` elevation ladder) · GMS blue `#00d4ff` as the single hero glow · red `#c05b4d` reserved for the fail-closed branch · Poppins/Lora type · GMS emblem watermark bottom-right.** No green except two success beats (send confirmation, absorbed memory). Slow, deliberate camera; the finale is the flywheel pull-back.

Target: ~90 s master cut (10 scenes × 7–10 s), 16:9, 24 fps, silent-first with optional sound cues below.

---

## Scene plan

| # | Scene | Duration | Camera | On screen |
|---|---|---|---|---|
| 1 | The body plan | 10 s | Slow push-in from wide, board tilted ~20° | Five glass zones labeled: BRAIN (Claude, highest slab), NERVOUS SYSTEM (LangGraph), HANDS (connector layer), MEMORY (Qdrant + markdown), SPINE (Postgres, wide slab at the base). Everything idle, faint white edge glow only. |
| 2 | Mail arrives | 8 s | Fly left, settle on the Gmail panel | A blue comet enters from off-frame into "Gmail In"; a thin blue thread simultaneously drops down the left side and lights the spine slab — the checkpoint. Caption: *"webhook → ingest · checkpoint written"*. |
| 3 | Classify | 9 s | Rise diagonally toward the brain slab | Blue particles run Gmail → Classify, then arc UP into the Claude panel, which blooms. A "Band 2" chip lights on the center display. Caption: *"no judgment in the graph — judgment lives only in the brain"*. |
| 4 | Memory recall | 8 s | Sweep right across the board to the memory column | A blue arc crosses the whole board from Classify to the Qdrant cylinder panel; a hub-note card and three linked-thread bars materialize on the center display. |
| 5 | Voice tier — fail closed | 9 s | Tight on Voice Tier, then a small pull to reveal the red branch | Five tier chips A–E; C fills blue. Then the ONLY red element of the film: a short red tube snaps from Voice Tier to the Approval Queue shield panel, pulsing red. Caption: *"unplaceable → approval queue · never guess"*. |
| 6 | Draft | 8 s | Glide down to the Draft panel | Blue threads converge on Draft from above (Claude/Opus) and from the right (memory hits); text bars type themselves onto a glass letter on the center display. "Opus · voice" chip. |
| 7 | Nothing sends | 8 s | Settle on the EOD Brief panel | The draft slides into a queue list and stops. One question card flips up: **"Send or hold? — S / H"**. All particle motion freezes for a beat — stillness is the message. |
| 8 | He answers S — one door out | 9 s | Follow the resume thread down to the spine, then left to Egress | An "S" chip lights; a blue pulse rises from the spine slab (resume from checkpoint), runs Brief → Egress. The Egress panel is drawn as a single glowing doorway — the only opening in a solid wall. The message comet exits through it and off-frame. Green "sent" micro-chip (success beat #1). |
| 9 | Overnight digestion | 9 s | Drift right and down, lights dimmed to night | The moon-marked Consolidate panel wakes; five pills cascade — split → filter → dedupe → link → embed — and a stream of small note-cards flows into the markdown stack and the Qdrant cylinder, which glow soft green as they absorb (success beat #2). Caption: *"markdown is truth · Qdrant is the index"*. |
| 10 | The flywheel (closing shot) | 12 s | Long, slow pull-back from the Claude panel to the full board | "3 weeks later" title card. One small mention-card touches the board — and the entire history lights along a single closed blue loop circling all five zones, particles orbiting it continuously. Camera keeps pulling back until the loop reads as one glowing ring around the organism. Hold 3 s. GMS emblem resolves bottom-right. |

---

## Generation prompts

### Veo (video clips, one per scene)

Shared style block — prepend to every prompt:

> Cinematic 3D motion graphics, true black void background, floating dark glass UI panels with rounded corners and faint hairline edges, subtle depth-of-field, slow deliberate camera, single electric-blue glow accent (#00d4ff) with additive bloom, drifting micro-dust particles, premium fintech-keynote aesthetic, no text other than specified captions, 16:9, photorealistic render quality.

1. **Body plan:** "Slow push-in on a tilted board of five dark glass slabs at different elevations arranged like an organism — a small high slab at top labeled BRAIN, a tall central column NERVOUS SYSTEM, left column HANDS, right column MEMORY, one wide low slab at the base labeled SPINE. Panels idle, lit only by faint white edge glow and a dim grid floor far below."
2. **Mail arrives:** "A glowing blue comet streaks in from the left edge and lands on a dark glass panel with an envelope icon; on impact a thin blue filament drops down the board and ignites a long low slab at the base; a soft ripple of blue light crosses the slab. Caption fades in: 'checkpoint written'."
3. **Classify:** "Blue light particles travel along a thin tube from an envelope panel to a branching-node panel, then arc steeply upward into an elevated glass panel with a brain icon that blooms with blue light; a small chip reading 'Band 2' illuminates on a central glass display."
4. **Memory recall:** "Camera sweeps right as a long blue arc of particles crosses a dark board and enters a glass panel bearing a database-cylinder icon; a contact card and three small linked bars assemble themselves from light on a central display."
5. **Fail closed:** "Five glass chips labeled A B C D E; the middle one fills electric blue. Then a short tube of deep red light (#c05b4d) snaps on, connecting the panel to a shield-marked panel that pulses red — the only red in an otherwise blue-and-black frame. Caption: 'never guess'."
6. **Draft:** "Two thin blue filaments converge from above and from the right onto a glass panel with a pen icon; on a central glass display, lines of text draw themselves as glowing bars inside a letter layout; a chip reading 'Opus' glows blue."
7. **Nothing sends:** "A glowing document slides into a vertical queue on a glass panel and halts; every moving particle in the frame freezes; a single card flips up reading 'Send or hold? — S / H'; two seconds of total stillness."
8. **One door out:** "A chip reading 'S' lights; a pulse of blue rises from the wide base slab and travels through a queue panel to a panel rendered as a single glowing arched doorway in a solid dark wall; a comet of light exits through the doorway and off-frame right; a tiny sage-green 'sent' chip blinks once."
9. **Overnight digestion:** "Night scene, all panels dimmed; a crescent-moon panel wakes and five pill-shaped stages cascade downward — split, filter, dedupe, link, embed — as a stream of tiny note cards flows into a document stack and a database cylinder that absorb them with a soft sage-green glow."
10. **Flywheel finale:** "Long slow pull-back from a single glowing brain panel to reveal the entire five-zone board; a small card touches the board and a single continuous ring of electric-blue light ignites around all five zones, particles orbiting it endlessly; camera recedes until the ring reads as a halo around the whole machine; hold on the closed loop."

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

**Continuity rules:** one hero accent (blue) per frame; red appears in scene 5 only; green only on the two success beats; camera never flies backward — cuts snap; keep the GMS emblem watermark in the final 3 s of every cut-down.
