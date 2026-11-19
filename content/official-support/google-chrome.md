
## GoogleChrome/modern-web-guidance-src

코딩 에이전트가 오래된 방식 대신 최신 HTML·CSS·브라우저 API를 사용하도록 돕는 지침 스킬 및 CLI입니다. 검색은 로컬에서 수행하며, 262개의 웹 기능과 각 기능의 브라우저 지원 정보를 제공합니다.

- **주요 업데이트**
  - 2026/11/10 Chrome 공식 블로그에서 1.0 정식판 발표
  - Firefox·Edge 팀도 함께 관리
  - 1.0에 기존 코드의 오래된 패턴을 탐지하는 `legacy-scan` 추가
  - Chrome 팀 자체 평가에서 Claude Code 과제 통과율 57% → 88%
  - 발표 후 일주일간 npm 다운로드 약 2.5배 증가
- **참고 사항**
  - 트렌딩에 오른 저장소는 원본(`-src`)이며, 실제 설치되는 배포본은 `GoogleChrome/modern-web-guidance`입니다.
  - 사용 통계 기본 활성화(에이전트가 생성한 검색어가 Google로 전송됨)

## ChromeDevTools/chrome-devtools-mcp

코딩 에이전트가 실제 Chrome을 열고 조작하면서 성능·네트워크·콘솔·메모리 등을 Chrome DevTools 기능 그대로 확인할 수 있도록 지원하는 Google 공식 도구입니다.

- **주요 업데이트**
  - v1.13.0 (2026/11/11)
  - 네트워크 응답을 로컬 파일로 대체하는 네트워크 목(Mock) 기능 추가(기본 비활성화, `--categoryNetworkMocks` 옵션)
  - 코드 수정 없이 로그를 남기는 Logpoint 지원
- **참고 사항**
  - 사용 통계 기본 활성화
  - 성능 측정 시 페이지 주소가 Google(CrUX)로 전송될 수 있습니다.

