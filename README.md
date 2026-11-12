# Codex Community Reports

OpenAI Developer Community의 Codex 및 ChatGPT Apps SDK MCP 관련 글을 조사한 한국어 기록입니다. OpenAI 공식 보고서가 아닙니다.

- 주기: 한국시간 매일 오전 9시 조사 작업.
- 범위: 실행 시점 직전24시간. 작성 시각 기준이며 각 보고서에 정확한 한국시간 범위를 기록합니다.
- 통계: 실제 읽은 본문만 집계한 부분 표본입니다. 영문 중심22개 주제 사전을 사용하므로 일반 어휘·인기·전체 장애 건수 순위와 다릅니다.
- 구분: 사용자 제보 / OpenAI 공식 지원 답변 / 사용자 확인 해결 / 추정 및 독립 미검증을 분리합니다.
- 저장: reports/YYYY-MM-DD.md 및 같은 이름의 JSON. 같은 날짜 재실행은 HHmmss 접미사로 보존합니다.
- 기존191 원본은 보존합니다. 이 저장소에는 조사 보고서와 관리 문서만 누적합니다.

## 보고서 목록

| 기록 | 보고서 | 집계·근거 JSON |
|---|---|---|
| 2026-10-21-7days | [읽기](reports/2026-10-21-7days.md) | [JSON](reports/2026-10-21-7days.json) |
| 2026-10-21 | [읽기](reports/2026-10-21.md) | [JSON](reports/2026-10-21.json) |
| 2026-10-22 | [읽기](reports/2026-10-22.md) | [JSON](reports/2026-10-22.json) |
| 2026-10-23 | [읽기](reports/2026-10-23.md) | [JSON](reports/2026-10-23.json) |
| 2026-10-24 | [읽기](reports/2026-10-24.md) | [JSON](reports/2026-10-24.json) |
| 2026-10-25 | [읽기](reports/2026-10-25.md) | [JSON](reports/2026-10-25.json) |
| 2026-10-26 | [읽기](reports/2026-10-26.md) | [JSON](reports/2026-10-26.json) |
| 2026-10-27 | [읽기](reports/2026-10-27.md) | [JSON](reports/2026-10-27.json) |
| 2026-10-28 | [읽기](reports/2026-10-28.md) | [JSON](reports/2026-10-28.json) |
| 2026-10-29-094104 | [읽기](reports/2026-10-29-094104.md) | [JSON](reports/2026-10-29-094104.json) |
| 2026-10-29 | [읽기](reports/2026-10-29.md) | [JSON](reports/2026-10-29.json) |
| 2026-10-30 | [읽기](reports/2026-10-30.md) | [JSON](reports/2026-10-30.json) |
| 2026-10-31 | [읽기](reports/2026-10-31.md) | [JSON](reports/2026-10-31.json) |
| 2026-11-01 | [읽기](reports/2026-11-01.md) | [JSON](reports/2026-11-01.json) |
| 2026-11-02 | [읽기](reports/2026-11-02.md) | [JSON](reports/2026-11-02.json) |
| 2026-11-03 | [읽기](reports/2026-11-03.md) | [JSON](reports/2026-11-03.json) |

## 운영 및 검증

새 작업 전에 AGENTS.md와 이 README를 읽습니다. 원본 보고서는 덮어쓰거나 삭제하지 않습니다. 보고서의 출처·범위·한계·본문별 수치와 저장 증거를 보존합니다. 새 보고서와 목록을 검토한 뒤 이 보고서 전용 저장소에 커밋합니다. 원격 재읽기·내용 및 SHA-256 대조가 성공한 경우에만 저장 PASS로 표시합니다.

기존 기록28개의 원본 SHA-256과 경로는 [이관 명세](manifests/migration-2026-11-01.json)에 보존합니다. 이관은 내용의 재검증이나 과거 판정의 승격을 뜻하지 않습니다.


## JARVIS Morning Radar 보관

JARVIS 외부 기술 레이더와 작업 복귀(PARENT_GOAL, PASS_GATE, TODAY_ONE_JOB 등) 기록을 한국시간 기준 매일 별도로 보관합니다. 이 공개 저장소에는 비밀값·내부 IP·비공개 로그를 저장하지 않습니다. 검증되지 않은 단계는 PASS로 표시하지 않습니다.

- [JARVIS 일별 보고서 폴더](reports/jarvis/)
- [2026-11-01 JARVIS 보고서](reports/jarvis/2026-11-01.md) · [근거 JSON](reports/jarvis/2026-11-01.json)
- [2026-11-01 야간 Runner 추가 검증](reports/jarvis/2026-11-01-235628.md) · [근거 JSON](reports/jarvis/2026-11-01-235628.json)
- [2026-11-03 JARVIS 보안·복귀 레이더](reports/jarvis/2026-11-03.md) · [근거 JSON](reports/jarvis/2026-11-03.json)

- [2026-11-04 JARVIS 복귀 레이더](reports/jarvis/2026-11-04.md) · [근거 JSON](reports/jarvis/2026-11-04.json)

- [2026-11-04 23:48 JARVIS LangGraph 메모리 추가 레이더](reports/jarvis/2026-11-04-234807.md) · [근거 JSON](reports/jarvis/2026-11-04-234807.json)

- [2026-11-05 JARVIS MCP·LangGraph·Home Assistant 복귀 레이더](reports/jarvis/2026-11-05.md) · [근거 JSON](reports/jarvis/2026-11-05.json)

- [2026-11-07 JARVIS 외부 레이더·작업 복귀](reports/jarvis/2026-11-07.md) · [근거 JSON](reports/jarvis/2026-11-07.json)

- [2026-11-08 JARVIS 복귀 레이더 (NO_CHANGE)](reports/jarvis/2026-11-08.md) · [근거 JSON](reports/jarvis/2026-11-08.json)

- [2026-11-08 야간 JARVIS OpenAI Agents SDK 추가 레이더](reports/jarvis/2026-11-08-234440.md) · [검증 JSON](reports/jarvis/2026-11-08-234440.json)

- [2026-11-10 JARVIS 복귀 레이더 (NO_CHANGE)](reports/jarvis/2026-11-10.md) · [근거 JSON](reports/jarvis/2026-11-10.json)

기존 Codex 커뮤니티 보고서 목록과 파일은 별도로 유지합니다.
- [2026-11-10 23:49 JARVIS 추가 레이더](reports/jarvis/2026-11-10-234954.md) · [검증 JSON](reports/jarvis/2026-11-10-234954.json)
- [2026-11-12 JARVIS MCP 보안·복귀 레이더](reports/jarvis/2026-11-12.md) · [근거 JSON](reports/jarvis/2026-11-12.json)
- [2026-11-13 JARVIS Pipecat 음성·E2E 복귀 레이더](reports/jarvis/2026-11-13.md) · [검증 JSON](reports/jarvis/2026-11-13.json)
