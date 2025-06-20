<!--
✅ 좋은 ADR 제목을 작성하는 방법
기본 원칙:
ADR 제목은 해당 문서가 어떤 기술적 결정을 다뤘는지를 간결하고 명확하게 요약해야 합니다.
이해하기 쉬운 동사와 핵심 명사를 활용하여, 한눈에 "무엇을 왜 결정했는가"를 알 수 있도록 만드세요.

✍️ 제목 작명 가이드
행동 중심 동사로 시작하세요.
예: Use, Choose, Switch, Deprecate, Adopt

무엇을 결정했는지를 짧고 명확하게 표현하세요.
예: Use Airflow for DAG orchestration

가능하면 '왜' 혹은 '언제'에 대한 간단한 맥락도 포함하세요.
예: Adopt batch ingestion for MVP stability

일관된 스타일을 유지하세요.
예: Verb + 대상 + 맥락 형식

📚 예시
- Use Airflow for DAG orchestration
- Adopt batch ingestion for low-volume data
- Switch from S3 to Delta Lake for data lake
- Reject real-time ingestion due to infra constraints
- Deprecate cron-based jobs in favor of managed scheduler
-->
# ADR-XXX: [결정 제목을 간결하고 명확하게]

## Status
<!-- 현재 이 결정의 상태는? -->
<!-- 예: Proposed, Accepted, Rejected, Superseded -->
Status: Proposed

## Date
<!-- 이 결정을 작성한 날짜는? -->
2025-06-20

---

## 1. Context (배경 및 문제 정의)
<!--
- 지금 어떤 문제를 해결하려는가?
- 왜 이 결정이 지금 필요한가?
- 어떤 제약이나 조건이 있는가?
- 이 문제가 시스템이나 사용자에게 어떤 영향을 주고 있는가?
-->

## 2. Decision (내린 결정)
<!--
- 우리가 내린 최종 결정은 무엇인가?
- 선언하듯 명확하게 적어보자.
- 예: "우리는 A 방식을 선택하기로 했다."
-->

## 3. Alternatives Considered (고려했던 대안들)
<!--
- 어떤 대안들이 있었는가?
- 각각의 장점과 단점은 무엇이었나?
- 왜 그 대안들을 선택하지 않았는가?
- 표나 목록 형태로 정리해도 좋다.
-->

## 4. Rationale (결정의 이유)
<!--
- 선택한 안이 다른 대안보다 나았던 이유는 무엇인가?
- 이 결정은 어떤 기준(비용, 성능, 단순성, 팀 역량 등)에 기반했는가?
- 직관이 아닌, 논리적이고 명확한 근거를 적어보자.
-->

## 5. Consequences (영향 및 결과)
<!--
- 이 결정을 채택하면 어떤 변화가 생길까?
- 긍정적인 효과는 무엇이고, 감수해야 할 트레이드오프는 무엇인가?
- 향후 이 결정으로 인해 생길 수 있는 리스크나 기술부채는?
-->

## 6. Related Decisions (관련 ADR 문서)
<!--
- 이 결정과 직접 연결되거나 영향을 주고받는 ADR이 있는가?
- 만약 있다면 번호와 제목을 함께 명시하자.
-->

## 7. References (참고 자료)
<!--
- 이 결정을 내리는 데 참고한 문서, 회의록, 외부 글 등이 있다면 모두 정리
- 내부 위키 문서, 기술 블로그, 테스트 결과, 회의 기록 등을 포함
-->
