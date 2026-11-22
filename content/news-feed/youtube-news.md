
## 2026.11
### AI 로 만든 Rust 애플리케이션 개발이 주목받는 중
- 이제 앱도 Rust가 대세? Discord가 앱을 Rust로 다시 만드는 중
- https://www.youtube.com/shorts/Z90SxbppmZU
- 아직은 AI 관련된 뉴스나 주요 사용경험들이 다들 '나 이거 해봤다'류 정도가 많아서 아직까지는 AI 사용사례가 완전한 성숙기에 도달하진 않은것 같아보이긴 합니다.

#### Discord**
- 데스크탑 앱은 기존 애플리케이션 대신 Rust 버전으로 새로 제작 중
- 기존 앱: 1GB 넘게 메모리를 사용
- Rust 앱: 290MB 메모리를 사용
- 뭐든 새로 만든 앱은 가볍고 레거시가 덜 쌓여서 체감상 더 빨라보이고 좋아보인다는 점도 감안해서 무조건 Rust가 맞다로 판단하지는 말아야 할것 같습니다.

https://x.com/svishnevskiy/status/2118081920194203799
> 저희는 2018년부터 Rust를 초기부터 사용해 왔으며, 인프라, 음성 기술, 심지어 현재 클라이언트의 일부까지 이미 Rust로 개발되었습니다. 궁극적인 목표는 클라이언트 전체를 Rust로 만드는 것이었습니다. 즉, Electron과 React Native는 더 이상 사용하지 않고, 모바일 버전은 네이티브 UI를 유지하면서 데스크톱 버전과 Rust를 통해 앱 코드를 공유합니다. 조만간 사용자 테스트를 시작할 수 있기를 바랍니다. (그리고 Tauri가 아니라 GPUI입니다. 모두 잘 맞추셨네요.) 자, 이제 다시 WoW Forever 로그인 화면을 봐야겠습니다.

시연영상: https://launchscene.app/v/discord-rebuilding-discord-in-rust-project-phoenix


#### Expo Exact — Rust 기반 Agent-Native 앱 프레임워크
> Expo 역시 Rust 기반의 Exact 프레임워크를 공개했으며, 한번 작성 후 Mac, Web, Mobile 빌드가 모두 가능하다고 합니다. AI 를 통해 조사한 내용은 다음과 같습니다.

**Exact**는 Expo에서 2026년 11월 공개한 Rust 기반의 크로스 플랫폼 애플리케이션 프레임워크입니다. 기존 React Native와 달리 AI 에이전트가 애플리케이션을 생성, 실행, 테스트할 수 있도록 설계된 **Agent-Native App Framework**를 지향합니다.<br/>

주요 특징은 다음과 같습니다.<br/>

- **Rust 기반 런타임**: Rust를 활용하여 공통 애플리케이션 실행 환경과 플랫폼 간 기능을 구현합니다.
- **크로스 플랫폼 지원**: Web, macOS, iOS, Linux 등 여러 플랫폼에서 애플리케이션을 실행하는 것을 목표로 합니다.
- **AI Agent 중심 설계**: AI 에이전트를 통한 애플리케이션 생성, 실행, 검증 및 자동화를 지원하도록 설계되었습니다.
- **Contract 기반 아키텍처**: 플랫폼 간 공유되는 애플리케이션 정의를 활용하여 UI와 동작을 구성합니다.
- **TypeScript 지원**: Rust 기반 런타임을 사용하면서 TypeScript로 애플리케이션 로직을 작성할 수 있습니다.

Exact는 현재 **Pre-alpha 단계**로, 상용 환경에 바로 적용하기보다는 Rust 기반 크로스 플랫폼 개발과 AI 중심 애플리케이션 개발의 새로운 접근 방식으로 살펴볼 만한 프로젝트입니다.<br/>

**참고 자료**
- GitHub: https://github.com/expo/exact
- Expo 공식 홈페이지: https://expo.dev/