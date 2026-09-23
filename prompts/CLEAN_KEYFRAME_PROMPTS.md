# STAGE 3 — CLEAN Keyframe Generation Prompts

아래 코드 블록 전체를 하나의 배치 지시문으로 사용한다. 25개 이미지를 각각 독립된 파일로 생성하며, 중간 확인을 요청하지 않는다.

```text
Create the complete batch of 25 independent CLEAN keyframes described below.

OUTPUT REQUIREMENTS
- Generate exactly 25 separate images, one image per listed Scene ID / Keyframe ID.
- Do not make a collage, storyboard, contact sheet, diptych, triptych, split screen, or multi-panel composition.
- Use the exact sortable filename assigned to each image.
- Every image must be vertical 9:16, preferably 1080 × 1920 or higher.
- Photoreal cinematic 3D historical-engineering documentary style, not a painting, illustration, game screenshot, museum infographic, or fantasy scene.
- Keep generous foreground, midground, and background separation for a later restrained 5–15 degree camera move.
- Keep the principal subject inside the central safe area while preserving useful negative space for a later INFO editing pass.
- Finish all 25 images without stopping to ask for confirmation.

PROJECT-WIDE HISTORICAL CONTINUITY
- For ancient Egyptian evidence scenes, use a plausible New Kingdom Nile Valley environment unless a prompt explicitly identifies a later Greek context.
- Agricultural terrain: broad low alluvial floodplain, dark brown wet silt near water, dry ochre soil farther away, sparse reeds and date palms only where physically plausible, mudbrick rural structures kept distant and restrained.
- Egyptian workers and scribes: natural human proportions, sun-weathered skin, simple undyed off-white linen kilts or dresses appropriate to labor and status, bare feet or simple sandals where appropriate, no Hollywood royal costumes.
- Survey equipment: plant-fiber rope, plain wooden stakes, simple period-plausible implements. No metal tape measure, surveyor's transit, theodolite, optical level, compass, ruler with modern markings, or modern tripod.
- Scribal materials: period-plausible papyrus, wooden writing board or palette, reed pens, pigment containers. Never show legible writing in a CLEAN image; turn written surfaces away, keep them rolled, or place them outside readable focus.
- Do not place pyramids, colossal statues, temples, obelisks, pharaohs, or tomb treasures into ordinary field scenes merely as visual shorthand for Egypt.
- Do not depict an unverified annual post-flood boundary-restoration procedure. Flood-effect scenes and attested surveying scenes must remain visibly distinct examples, not before-and-after views of the same field.
- S01A through S08B share a believable Nile floodplain palette and weather continuity.
- S09A through S13A share restrained museum/documentary lighting and historically plausible reconstructed workspaces.
- S14A through S15C may introduce a later classical Greek material culture only where explicitly required, while visually preserving the chronological distinction from Egyptian evidence.

GLOBAL CLEAN PROHIBITIONS — APPLY TO EVERY IMAGE
- No text, letters, words, captions, subtitles, hieroglyphs, hieratic signs, Greek letters, numbers, dates, formulas, equations, labels, logos, signatures, or watermarks.
- No arrows, arrowheads, callout lines, leader lines, dimension lines, measuring ticks, diagrams, charts, maps, timelines, grids, UI, HUD, icons, badges, glowing overlays, infographic elements, or floating geometry.
- No split screen, framed inset, document reproduction panel, before-and-after layout, or multiple time periods in one composite image.
- No neon, magical glow, fantasy energy, steampunk devices, modern machinery, modern clothing, modern buildings, concrete embankments, electric lighting, plastic, printed paper, or glass museum display cases.
- No physically impossible water behavior, perfectly geometric flood edges, exaggerated disaster wave, giant sediment particles, impossible aerial height, duplicated people, malformed hands, extra limbs, or rope passing through bodies.
- No legible marks on papyrus, walls, tablets, palettes, stakes, ropes, fields, or props.

01 — Scene S01A / Keyframe KF-01A
Filename: 01_S01A_KF-01A_CLEAN_flood-submerges-field-marker.png
Purpose: immediate visual contradiction—moving water makes a low field marker difficult to see, without claiming a documented restoration procedure.
Scene: vertical overhead-oblique view of muddy Nile floodwater advancing across a low alluvial field; a small irregular earthen ridge and one plain weathered wooden marker are partly submerged, with their contours fading beneath turbid water; subtle suspended silt, physically plausible ripples and eddies around the marker.
Composition: foreground water entering from the lower edge, marker near the middle, still-visible dry field texture in the upper background; strong depth despite the high viewpoint.
Camera/lens: elevated 35 mm documentary lens feel, about 55 degrees downward, enough lateral depth for a short descending dolly.
Lighting/materials: early-morning warm sidelight, brown-gray turbid water, saturated dark silt, rough wood and crumbly earth.
Error prevention: the marker must look incidental and low, not like a modern property post; do not show surveyors, rope, reconstruction, geometric boundaries, or a matching before-state.

02 — Scene S02A / Keyframe KF-02A
Filename: 02_S02A_KF-02A_CLEAN_broad-inundated-floodplain.png
Purpose: reset from the provocative hook to an observational, evidence-oriented view of seasonal inundation.
Scene: broad Nile floodplain under shallow calm inundation, natural distributary channels and patches of emerging ground, distant vegetation and restrained mudbrick settlement silhouettes.
Composition: reflective water in foreground, alternating water and land bands in midground, hazy river valley depth in background; ample open sky and water.
Camera/lens: human-height wide 28 mm lens, slightly elevated riverbank viewpoint, designed for a slow pullback.
Lighting/materials: neutral clear morning, natural earth tones, no dramatic apocalypse atmosphere.
Error prevention: no people measuring, no field grid, no geometric water boundary, no monuments dominating the horizon.

03 — Scene S03A / Keyframe KF-03A
Filename: 03_S03A_KF-03A_CLEAN_water-and-silt-enter-low-field.png
Purpose: make the physical delivery of water and suspended sediment visible.
Scene: close landscape view where river water spreads through a natural low opening into a lower field basin; turbid flow is faster at the opening and broadens and slows across the field, with fine sediment visibly suspended in the water.
Composition: inlet in lower-left foreground, fan-shaped natural flow across midground, calmer shallow water and floodplain in background.
Camera/lens: low 32 mm lens just above the water, three-quarter view with clear foreground-to-background flow depth.
Lighting/materials: soft lateral sunlight revealing ripples, wet silt sheen, realistic brown suspended sediment.
Error prevention: no engineered modern sluice, no arrows or colored streamlines, no oversized particles, no perfect fan geometry.

04 — Scene S04A / Keyframe KF-04A
Filename: 04_S04A_KF-04A_CLEAN_natural-high-water-traces.png
Purpose: show that flood reach and level can vary without adding a diagram.
Scene: eroded earthen riverbank with several naturally visible horizontal moisture and silt traces at different heights; current water below the highest trace; sparse reeds rooted at plausible elevations.
Composition: textured bank occupies one side, water channel recedes diagonally, floodplain stretches behind it.
Camera/lens: 50 mm documentary lens at bank level, oblique angle suitable for a gentle upward tilt.
Lighting/materials: late-afternoon raking light emphasizes real sediment layers and dampness.
Error prevention: traces must be organic and irregular, never colored, labeled, numbered, or drawn like measurement lines; no nilometer architecture unless historically verified for a specific site.

05 — Scene S05A / Keyframe KF-05A
Filename: 05_S05A_KF-05A_CLEAN_low-flood-dry-outer-field.png
Purpose: show the agricultural constraint of insufficient water reach.
Scene: reduced river edge and shallow isolated wet patch, with broad dry outer field showing cracked, dusty soil and sparse stressed vegetation; one or two distant farmers observing rather than theatrically despairing.
Composition: dry cracked foreground leads toward limited water in midground and river vegetation in background.
Camera/lens: 35 mm lens at chest height, lateral depth for a slow move toward the dry field.
Lighting/materials: hard warm daylight, matte pale dust contrasting with darker damp soil near water.
Error prevention: no modern drought infrastructure, dead livestock, sensational famine imagery, or text scratched into soil.

06 — Scene S05B / Keyframe KF-05B
Filename: 06_S05B_KF-05B_CLEAN_excess-water-over-cultivated-ground.png
Purpose: show the opposite constraint—excess inundation over cultivated ground.
Scene: shallow but extensive muddy water covering low cultivated soil and the lower stems of field vegetation; a simple elevated footpath remains barely above water in the distance.
Composition: rippling water foreground, partially submerged plants midground, higher dry edge and distant trees behind.
Camera/lens: low 35 mm lens near water level, forward visual path for a restrained dolly.
Lighting/materials: overcast-bright sky, physically accurate reflections, soaked vegetation and dark mud.
Error prevention: no catastrophic wall of water, houses collapsing, boats in fields, modern levees, or perfect rectangular inundation.

07 — Scene S06A / Keyframe KF-06A
Filename: 07_S06A_KF-06A_CLEAN_silt-alters-ground-marker.png
Purpose: show deposition and minor surface alteration without depicting a proven boundary-restoration workflow.
Scene: receding shallow water leaves fresh, uneven silt around a small weathered wooden or earthen marker; one side is partly buried while nearby soil shows tiny erosion channels.
Composition: extreme textured foreground of wet silt, marker in midground, retreating water and floodplain softly behind.
Camera/lens: low macro-documentary 55 mm lens, shallow but sufficient depth for a short tracking move.
Lighting/materials: soft morning light, glossy wet silt transitioning to matte drying mud.
Error prevention: no ropes, measuring team, replacement stake, straight boundary, before-and-after comparison, or implication that this exact marker is being restored.

08 — Scene S07A / Keyframe KF-07A
Filename: 08_S07A_KF-07A_CLEAN_farming-resumes-on-damp-silt.png
Purpose: transition from floodwater to the recurring agricultural cycle.
Scene: water has withdrawn from a broad field; farmers in simple linen work garments prepare dark damp alluvial soil with period-plausible hand tools and a wooden plough team in the farther midground.
Composition: moist soil foreground with footprints, active preparation midground, residual water and vegetation in background.
Camera/lens: 40 mm lens at low human height, diagonal work line supporting a gentle dolly toward the farmers.
Lighting/materials: clean morning light, realistic wood, linen, animal hide and dark soil.
Error prevention: no modern plough, steel blade, tractor, perfect field grid, royal costume, or monumental skyline.

09 — Scene S08A / Keyframe KF-08A
Filename: 09_S08A_KF-08A_CLEAN_harvest-and-scribe-observation.png
Purpose: place agricultural production and administrative observation in the same social environment without claiming a specific tax event.
Scene: workers gather grain in a mature field while, at a respectful distance, a seated or crouching scribe uses a wooden palette and papyrus roll angled away from camera.
Composition: grain bundles in foreground, workers midground, scribe on one side with landscape depth behind.
Camera/lens: 45 mm lens, three-quarter view allowing a later pan from harvest to scribe.
Lighting/materials: dry golden harvest light, undyed linen, natural papyrus and wood.
Error prevention: no readable marks, coins, scales, guards, coercive tax scene, royal insignia, or infographic linkage.

10 — Scene S08B / Keyframe KF-08B
Filename: 10_S08B_KF-08B_CLEAN_varied-field-parcels-landscape.png
Purpose: visually pose the practical questions of location, extent, and record through real terrain.
Scene: elevated oblique view of several cultivated areas with naturally varied outlines defined by paths, irrigation earthworks, vegetation changes and terrain—not by perfect modern parcel lines.
Composition: near field corner in foreground, three distinguishable agricultural areas across midground, river and settlement far behind.
Camera/lens: elevated 35 mm lens, not a satellite or map view; enough oblique depth for a short arc move.
Lighting/materials: late-afternoon side light clarifies terrain relief and crop texture.
Error prevention: no cadastral grid, glowing outlines, aerial labels, exact rectangles, modern canals, or map styling.

11 — Scene S09A / Keyframe KF-09A
Filename: 11_S09A_KF-09A_CLEAN_tomb-art-survey-evidence-context.png
Purpose: introduce visual evidence for surveying as a distinct documented context.
Scene: intimate documentary reconstruction of an ancient Egyptian tomb wall section inspired by New Kingdom agricultural registers; the visible register contains human figures handling a long rope in a field context, while any hieroglyphic bands are entirely outside the crop.
Composition: wall surface fills most of frame but remains oblique with a dark architectural edge in foreground and chamber depth behind.
Camera/lens: 50 mm lens, oblique museum-documentary viewpoint for a restrained push-in.
Lighting/materials: warm grazing lamplike conservation lighting, aged plaster, mineral pigments, visible surface wear.
Error prevention: no legible glyphs, captions, glass display case, modern visitors, invented bright colors, animated figures, or claim that the image shows post-flood restoration.

12 — Scene S09B / Keyframe KF-09B
Filename: 12_S09B_KF-09B_CLEAN_rope-field-measurement-reconstruction.png
Purpose: reconstruct the attested action of people stretching a rope to measure a field, separate from flood scenes.
Scene: dry cultivated field under normal conditions; two Egyptian workers hold a long plant-fiber rope taut close to the ground while a third observes; no floodwater, damaged marker, or active boundary restoration.
Composition: rope runs diagonally from foreground hands to midground worker, crops and rural landscape behind.
Camera/lens: 40 mm lens at waist height, lateral depth parallel to the rope for later tracking.
Lighting/materials: clear warm daylight, fibrous rope detail, simple linen clothing, dry compacted soil.
Error prevention: rope has no knots, numbers, colored marks, or measuring ticks visible; no right-angle demonstration, geometric outline, modern tools, or ceremonial rope-stretching scene.

13 — Scene S10A / Keyframe KF-10A
Filename: 13_S10A_KF-10A_CLEAN_rope-and-wooden-stake-detail.png
Purpose: show period-plausible surveying materials as a separate close observational detail.
Scene: close-up of a worker's hands maintaining tension on plain plant-fiber rope beside a simple wooden stake set in dry ground; another worker is softly visible farther along the rope.
Composition: stake and hands in foreground, taut rope receding through midground, dry field background.
Camera/lens: 65 mm close documentary lens, shallow focus with enough depth along the rope for a rack-focus move.
Lighting/materials: directional natural light, rough wood grain, twisted fiber, dusty skin and soil.
Error prevention: no floodwater, boundary restoration action, knot scale, calibrated marks, mallet strike, right-angle claim, metal hardware, text, or symbols.

14 — Scene S11A / Keyframe KF-11A
Filename: 14_S11A_KF-11A_CLEAN_wilbour-papyrus-object-context.png
Purpose: introduce the Wilbour Papyrus as a physical administrative document without exposing text in CLEAN.
Scene: long ancient papyrus roll resting on a dark matte conservation support in a quiet archival setting; show the fibrous blank reverse surface and layered rolled ends, with the written face turned downward and invisible.
Composition: near rolled end in foreground, long papyrus body receding diagonally, soft dark background.
Camera/lens: 55 mm museum-object lens, low oblique viewpoint suitable for slow lateral travel.
Lighting/materials: restrained warm conservation light, brittle tan fibers, worn edges, no glossy modern display.
Error prevention: absolutely no visible ink, hieratic signs, accession number, placard, label, ruler, color target, glass case, museum logo, or modern hand.

15 — Scene S11B / Keyframe KF-11B
Filename: 15_S11B_KF-11B_CLEAN_land-recording-workspace.png
Purpose: evoke the kinds of land information preserved in an administrative document without making a diagram or asserting a specific use for a value.
Scene: New Kingdom scribal workspace overlooking multiple agricultural plots; a scribe handles a partly rolled papyrus with its writing surface facing away while an assistant holds a plain wooden palette.
Composition: papyrus and hands foreground, scribes midground, varied fields visible through an open shaded workspace in background.
Camera/lens: 40 mm lens over the side of the work surface, deep enough for a gentle move toward the fields.
Lighting/materials: shaded interior foreground, sunlit earth-toned landscape beyond, natural papyrus fibers and wood.
Error prevention: no readable document, numbers, parcel outlines, counting tokens, coin payment, tax collection performance, or modern furniture.

16 — Scene S11C / Keyframe KF-11C
Filename: 16_S11C_KF-11C_CLEAN_scribe-and-distant-survey-context.png
Purpose: place surveying, calculation, and land administration in related social space without drawing a direct causal arrow.
Scene: one continuous deep rural scene: a scribe works under a simple shade canopy in the foreground; far in the background, separate workers hold a rope on dry agricultural ground; neither group is acting out a post-flood restoration.
Composition: scribe and rolled papyrus foreground, open field midground, small surveying group background; strong occlusion and depth planes.
Camera/lens: 50 mm lens with focus on the scribe but recognizable background activity, suited to a later focus pull.
Lighting/materials: midday exterior with soft canopy shade, subdued linen and wood colors.
Error prevention: no split screen, connecting line, gesture passing measurements between groups, readable marks, floodwater, ruined marker, tax exchange, or forced one-to-one causation.

17 — Scene S12A / Keyframe KF-12A
Filename: 17_S12A_KF-12A_CLEAN_rhind-papyrus-object-context.png
Purpose: introduce the Rhind Mathematical Papyrus as a distinct physical mathematical source without text in CLEAN.
Scene: ancient papyrus roll on a neutral dark support, showing only its uninscribed fibrous reverse and uneven ancient edges; several joined sheets are apparent from fiber seams, but the written side is hidden.
Composition: diagonal length across the vertical frame with a rolled end near foreground and layered support depth behind.
Camera/lens: 60 mm object-documentary lens, raking oblique view for a slow push-in.
Lighting/materials: soft warm conservation light reveals fiber direction and age without theatrical gold glow.
Error prevention: no visible ink, hieratic characters, numbers, formulas, accession marks, labels, scale bars, glass, or modern museum fixtures.

18 — Scene S12B / Keyframe KF-12B
Filename: 18_S12B_KF-12B_CLEAN_varied-field-shapes-oblique-view.png
Purpose: show that practical area problems can concern differently shaped fields, without overlaying geometry.
Scene: high but oblique landscape view of three naturally bounded cultivated areas: one broadly rectangular, one tapering triangular-like, one rounded by a river bend; boundaries arise from paths, banks and terrain.
Composition: closest field at lower edge, other two staggered in depth, river curve and vegetation in background.
Camera/lens: elevated 35 mm lens, strong perspective rather than map projection, designed for a restrained sideways move.
Lighting/materials: clean late-morning light, distinct crop and soil textures, plausible irregular edges.
Error prevention: no perfect Euclidean shapes, outline strokes, formulas, grid, labels, numerals, top-down map, or modern monoculture machinery.

19 — Scene S13A / Keyframe KF-13A
Filename: 19_S13A_KF-13A_CLEAN_practical-measurement-calculation-workspace.png
Purpose: connect physical measurement and scribal calculation as practical work while keeping the image free of explanatory graphics.
Scene: close historical workspace at the edge of a dry field; plain rope and wooden stake lie to one side, while a scribe prepares pigment with a reed pen over a papyrus whose surface is turned away from camera.
Composition: rope coils foreground, scribe's hands and tools midground, measured field activity softly visible background.
Camera/lens: 45 mm lens from low side angle, layered for a dolly from rope toward the writing tools.
Lighting/materials: natural shaded daylight, rough fiber rope, matte wood, linen and papyrus.
Error prevention: no visible calculation, writing, geometric diagram, abacus, modern ruler, claim of formal proof, flood aftermath, or literal data-transfer gesture.

20 — Scene S14A / Keyframe KF-14A
Filename: 20_S14A_KF-14A_CLEAN_later-greek-author-context.png
Purpose: mark a clear chronological transition to a later Greek author's account.
Scene: restrained fifth-century-BCE Greek writing environment; an adult male author in historically plausible simple draped wool clothing sits with a blank-facing papyrus roll, Egyptian landscape absent, architecture modest and period-plausible.
Composition: papyrus roll foreground, author midground in profile, stone or plaster interior depth behind.
Camera/lens: 50 mm portrait-documentary lens, three-quarter side view for a gentle lateral move.
Lighting/materials: cool natural window light on wool, papyrus and stone, distinct from the warmer Egyptian palette.
Error prevention: no readable Greek, no modern bound book, quill pen, laurel-crowned philosopher cliché, marble palace, portrait-name label, Egyptian costume, or anachronistic Roman props.

21 — Scene S14B / Keyframe KF-14B
Filename: 21_S14B_KF-14B_CLEAN_herodotean-account-symbolic-land-loss.png
Purpose: visually stage the content attributed to Herodotus as a clearly separate symbolic reconstruction, not direct Egyptian evidence.
Scene: natural riverbank has eroded into a cultivated plot; two period-plausible figures examine the reduced dry land while a third holds plain rope loosely; no active tax transaction and no claim that this exact scene is documented.
Composition: eroded bank foreground, figures and remaining plot midground, river receding behind.
Camera/lens: 40 mm lens at shoulder height, diagonal river edge supports a modest orbit.
Lighting/materials: neutral daylight and natural erosion textures; slightly desaturated to distinguish the narrated account from evidence scenes.
Error prevention: no coins, tax collector, ledger text, king, explicit boundary-restoration procedure, measurement marks, geometric overlay, or mixed Greek/Egyptian costume spectacle.

22 — Scene S14C / Keyframe KF-14C
Filename: 22_S14C_KF-14C_CLEAN_rope-lines-suggest-geometry.png
Purpose: create a visual metaphor for the famous origin story without asserting it as fact.
Scene: several plain plant-fiber ropes lie naturally on dry earth after practical handling, their intersections incidentally suggesting simple angular and curved relationships; human hands have just released them and remain at frame edge.
Composition: close foreground rope intersections, hands midground edge, blurred open field behind; one continuous real scene.
Camera/lens: 50 mm lens at low oblique angle, designed for a slight rising move.
Lighting/materials: raking warm light, realistic rope fibers and granular soil.
Error prevention: no perfect luminous triangle or circle, no drawn geometry, protractor, compass, formula, Greek letter, supernatural transformation, floodwater, or definitive invention tableau.

23 — Scene S15A / Keyframe KF-15A
Filename: 23_S15A_KF-15A_CLEAN_two-era-material-evidence-depth.png
Purpose: establish chronological distance between earlier Egyptian mathematics and the later written Greek account without a timeline graphic.
Scene: a single archival study space with an ancient Egyptian papyrus roll in sharp foreground and a materially distinct later Greek-style papyrus roll far behind on a separate support; both show only blank reverse surfaces.
Composition: large foreground Egyptian roll, long empty depth, smaller later roll in background, physical separation doing the storytelling.
Camera/lens: 65 mm lens with compressed but visible depth, positioned for a slow pullback.
Lighting/materials: warm light on foreground object, cooler softer light on background object, dark neutral surroundings.
Error prevention: no split screen, dates, labels, timeline, arrows, readable writing, glass cases, accession numbers, or implication that both documents were found together.

24 — Scene S15B / Keyframe KF-15B
Filename: 24_S15B_KF-15B_CLEAN_confirmed-evidence-tableau.png
Purpose: gather the confirmed categories—flood agriculture, land administration, surveying and practical mathematics—without converting them into a single causal diagram.
Scene: one coherent deep Egyptian riverside workspace: residual floodplain water and cultivated land in background, separate rope-measuring workers in far midground on dry soil, a scribe with rolled blank-facing papyrus under shade in foreground.
Composition: scribe foreground left, open neutral center, survey workers midground right, water and fields background; all elements share one realistic environment but retain spatial separation.
Camera/lens: 35 mm lens at human height with strong depth for a short arc across the evidence categories.
Lighting/materials: balanced late-afternoon daylight, consistent linen, wood, fiber, water and alluvial soil.
Error prevention: no arrows, connecting paths, split panels, repeated characters, simultaneous flood restoration, readable writing, geometric shapes, giant monuments, or claim that one activity caused another.

25 — Scene S15C / Keyframe KF-15C
Filename: 25_S15C_KF-15C_CLEAN_river-and-unconnected-rope-form.png
Purpose: conclude visually that the Nile and practical geometry should not be joined by an asserted single causal mechanism.
Scene: contemplative real landscape with Nile water in the deep background and, in the dry foreground, a loose plant-fiber rope beside scribal tools; a clear natural gap of untouched earth separates rope and water, while people have left the frame.
Composition: rope and tools low foreground, broad empty-earth middle distance, river and floodplain background; central negative space reserved for later conclusion graphics.
Camera/lens: 45 mm lens from low human height, layered depth for a slow push toward the empty separation.
Lighting/materials: quiet dusk light, restrained bronze-blue sky reflection, tactile rope, wood, papyrus back and dry soil.
Error prevention: do not form the rope into a perfect symbol, broken arrow, X, question mark, letters or geometric theorem; no visible text, no dramatic rupture, no flood-restoration scene, and no fantasy glow.
```

## 승인 게이트

이 문서는 CLEAN 이미지 생성을 위한 프롬프트만 정의한다. 아직 이미지를 생성하지 않았으며, 사용자 승인 전에는 CLEAN 자산 생성·검토나 INFO/VIDEO 프롬프트 단계로 진행하지 않는다.
