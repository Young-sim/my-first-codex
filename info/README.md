# INFO Asset Generation Handoff

## 현재 상태

`prompts/INFOGRAPHIC_KEYFRAME_PROMPTS.md`의 25개 INFO second-pass 편집 프롬프트는 사용자 승인본으로 확정됐다. 실제 INFO 이미지는 아직 생성하지 않았다.

## 운영 규칙상 다음 단계

다음 작업은 승인된 CLEAN–INFO 1:1 매핑을 이용해 외부 이미지 편집 플랫폼에서 **INFO 이미지 25개를 생성**하는 것이다. 생성이 완료되면 STAGE 6에서 CLEAN과 INFO를 ID별로 비교 검수한다.

INFO는 새로운 장면 생성이 아니다. 각 CLEAN 파일을 변경 불가능한 base plate로 사용하고, 같은 장면 위에 승인된 restrained engineering overlay만 추가해야 한다.

## 필요한 입력 자산

1. 사용자 승인된 정식 CLEAN 이미지 25개
   - Scene ID / Keyframe ID / 파일명은 `manifests/CLEAN_ASSET_REVIEW_CHECKLIST.md`의 `USER APPROVED` 25개를 사용한다.
   - 정식 시퀀스에서 제외된 EXTRA 이미지 4개는 사용하지 않는다.
2. 승인된 INFO 편집 프롬프트
   - `prompts/INFOGRAPHIC_KEYFRAME_PROMPTS.md`
3. 승인된 장면 매핑
   - `manifests/IMAGE_SEQUENCE.md`
4. 승인된 내레이션
   - `script/APPROVED_NARRATION_KR.md`

## 다음 단계에서 수행할 작업

1. 같은 Keyframe ID의 승인 CLEAN 이미지와 INFO 프롬프트를 한 쌍으로 준비한다.
2. 외부 플랫폼에서 **새 이미지 생성이 아니라 기존 CLEAN 이미지 편집** 모드를 사용한다.
3. CLEAN의 카메라, 크롭, 원근, 인물, 자세, 손, 복식, 도구, 물, 토양, 파피루스, 조명, 재질과 배경을 그대로 보존한다.
4. 해당 ID에 지정된 앵커, 선, 화살표, 짧은 한국어 라벨만 추가한다.
5. 결과를 프롬프트에 명시된 정확한 INFO 파일명으로 별도 저장한다. CLEAN 원본을 덮어쓰지 않는다.
6. 25개 생성 결과를 `info/`에 제공한다.
7. STAGE 6에서 CLEAN–INFO 쌍을 실제로 열어 카메라·구도·인물·지형 보존, 라벨 정확성, 원근·가림, 화살표 방향, 누락·중복을 검수한다.
8. 결함이 있으면 전체 세트가 아니라 해당 Keyframe ID만 수정한다.

## STAGE 6 검수에 필요한 파일 구조

```text
clean/
  01_S01A_KF-01A_CLEAN_....png
  ...
  25_S15C_KF-15C_CLEAN_....png

info/
  01_S01A_KF-01A_INFO_....png
  ...
  25_S15C_KF-15C_INFO_....png
```

각 CLEAN–INFO 쌍은 번호, Scene ID, Keyframe ID가 같아야 한다. 파일명에서 달라지는 역할 표시는 `_CLEAN_`과 `_INFO_`뿐이며, 설명 부분은 유지한다.

## 생성 전 확인 사항

- INFO 프롬프트 전체를 승인본 그대로 사용한다.
- CLEAN 25개 중 해당 ID의 정확한 이미지가 입력되었는지 확인한다.
- EXTRA 4개를 입력으로 사용하지 않는다.
- 플랫폼에 같은 ID의 CLEAN 이미지가 이미 있다면 다시 업로드할 필요는 없지만, 다른 ID의 이미지를 참조하지 않는다.
- INFO를 첫 장면이나 새로운 합성 장면으로 만들지 않는다.
- 거대한 제목, 문장형 자막, 검증되지 않은 숫자·단위·공식, 평면 HUD를 추가하지 않는다.
- 원본 CLEAN은 보존하고 INFO는 별도 파일로 저장한다.

## 다음 승인 게이트

INFO 이미지 25개가 생성되고 STAGE 6의 CLEAN–INFO 1:1 검수를 통과한 뒤 사용자 승인을 받는다. 그전에는 CLEAN-to-INFO VIDEO 프롬프트를 작성하거나 영상을 생성하지 않는다.
