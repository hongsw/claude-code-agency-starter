# /help-project — 프로젝트 명령어 가이드

본 프로젝트(AI 에이전시 운영 시스템)에서 사용 가능한 모든 명령어를 보여준다.

## 실행할 것

아래 형식으로 출력:

```
## 🎯 의사결정자용 명령어

**현황 파악**
- `/dashboard` - 현황판 (전체 작업 상태 한눈에)
- `/brief` - 30초 브리핑 (빠른 현황 확인)
- `/week` - 주간 요약
- `/weekly-report` - 주간 리포트 생성
- `/feedback` - 고객 피드백 확인
- `/check-feedback` - 고객 피드백 확인

**의사결정**
- `/approve` - 승인 (리뷰중 작업 승인)
- `/reject` - 반려 (작업 반려 및 피드백)
- `/decide` - 결정 요청 상세 (선택지 제시)
- `/reprioritize` - 우선순위 재배치

**작업 관리**
- `/add` - 작업 추가 (빠른 TODO 추가)
- `/new-todo` - 새 TODO 생성 (상세 정보 포함)
- `/kickoff` - 실행 지시 (특정 작업 시작)

## 🤖 Claude Code 자율 실행용

**자동화**
- `/loop-start` - 자율 Loop 시작 (Notion TODO → 코드 → PR → Notion 기록)
- `/sync` - Notion 동기화
- `/sync-notion` - 현재 작업을 Notion에 동기화

## 💡 추천 워크플로우

**의사결정자 일일 루틴**:
```
/brief              # 아침: 빠른 현황 확인
/kickoff            # 작업 지시 또는 /loop-start로 자동 실행
/dashboard          # 저녁: 진행 상황 확인
```

**주간 루틴**:
```
/week               # 주간 요약 확인
/reprioritize       # 우선순위 조정
/weekly-report      # 주간 리포트 생성
```

**Claude Code 자율 실행**:
```
/loop-start         # Claude가 알아서 대기 TODO를 하나씩 처리
```
```

단순히 명령어 목록만 보여주는 것이 아니라, 사용 맥락과 추천 워크플로우를 함께 제공한다.
