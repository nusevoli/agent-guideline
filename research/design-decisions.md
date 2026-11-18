# 모듈형 공통 지침의 설계 근거

## 채택한 방향

- 공통 원칙은 짧게 유지하고 목적별 상세 문서를 조건부로 읽는다.
- 특정 도구 대신 상태·인계·완료 근거를 공통화한다.
- 기술별 프로필 대량 작성보다 필요 시 기존 스킬·에이전트 조사·도입을 우선한다.
- 프로젝트별 명세·컨벤션·검사·실제 TODO는 프로젝트에서 관리한다.
- 외부 프레임워크와 지식 그래프는 확정하지 않는다. 자동 실행기는 이번 문서 변경에 포함하지 않는다.

## 참고 자료와 적용 한계

아래는 설계 조사에서 확인한 참고 경로다. 변경 가능한 main 문서이므로 실제 도입 시 버전·라이선스·호환성을 다시 확인한다. 인기도·홍보·개인 후기는 성능 검증을 대신하지 않는다.

| 자료 | 참고한 관점 | 도입 판단 |
| --- | --- | --- |
| [OpenAI harness engineering](https://openai.com/index/harness-engineering/) | 짧은 진입 문서·실행 가능한 검사 | 원칙 참고 |
| [Superpowers](https://github.com/obra/superpowers) | 구현·검토 흐름 | 승인·완료 기준 충돌 검토 후 실험 후보 |
| [OpenSpec](https://github.com/Fission-AI/OpenSpec) | 명세와 변경 기록 | 프로젝트 실험 후보 |
| [Matt Pocock skills](https://github.com/mattpocock/skills) | 조건부 질문·선택형 전문 절차 | 개별 스킬 검토 후보 |
| [GSD Core](https://github.com/open-gsd/gsd-core) | 단계·상태·재개 | 장기 작업 실험 후보 |
| [BMAD](https://github.com/bmad-code-org/BMAD-METHOD) | 제품·설계·개발 연결 | 필요 시 평가 |
| [ECC](https://github.com/affaan-m/ECC) | 전문 기능 묶음 | 호환성·중복 확인 필요 |
| [Oh-My-OpenClaw](https://github.com/happycastle114/oh-my-openclaw) | 역할 분리·이벤트 재개 | 문서와 실제 강제 기능 구분 |

이 저장소에 외부 스킬 코드를 복사하거나 설치한 것은 아니다. 수치 비교와 대화 원문은 배포 규칙에 포함하지 않는다.
