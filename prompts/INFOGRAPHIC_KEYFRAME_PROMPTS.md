# STAGE 5 — INFO Second-Pass Editing Prompts

아래 코드 블록 전체를 하나의 배치 지시문으로 사용한다. 승인된 CLEAN 25개를 각각 같은 ID의 INFO 이미지로 편집하며, 새로운 장면을 생성하지 않는다.

```text
Convert the 25 user-approved CLEAN keyframes into 25 matching INFO keyframes by editing each specified CLEAN file in place conceptually and saving a separate INFO copy.

ASSET MAPPING AND OUTPUT
- Use only the 25 approved CLEAN files listed below. Ignore all four EXTRA images.
- Every CLEAN source maps 1:1 to the INFO output with the same Scene ID and Keyframe ID.
- Generate exactly 25 separate vertical 9:16 INFO images, never a collage, storyboard, contact sheet, or split screen.
- Do not overwrite, crop, rename, or modify the original CLEAN files.
- Use each exact INFO output filename specified below.
- Complete all 25 edits without stopping for confirmation between images.

GLOBAL BASE-IMAGE PRESERVATION — MANDATORY
- The matching CLEAN image is the immutable base plate. Preserve its camera, crop, aspect ratio, lens perspective, horizon, geometry, terrain, water, people, poses, hands, clothing, tools, rope, stakes, papyrus, plants, architecture, lighting, shadows, color, materials, textures, atmosphere, background, and physical state.
- Do not redraw, regenerate, replace, rotate, mirror, reframe, zoom, enlarge, shrink, reposition, beautify, erase, duplicate, or morph any base-scene element.
- Do not turn the INFO pass into a new illustration. Add only the restrained engineering-information layer requested for that ID.
- Do not introduce a person, object, monument, device, document, border, panel, or historical detail that is absent from CLEAN.
- Keep all graphics anchored to actual locations or physical phenomena in the CLEAN image. Respect perspective, parallax, depth, surface orientation, occlusion, and the frame safe area.
- A line passing behind a person, rope, stake, crop, bank, or foreground object must be correctly occluded. Never draw through a body or solid object.

PROJECT-WIDE INFO DESIGN SYSTEM
- Restrained model-rendered engineering-documentary overlays integrated into real 3D space, never a flat HUD.
- Normal water flow and transport: muted cyan/teal.
- Excess water, erosion risk, or warning condition: restrained orange-red.
- Soil, land extent, survey structure, and documentary evidence: warm gold or neutral blue-white.
- Source qualification, uncertainty, later account, or non-causal relationship: desaturated violet-gray or neutral white with a dashed line.
- Use thin lines, small anchors, modest arrowheads, soft low-intensity edge light, and subtle transparent surface tint only where requested.
- Korean labels only. Normally use 1–3 short labels and no sentence-length heading. Use no unverified measurement, invented unit, fake precision, or decorative formula.
- Use one small sans-serif Korean type family consistently. Keep text horizontal and readable; do not imitate hieroglyphs or write directly onto ancient artifacts.
- Keep labels away from faces, hands, tools, documentary objects, and the primary physical phenomenon.
- The main subject must remain the real water, soil, land, rope, document, or human action—not the overlay.

GRAPHIC CONSTRUCTION READINESS
- Organize every overlay as separable elements for later animation in this order: anchor → line/path → arrow body → arrowhead → value if any → short label → moving pulse cue.
- Do not bake a giant title, subtitle block, legend panel, full-screen tint, map frame, chart, or timeline board into any INFO image.
- Do not add logos, watermarks, UI, HUD, neon, fantasy energy, or unrelated decoration.

01 — Scene S01A / Keyframe KF-01A
CLEAN source: 01_S01A_KF-01A_CLEAN_flood-submerges-field-marker.png
INFO output: 01_S01A_KF-01A_INFO_flood-submerges-field-marker.png
Overlay purpose: show that turbid water is obscuring a low physical marker, without claiming a documented restoration procedure.
Add: one small gold anchor exactly on the visible top of the low marker; a thin neutral leader to the short label “흐려진 지표”; two restrained teal flow traces that follow the real water around the marker and end downstream.
Depth/occlusion: water flow traces must conform to the water surface and disappear behind the marker where physically required.
Do not add: geometry, parcel boundary, surveyor, rope, before/after inset, restoration arrow, or the claim that this is an attested annual practice.

02 — Scene S02A / Keyframe KF-02A
CLEAN source: 02_S02A_KF-02A_CLEAN_broad-inundated-floodplain.png
INFO output: 02_S02A_KF-02A_INFO_broad-inundated-floodplain.png
Overlay purpose: identify seasonal water spread as the confirmed physical setting.
Add: two thin teal paths following actual shallow channels; small labels “범람수” near water and “범람원” anchored to exposed low land.
Depth/occlusion: paths remain on the water plane and recede with perspective; labels stay clear of the horizon.
Do not add: cadastral boundary, fixed flood outline, modern map, annual restoration claim, or monument label.

03 — Scene S03A / Keyframe KF-03A
CLEAN source: 03_S03A_KF-03A_CLEAN_water-and-silt-enter-low-field.png
INFO output: 03_S03A_KF-03A_INFO_water-and-silt-enter-low-field.png
Overlay purpose: visualize water spreading, slowing, and carrying fine sediment.
Add: teal flow arrows beginning at the real inlet and widening downstream; sparse gold-brown particle dots following the visible current; small labels “유입”, “유속 감소”, “부유 토사”.
Depth/occlusion: arrows hug the water surface and narrow with depth; particle dots are partially hidden by ripples and banks.
Do not add: engineered sluice, numerical velocity, oversized sediment, or perfectly symmetric fan.

04 — Scene S04A / Keyframe KF-04A
CLEAN source: 04_S04A_KF-04A_CLEAN_natural-high-water-traces.png
INFO output: 04_S04A_KF-04A_INFO_natural-high-water-traces.png
Overlay purpose: distinguish naturally visible traces of different water reach without inventing measured values.
Add: three short thin blue-white brackets aligned only to the existing irregular moisture/silt traces; labels “낮은 흔적”, “중간 흔적”, “높은 흔적”.
Depth/occlusion: brackets conform to the bank plane and stop where the trace disappears.
Do not add: numbers, scale, exact annual dates, nilometer, full-width straight levels, or chart axes.

05 — Scene S05A / Keyframe KF-05A
CLEAN source: 05_S05A_KF-05A_CLEAN_low-flood-dry-outer-field.png
INFO output: 05_S05A_KF-05A_INFO_low-flood-dry-outer-field.png
Overlay purpose: show the agricultural constraint when water does not reach the outer field.
Add: muted teal tint along the actual wet limit; a restrained dashed neutral line across the natural transition; labels “도달한 물” and “건조한 바깥 밭”.
Depth/occlusion: transition line follows terrain perspective and disappears behind vegetation.
Do not add: drought percentage, crop-loss number, modern irrigation proposal, or disaster icon.

06 — Scene S05B / Keyframe KF-05B
CLEAN source: 06_S05B_KF-05B_CLEAN_excess-water-over-cultivated-ground.png
INFO output: 06_S05B_KF-05B_INFO_excess-water-over-cultivated-ground.png
Overlay purpose: identify excess inundation over cultivated ground.
Add: a thin orange-red contour following the real water edge; two small vertical depth cues anchored from soil surface to water surface with no numbers; labels “침수 범위” and “경작지”.
Depth/occlusion: contour remains attached to the visible shoreline and passes behind plants.
Do not add: giant hazard symbol, catastrophic wave, numerical depth, or modern levee graphic.

07 — Scene S06A / Keyframe KF-06A
CLEAN source: 07_S06A_KF-06A_CLEAN_silt-alters-ground-marker.png
INFO output: 07_S06A_KF-06A_INFO_silt-alters-ground-marker.png
Overlay purpose: distinguish local deposition and erosion around a partly buried marker.
Add: one gold anchor on the visible marker top; small brown-gold stipple over the actual fresh deposit labeled “퇴적”; one restrained orange trace following an existing tiny erosion channel labeled “침식”.
Depth/occlusion: stipple conforms to ground relief; traces stop at occluding mud clumps.
Do not add: reconstructed boundary, replacement stake, rope, survey team, before/after comparison, or annual-restoration statement.

08 — Scene S07A / Keyframe KF-07A
CLEAN source: 08_S07A_KF-07A_CLEAN_farming-resumes-on-damp-silt.png
INFO output: 08_S07A_KF-07A_INFO_farming-resumes-on-damp-silt.png
Overlay purpose: show the transition from residual water to workable moist soil.
Add: thin teal-to-gold gradient path following the real ground transition; labels “잔류 수분”, “젖은 충적토”, “경작 재개”.
Depth/occlusion: ground path passes behind farmers, animals, and tools; never covers hands or faces.
Do not add: calendar date, modern crop icon, production figure, or idealized field grid.

09 — Scene S08A / Keyframe KF-08A
CLEAN source: 09_S08A_KF-08A_CLEAN_harvest-and-scribe-observation.png
INFO output: 09_S08A_KF-08A_INFO_harvest-and-scribe-observation.png
Overlay purpose: identify harvest activity and separate administrative observation without asserting a specific tax event.
Add: small gold anchors on a grain bundle and the scribe’s palette; neutral leader labels “수확” and “기록”.
Depth/occlusion: leaders occupy open space and never cross bodies or the papyrus.
Do not add: tax label, payment arrow, coin, numerical yield, readable writing, or causal arrow between workers and scribe.

10 — Scene S08B / Keyframe KF-08B
CLEAN source: 10_S08B_KF-08B_CLEAN_varied-field-parcels-landscape.png
INFO output: 10_S08B_KF-08B_INFO_varied-field-parcels-landscape.png
Overlay purpose: point out practical questions of location, extent, and record across varied terrain.
Add: three small gold anchors on three real agricultural areas; short labels “위치”, “넓이”, “기록”; only short local leader segments, not complete parcel outlines.
Depth/occlusion: anchors sit on terrain and scale with distance.
Do not add: cadastral map, full boundary polygons, coordinate grid, dimensions, or perfect rectangles.

11 — Scene S09A / Keyframe KF-09A
CLEAN source: 11_S09A_KF-09A_CLEAN_tomb-art-survey-evidence-context.png
INFO output: 11_S09A_KF-09A_INFO_tomb-art-survey-evidence-context.png
Overlay purpose: identify the wall image as evidence for a surveying scene while preserving the artifact.
Add: one small blue-white corner bracket outside the painted register; label “밭 측량 도상”; two tiny anchors beside, not on top of, the rope-holding figures.
Depth/occlusion: bracket follows the oblique wall plane; overlay stays off pigment and damaged plaster where possible.
Do not add: translated hieroglyphs, invented tomb text, flood-restoration label, modern museum placard, or bright outline around figures.

12 — Scene S09B / Keyframe KF-09B
CLEAN source: 12_S09B_KF-09B_CLEAN_rope-field-measurement-reconstruction.png
INFO output: 12_S09B_KF-09B_INFO_rope-field-measurement-reconstruction.png
Overlay purpose: show the measured span and rope tension in an attested surveying reconstruction.
Add: a thin gold line precisely coincident with the existing rope, anchored only at the two held ends; subtle outward tension cues; labels “측량줄” and “측정 구간”.
Depth/occlusion: the gold line must disappear wherever hands or bodies occlude the rope.
Do not add: length value, right-angle symbol, knot scale, boundary polygon, floodwater, or post-flood restoration claim.

13 — Scene S10A / Keyframe KF-10A
CLEAN source: 13_S10A_KF-10A_CLEAN_rope-and-wooden-stake-detail.png
INFO output: 13_S10A_KF-10A_INFO_rope-and-wooden-stake-detail.png
Overlay purpose: explain rope tension and the physical anchor point.
Add: one gold anchor at the real rope–stake contact; one thin gold tension path following the rope; labels “고정점” and “장력”.
Depth/occlusion: line remains exactly on the rope and behind the worker’s fingers where occluded.
Do not add: calibration marks, distance value, right angle, metal fitting, flood context, or replacement-stake action.

14 — Scene S11A / Keyframe KF-11A
CLEAN source: 14_S11A_KF-11A_CLEAN_wilbour-papyrus-object-context.png
INFO output: 14_S11A_KF-11A_INFO_wilbour-papyrus-object-context.png
Overlay purpose: identify the object and its documentary category without altering or fabricating its text.
Add: a small neutral leader anchored to the outer edge of the papyrus support, not the artifact surface; labels “윌버 파피루스” and “토지 행정 기록”.
Depth/occlusion: leader terminates beside the object and respects the support plane.
Do not add: simulated hieratic writing, translation, land numbers, accession number, scale, document reconstruction, or tax-causation arrow.

15 — Scene S11B / Keyframe KF-11B
CLEAN source: 15_S11B_KF-11B_CLEAN_land-recording-workspace.png
INFO output: 15_S11B_KF-11B_INFO_land-recording-workspace.png
Overlay purpose: show the categories of information associated with land administration, not a specific value transfer.
Add: small anchors near the distant field, rolled papyrus, and scribe’s workspace; labels “토지 크기”, “보유·관리”, “행정 기록”.
Depth/occlusion: leaders remain separate and do not connect into a causal chain; never cover papyrus or hands.
Do not add: readable entries, tax amount, parcel polygon, modern ledger, or direct measurement-to-tax arrow.

16 — Scene S11C / Keyframe KF-11C
CLEAN source: 16_S11C_KF-11C_CLEAN_scribe-and-distant-survey-context.png
INFO output: 16_S11C_KF-11C_INFO_scribe-and-distant-survey-context.png
Overlay purpose: show a restrained relationship between surveying/calculation and land administration without asserting a one-way cause.
Add: one anchor near the distant rope activity labeled “측량·계산”; one anchor near the scribe labeled “토지 행정”; a thin desaturated dashed bidirectional relation curve through open space.
Depth/occlusion: curve passes behind midground terrain and never intersects people or tools.
Do not add: solid causal arrow, data-transfer animation, floodwater, restoration workflow, or sentence-length conclusion.

17 — Scene S12A / Keyframe KF-12A
CLEAN source: 17_S12A_KF-12A_CLEAN_rhind-papyrus-object-context.png
INFO output: 17_S12A_KF-12A_INFO_rhind-papyrus-object-context.png
Overlay purpose: identify the Rhind Mathematical Papyrus without fabricating its written surface.
Add: a small neutral leader anchored to the support beside the papyrus; labels “린드 수학 파피루스” and “실용 계산 문제”.
Depth/occlusion: label floats in safe negative space and the line stops before touching the artifact.
Do not add: hieratic text, equation, copied problem, modern geometry symbols, accession number, or fake numeric example.

18 — Scene S12B / Keyframe KF-12B
CLEAN source: 18_S12B_KF-12B_CLEAN_varied-field-shapes-oblique-view.png
INFO output: 18_S12B_KF-12B_INFO_varied-field-shapes-oblique-view.png
Overlay purpose: identify approximate field forms relevant to area calculation while preserving their irregularity.
Add: three short gold edge traces following limited portions of the real terrain boundaries; labels “직사각형에 가까운 밭”, “삼각형에 가까운 밭”, “곡선형 밭”.
Depth/occlusion: edge traces follow surface perspective, break behind vegetation, and never close into perfect polygons.
Do not add: formula, area value, complete outline, Cartesian grid, compass, or exact Euclidean shape.

19 — Scene S13A / Keyframe KF-13A
CLEAN source: 19_S13A_KF-13A_CLEAN_practical-measurement-calculation-workspace.png
INFO output: 19_S13A_KF-13A_INFO_practical-measurement-calculation-workspace.png
Overlay purpose: show the practical workflow from physical measurement to area calculation.
Add: one gold anchor near the existing rope labeled “길이 측정”; one near the writing tools labeled “면적 계산”; a restrained neutral directional path through open workspace.
Depth/occlusion: path remains behind foreground tools and avoids papyrus surface and hands.
Do not add: invented calculation, formula, modern proof notation, exact measurement, abacus, or claim that flood alone caused the method.

20 — Scene S14A / Keyframe KF-14A
CLEAN source: 20_S14A_KF-14A_CLEAN_later-greek-author-context.png
INFO output: 20_S14A_KF-14A_INFO_later-greek-author-context.png
Overlay purpose: mark a chronological and evidentiary shift to Herodotus’s later written account.
Add: small desaturated violet-gray labels “헤로도토스” and “후대의 기록”; one subtle source bracket beside the blank-facing papyrus.
Depth/occlusion: bracket respects the papyrus plane without writing on it; labels avoid the author’s face and hands.
Do not add: quotation text, Greek script, modern book title, Egyptian imagery, giant portrait label, or claim of eyewitness evidence.

21 — Scene S14B / Keyframe KF-14B
CLEAN source: 21_S14B_KF-14B_CLEAN_herodotean-account-symbolic-land-loss.png
INFO output: 21_S14B_KF-14B_INFO_herodotean-account-symbolic-land-loss.png
Overlay purpose: identify elements inside the account attributed to Herodotus while clearly framing them as a reported explanation.
Add: a small violet-gray corner tag “헤로도토스의 설명”; restrained anchors labeled “줄어든 토지” and “재측정”; one short dashed relation line.
Depth/occlusion: anchors attach to the real eroded edge and visible rope activity; dashed line stays in open ground.
Do not add: coin, tax number, king, definitive historical stamp, flood-restoration sequence, or unqualified causal arrow.

22 — Scene S14C / Keyframe KF-14C
CLEAN source: 22_S14C_KF-14C_CLEAN_rope-lines-suggest-geometry.png
INFO output: 22_S14C_KF-14C_INFO_rope-lines-suggest-geometry.png
Overlay purpose: present the famous origin claim as a question, not a confirmed invention event.
Add: thin desaturated dashed traces following only two existing rope segments; a small label “기하학의 기원?” placed in negative space; one source cue “후대 설명”.
Depth/occlusion: traces remain on the rope and disappear beneath hands or soil overlap.
Do not add: perfect triangle, circle, proof, formula, magical transformation, large headline, or confirmed-causation arrow.

23 — Scene S15A / Keyframe KF-15A
CLEAN source: 23_S15A_KF-15A_CLEAN_two-era-material-evidence-depth.png
INFO output: 23_S15A_KF-15A_INFO_two-era-material-evidence-depth.png
Overlay purpose: make the chronological distance between earlier Egyptian mathematics and the later Greek account readable.
Add: a warm-gold anchor beside the foreground roll labeled “이집트 수학 자료”; a cool violet-gray anchor beside the distant roll labeled “후대 그리스 기록”; a thin receding dashed depth line labeled “수백 년 뒤”.
Depth/occlusion: line follows the tabletop or support depth and does not touch either artifact.
Do not add: exact unsupported date interval, full timeline panel, readable writing, split screen, or implication that the objects were found together.

24 — Scene S15B / Keyframe KF-15B
CLEAN source: 24_S15B_KF-15B_CLEAN_confirmed-evidence-tableau.png
INFO output: 24_S15B_KF-15B_INFO_confirmed-evidence-tableau.png
Overlay purpose: gather only the categories independently supported by evidence.
Add: four restrained anchors labeled “범람 농업”, “토지 기록”, “측량”, “면적 계산”; neutral thin relation lines may share a central open area but must have no arrowheads.
Depth/occlusion: each anchor attaches to its real scene element; relation lines pass behind people and foreground objects.
Do not add: single origin arrow, causal ranking, giant conclusion text, formula, repeated figure, or post-flood restoration sequence.

25 — Scene S15C / Keyframe KF-15C
CLEAN source: 25_S15C_KF-15C_CLEAN_river-and-unconnected-rope-form.png
INFO output: 25_S15C_KF-15C_INFO_river-and-unconnected-rope-form.png
Overlay purpose: state the final evidentiary limit without replacing the contemplative physical scene.
Add: one teal anchor near the distant river labeled “범람”; one gold anchor near the foreground rope/tools labeled “실용 수학”; between them, a thin dashed neutral line that stops before connecting; small conclusion label “단일 원인으로 입증되지 않음”.
Depth/occlusion: anchors respect the river and ground planes; the interrupted line lies in empty middle ground and remains behind any terrain rise.
Do not add: giant title, red X, broken physical object, perfect geometric symbol, dramatic warning icon, or new historical claim.
```

## 승인 게이트

이 문서는 승인된 CLEAN 25개를 1:1로 편집하는 INFO 프롬프트만 정의한다. INFO 이미지는 아직 생성하지 않았으며, 사용자 승인 전에는 INFO 생성·검수 또는 VIDEO 프롬프트 단계로 진행하지 않는다.
