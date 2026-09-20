출처: 다운로드 머더 미스터리/Claude.md (확장자는 .md이나 실제 DOCX이므로 문단 텍스트 추출)

# CLAUDE.md — Murder Mystery 제작 규칙



## 작업 원칙

- 단서/타임라인/캐릭터 중 하나를 수정하면 연관된 나머지도 반드시 함께 체크

- 새 요소 추가 전 기존 파일과 모순 여부 먼저 언급할 것

- 확신 없으면 만들지 말고 물어볼 것



## 파일 구조

/mystery/biblecharacters.md # 캐릭터 전체 (SPOILER 포함)timeline.md # 마스터 타임라인truth.md # 범행 진실 [MASTER]/player-facingclues/ # 단서 카드 (스포일러 제거)character-sheets/ # 플레이어용 시트/gm-guidehints.md # 힌트 흐름 가이드



## 출력 규칙

- 스포일러 포함 내용: 파일 상단에 `[SPOILER]` 명시

- 플레이어용 파일: truth.md 절대 참조 금지

- 단서 카드 포맷 항상 통일:

[단서명] / 발견 위치 / 공개 시점내용:연결 단서:



## 요청 방식 가이드

- "캐릭터 추가해줘" → characters.md 수정 + timeline 영향 체크까지

- "단서 만들어줘" → truth.md 참고해서 모순 없는지 검증 후 생성

- "플레이어 시트 뽑아줘" → /player-facing만 참조, bible은 참고용
