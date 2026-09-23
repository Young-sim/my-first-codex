# CLEAN Asset Handoff

이 폴더는 승인된 25개 CLEAN 키프레임의 외부 생성 결과를 받기 위한 위치다. 현재 이미지 자산은 아직 생성되거나 검수되지 않았다.

## 사용자가 수행할 작업

1. `prompts/CLEAN_KEYFRAME_PROMPTS.md`를 연다.
2. 파일 안의 단일 `text` 코드 블록 전체를 첫 줄 `Create the complete batch...`부터 마지막 `25 — Scene S15C / Keyframe KF-15C` 지시문 끝까지 그대로 복사한다.
3. 외부 이미지 생성 플랫폼의 새 작업 또는 동일한 배치 세션에 한 번에 붙여 넣는다.
4. 플랫폼이 배치를 지원하면 **25개 독립 이미지**로 생성한다. 지원하지 않으면 코드 블록의 공통 규칙을 유지한 채 `01`부터 `25`까지 한 항목씩 생성한다.
5. 각 결과를 프롬프트에 지정된 정확한 파일명으로 저장한다. 자동으로 붙은 임의 파일명이나 생성 순서를 신뢰하지 않는다.
6. 결과 파일 25개를 이 `clean/` 폴더에 넣는다. 원본 파일은 덮어쓰거나 삭제하지 않는다.
7. 생성이 끝나면 전체 파일을 제공하고 CLEAN 자산 검수를 요청한다. 그때 실제 이미지를 열어 내용과 순서를 검증한다.

## 외부 플랫폼에 넣을 정확한 배치 프롬프트

정본은 다음 파일의 **단일 코드 블록 전체**다.

```text
prompts/CLEAN_KEYFRAME_PROMPTS.md
```

프롬프트를 요약하거나 번역하거나 재작성하지 않는다. 특히 다음 항목을 플랫폼 입력에서 제거하지 않는다.

- `OUTPUT REQUIREMENTS`
- `PROJECT-WIDE HISTORICAL CONTINUITY`
- `GLOBAL CLEAN PROHIBITIONS — APPLY TO EVERY IMAGE`
- 25개 Scene ID / Keyframe ID별 전체 지시문
- 각 항목의 정확한 `Filename`

## 생성 순서와 기대 파일명

```text
01_S01A_KF-01A_CLEAN_flood-submerges-field-marker.png
02_S02A_KF-02A_CLEAN_broad-inundated-floodplain.png
03_S03A_KF-03A_CLEAN_water-and-silt-enter-low-field.png
04_S04A_KF-04A_CLEAN_natural-high-water-traces.png
05_S05A_KF-05A_CLEAN_low-flood-dry-outer-field.png
06_S05B_KF-05B_CLEAN_excess-water-over-cultivated-ground.png
07_S06A_KF-06A_CLEAN_silt-alters-ground-marker.png
08_S07A_KF-07A_CLEAN_farming-resumes-on-damp-silt.png
09_S08A_KF-08A_CLEAN_harvest-and-scribe-observation.png
10_S08B_KF-08B_CLEAN_varied-field-parcels-landscape.png
11_S09A_KF-09A_CLEAN_tomb-art-survey-evidence-context.png
12_S09B_KF-09B_CLEAN_rope-field-measurement-reconstruction.png
13_S10A_KF-10A_CLEAN_rope-and-wooden-stake-detail.png
14_S11A_KF-11A_CLEAN_wilbour-papyrus-object-context.png
15_S11B_KF-11B_CLEAN_land-recording-workspace.png
16_S11C_KF-11C_CLEAN_scribe-and-distant-survey-context.png
17_S12A_KF-12A_CLEAN_rhind-papyrus-object-context.png
18_S12B_KF-12B_CLEAN_varied-field-shapes-oblique-view.png
19_S13A_KF-13A_CLEAN_practical-measurement-calculation-workspace.png
20_S14A_KF-14A_CLEAN_later-greek-author-context.png
21_S14B_KF-14B_CLEAN_herodotean-account-symbolic-land-loss.png
22_S14C_KF-14C_CLEAN_rope-lines-suggest-geometry.png
23_S15A_KF-15A_CLEAN_two-era-material-evidence-depth.png
24_S15B_KF-15B_CLEAN_confirmed-evidence-tableau.png
25_S15C_KF-15C_CLEAN_river-and-unconnected-rope-form.png
```

## 제출 전 빠른 확인

- 파일 수가 정확히 25개인가?
- 모두 개별 9:16 이미지인가?
- 파일명 접두사가 `01_`부터 `25_`까지 중복이나 누락 없이 이어지는가?
- 텍스트, 숫자, 라벨, 화살표, 측정선, UI, HUD, 로고, 워터마크가 없는가?
- 범람 장면과 측량 장면이 동일한 밭의 경계 복원 전후처럼 보이지 않는가?
- 콜라주, 분할 화면, 접촉 시트가 아닌가?

하나라도 실패하면 전체 배치를 다시 만들지 말고 해당 Keyframe ID만 별도로 재생성한다. 최종 적합성 판정과 순서 확정은 실제 파일을 받은 뒤 STAGE 4에서 수행한다.
