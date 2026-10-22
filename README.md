# labyrinth03 | Game Client Programmer

## About Me

- SGU CSE 21
- Unreal Engine 5 기반 협동 액션 RPG **Balance Due** 1인 개발


## Featured Project

### [Balance Due](https://store.steampowered.com/app/5198690/Balance_Due/)

낮과 밤의 순환 속에서 할당량을 관리하며 탐험하는 Unreal Engine 5 기반 협동 액션 RPG입니다.

- C++와 Blueprint를 활용한 전투, 인벤토리, 상점, 강화, 포탈과 세이브 시스템 구현
- Server Authority, RPC, Replication 기반의 Steam 온라인 멀티플레이 구현
- GameState, PlayerState, SaveGame을 활용한 공용·개인·영속 상태 분리
- Unreal Insights와 CSV Profiler를 활용한 AI Tick 및 네트워크 갱신 최적화
- Shipping 패키징, Steam 도전과제, SteamPipe 빌드 업로드와 출시 준비

### [Morituri](https://github.com/2026-1-capstone-design/main-game)

Unity 6 기반 검투사 육성·전투 게임의 캡스톤디자인 팀 프로젝트입니다.

- 게임 진입 흐름과 인벤토리, 상점, 스쿼드 편성 및 전투 UI 구현
- 검투사, 장비, 재화와 진행 상태를 관리하는 JSON 기반 슬롯 세이브 시스템 개발
- UI 레이아웃 갱신 충돌과 저장 데이터 참조 불일치 문제 해결
- 교내 캡스톤디자인 경진대회 은상

### [겜만툴](https://github.com/2026-2-CapstoneTeamIdle/MainFlowChart)

자연어 요구사항을 바탕으로 플레이 가능한 Unity 2D 게임 프로토타입을 생성하는 캡스톤디자인 팀 프로젝트입니다.

- 플랫포머, 타워디펜스, 카드 게임 등 6개 장르의 공통 C# 게임플레이 모듈과 Unity 프로젝트 생성 파이프라인 구현
- 기존 모듈을 조립하고 부족한 기능만 LLM으로 생성하는 장르별 기능 설계 및 코드 생성 구조 개발
- 게임 디렉팅, 시스템, 콘텐츠, 레벨과 밸런스를 구조화한 JSON 설계 계약과 Scene·Prefab 자동 조립 기능 구현
- MCP 기반 프로젝트 파일 탐색 및 API 인덱스를 활용한 생성 코드 문맥 검수 체계 구축
- Unity 컴파일·Play Mode 결과를 반영하는 자동 수정 반복과 독립 Validator AI를 통한 결과물 검증

### [PUBG SUS](https://github.com/labyrinth03/PUBG_Malicious_Detect)

[사이트 바로가기](https://pubg-a2d6rnagf-still-blinding.vercel.app/)

팀킬을 유도하는 아군 피해와 방송 저격 의심 상황을 확인하기 위해 만든 PUBG 공식 API 기반 웹 도구입니다. 여러 경기의 전적을 일일이 대조하는 대신, 피해의 선후 관계와 두 플레이어의 동시 매칭 기록을 한 화면에서 확인할 수 있도록 개발했습니다.

- JavaScript, Node.js, Express로 Steam·Kakao 서버의 최근 매치 조회 및 분석 구현
- 참가자·팀 구성과 telemetry 피해 이벤트를 대조해 아군 피해를 분류하고, 최초 공격 이후 받은 피해를 타임라인으로 표시
- 두 플레이어의 매치 ID 교집합에서 같은 팀 경기를 제외해 저격 의심 판단에 필요한 동시 매칭 기록 제공
- 외부 요청 동시 실행·대기열·시간 초과 제한과 Promise 캐시로 중복 작업 및 실패 후 재시도 처리
- 분석·API 통합 테스트 13개로 피해 분류, 시간 순서, 부분 실패와 요청 복구 검증

## Tech Stack

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![Unreal Engine](https://img.shields.io/badge/Unreal_Engine-0E1128?style=flat-square&logo=unrealengine&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Steam](https://img.shields.io/badge/Steamworks-1B2838?style=flat-square&logo=steam&logoColor=white)
