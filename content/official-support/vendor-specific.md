# 공급사에서 공식으로 제공하는 도구모음
## JetBrains
### Jetbrains/thinkrail
- https://github.com/JetBrains/thinkrail

JetBrains 인큐베이터에서 개발한 가벼운 데스크톱 개발 도구로, 오픈소스 코딩 에이전트 pi를 내장하고 있으며 작업 공간별 git worktree 및 스펙 문서를 지원합니다.<br/>

## Anthropic
### anthropics/skills
- https://github.com/anthropics/skills

Anthropic이 제공하는 공식 예제 스킬 19개 모음으로, Claude 앱 문서 기능 등과 연동됩니다.<br/>

2026.11.18
- 문서 관련 스킬 2회 수정
- PPTX: 테마 → 레이아웃 → 자리 표시 칸 순서로 구성하는 구조화된 덱 생성 방식
- XLSX: 사본에서 계산한 뒤 값만 원본에 반영하여 외부 링크 보존
- 문서를 PDF·이미지로 변환할 때 문서 외부 파일 링크부터 제거하도록 개선

## alibaba
### alibaba/open-code-review
https://github.com/alibaba/open-code-review

코드 변경 사항에 줄 단위 리뷰 댓글을 남기는 CLI입니다.<br/>

파일 선택과 댓글 위치 지정은 정해진 코드가 담당하고, 문맥 판단만 에이전트가 수행하는 구조입니다.<br/>

- **주요 업데이트**
  - 9월 말 이후 릴리스 16건
  - 10월 ChatGPT 요금제 로그인 미리보기 추가
  - 이번 주 GitHub Copilot CLI 연동
  - `--tools` 옵션 제거
- **참고 사항**
  - ChatGPT 로그인은 개인 및 본인 컴퓨터 사용을 전제로 합니다.
  - 공용 CI 환경에서 개인 계정을 사용하지 않아야 합니다.

<br/>

## vercel
### vercel-labs/agent-browser
https://github.com/vercel-labs/agent-browser

에이전트가 셸 명령을 통해 브라우저를 제어할 수 있도록 지원하는 CLI입니다.<br/>

- **주요 업데이트**
  - v0.43.0 (11/13 KST)
  - Modern Web Guidance 스킬 추가
  - 지침에 따라 만든 페이지의 화면 밀림, 움직임 감소, 색 테마, 대화상자 포커스 등을 실제 브라우저에서 확인하고 근거와 함께 보고
  - 이름이 없는 아이콘 버튼에 대한 힌트 추가
- **참고 사항**
  - 기본 설정에서는 페이지 이동과 동작에 제한이 없습니다.

<br/>
