# Harness 및 Agent Engineering
## 하네스 스킬
### obra/superpowers
- https://github.com/obra/superpowers

요구 확인부터 계획, 테스트 먼저, 리뷰로 이어지는 개발 순서를 강제하는 16개의 하네스 스킬 묶음입니다.<br/>

Github Star 가 약 32만개로 코딩 AI가 코드부터 짜지 않고 계획과 테스트를 먼저 하게 만드는 스킬 모음입니다. 최근 업데이트에서는 AI가 처음에 던지는 질문이 너무 많다는 불만을 받아들여, 자체 테스트에서 나오던 불필요한 질문을 41개에서 23개로 줄였다고 합니다.<br/>

관련 설명
- https://www.youtube.com/watch?v=wD_KuqThn1g&t=462s

<br/>

### ECC (8:02)
- **GitHub:** https://github.com/affaan-m/everything-claude-code
- **설명:** 72개의 에이전트와 수백 개의 스킬이 포함된 체계적인 AI 코딩 환경 설정 도구입니다.
- 엔트로픽 해커톤 우승자가 자기 클로드 코드 설정을 모아 만든 저장소입니다. superpowers 처럼 AI가 코드를 짜는 과정을 체계적으로 만들어주지만, 규모는 훨씬 커서 에이전트 72개와 스킬 327개가 들어있습니다. 

계획하고 테스트하는 데 까지는 superpowers 와 비슷하지만 ECC 는 끝난 작업을 한 번 더 검토하게 하고, 중요한 내용은 기억해두고, 자주 반복하는 작업은 다음에 바로 꺼내 쓸 스킬로 만들어둡니다.<br/>

Claude Code, Codex, Cursor 에서 모두 쓸수 있습니다. 설치 방법이 여러가지라 겹쳐서 설치하면 스킬이 두번 설치하게 되므로 설치 방법을 하나만 골라서 설치하면 됩니다.<br/>


관련 설명
- https://www.youtube.com/watch?v=wD_KuqThn1g&t=482s


### addyosmani/agent-skills
- https://github.com/addyosmani/agent-skills

스펙 → 계획 → 구현 → 테스트 → 리뷰 → 출시 순서를 에이전트가 준수하도록 돕는 스킬 모음입니다.<br/>

- **주요 업데이트**
  - v0.6.16 (2026/11/14): 출시된 기능은 변경 스펙만 별도로 관리하고, 문서가 오래되었는지 감지하는 기능 추가
  - v0.6.15 (2026/10/31): 보안 스킬이 탐지한 비밀값을 출력하던 문제 수정

<br/>

## Claude.md, AGENT.md
### multica-ai/andrej-karpathy-skills
- https://github.com/multica-ai/andrej-karpathy-skills

Andrej Karpathy의 글을 바탕으로 다른 개발자가 구축한 CLAUDE.md 원칙 스킬입니다.<br/>
