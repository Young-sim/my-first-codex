# Project Status

- **Project:** Nile Flood, Land Survey, and Egyptian Geometry Short
- **Topic:** 나일강의 주기적 범람, 고대 이집트 농업, 토지 경계의 재측량과 이집트 기하학의 발달 사이의 관계
- **Target duration:** 약 90초
- **TTS voice:** Vrew 다현 1 (빠르게)
- **Actual TTS duration:** 86초 (`01:26`)
- **Aspect ratio:** `9:16`
- **Current approved stage:** STAGE 5 — INFO second-pass 편집 프롬프트 25개 사용자 승인 완료
- **Last completed asset ID:** `KF-15C` INFO 프롬프트 승인 완료 (INFO 이미지 미생성)
- **Next required stage:** 승인 CLEAN 25개와 승인 INFO 프롬프트를 사용해 외부에서 INFO 이미지 25개 생성 후 STAGE 6 CLEAN–INFO 1:1 검수
- **Known defects:** 범람 후 경계 복원의 구체적 절차는 직접 증거가 없어 장면에서 단정하지 않음
- **Regeneration required:** 없음
- **Pending user approval:** 없음 — 실제 INFO 이미지 생성·제공 대기

## Stage files

- `script/STAGE1_RESEARCH_AND_SCRIPT_KR.md` — 조사 메모, 네 가지 핵심 문장, Production script, Clean Korean TTS narration
- `script/APPROVED_NARRATION_KR.md` — 사용자 승인된 최종 한국어 TTS 내레이션
- `manifests/IMAGE_SEQUENCE.md` — 실제 86초 TTS 기준 STAGE 2 장면·키프레임 계획
- `prompts/CLEAN_KEYFRAME_PROMPTS.md` — 25개 키프레임의 독립형 CLEAN 이미지 생성 프롬프트
- `prompts/CLEAN_TEST_KF-01A.md` — 품질 확인용 `KF-01A` 단일 독립 프롬프트
- `clean/README.md` — 외부 CLEAN 이미지 생성·파일명·제출 절차
- `manifests/CLEAN_ASSET_REVIEW_CHECKLIST.md` — 정식 25개와 재생성·추가 4개를 분리하는 STAGE 4 검수 원장
- `prompts/INFOGRAPHIC_KEYFRAME_PROMPTS.md` — 승인 CLEAN 25개의 1:1 restrained engineering overlay 편집 프롬프트
- `info/README.md` — INFO 생성에 필요한 입력 자산, 작업 순서, STAGE 6 검수 인계 절차

## Approval gate

STAGE 1 내레이션, STAGE 2의 86초·25개 장면 매핑, STAGE 3 CLEAN 프롬프트와 정식 CLEAN 25개, STAGE 5 INFO 프롬프트 25개가 사용자 승인·확정됐다. EXTRA 4개는 정식 시퀀스와 INFO 입력에서 제외한다. 실제 INFO 이미지는 아직 생성하지 않았으며, INFO 생성 후 STAGE 6 검수와 사용자 승인이 완료되기 전에는 VIDEO 프롬프트 또는 영상 자산을 만들지 않는다.
