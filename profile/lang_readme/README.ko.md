<div align="center">
  <br>
  <img src="../assets/distillery-512.png" width="140" alt="Distillery" />
  <h1>Distillery</h1>
  <p><strong>생각을 숙성된 지식으로 증류하다.</strong></p>
  <br>
</div>

지식은 정돈된 채로 찾아오지 않습니다. 산책 중 떠오른 인사이트, 회의에서 내린 결정, 머릿속을 떠나지 않는 질문 — 늘 파편으로 흩어져 있습니다.

**Distillery**는 이 날것의 생각들을 살아 있는 지식 그래프로 변환합니다. 위스키 증류의 과정과 어휘를 빌려, 각 단계에 목적을 부여하고 한 걸음마다 명료함을 더합니다.

<br>

## 과정

```
Malting          날것의 생각을 포착 — 결정, 문제, 인사이트, 질문
   ↓
Still            중요한 것을 선별하고 큐레이션
   ↓
Distillation     AI가 의미를 임베딩하고, 숨겨진 관계를 발견
   ↓
Cask             지식이 연결된 그래프 속에서 숙성
   ↓
Blending Room    탐색하고, 다듬고, 사람의 판단으로 연결
```

<br>

## 프로젝트

### [Moonshine](https://github.com/Cognito-Distillery/moonshine)

통합 독립 실행형 에디션. 기록, 선별, 증류, 탐색까지 하나의 앱에서 — 서버 없이 동작합니다. 단일 SQLite 파일에 전체 지식 그래프를 저장합니다. 자연어 검색, 자동 관계 발견, 플로팅 메모를 지원합니다.

`Tauri 2` `Svelte 5` `Rust` `SQLite` `Cytoscape.js` `OpenAI` `Gemini`

### [Moonshine MCP](https://github.com/Cognito-Distillery/Moonshine-MCP)

Moonshine 지식 그래프에 AI 어시스턴트(Claude, ChatGPT, Gemini)가 직접 접근할 수 있게 해주는 MCP 서버. 자연어 대화로 매시와 관계를 검색, 탐색, 편집할 수 있습니다. Moonshine 앱과 독립적으로 동작합니다.

`MCP` `TypeScript` `better-sqlite3`

---

### [Distillery Desktop](https://github.com/Cognito-Distillery/Distillery-desktop)

오리지널 클라이언트. 생각을 포착하고 큐레이션하는 데스크톱 앱. 글로벌 단축키로 빠르게 기록하고, 전문 검색과 서버 연동 증류 큐를 제공합니다.

`Tauri` `Svelte 5` `Rust` `SQLite`

### [Distillery Server](https://github.com/Cognito-Distillery/Distillery-server)

엔진. 큐에 담긴 생각을 받아 임베딩을 생성하고, AI로 관계를 추출하여 지식 그래프를 구축합니다. 정오와 자정에 증류를 실행하며, 주간 백필로 고립된 지식이 없도록 합니다.

`Elysia` `PostgreSQL + pgvector` `Neo4j` `OpenAI`

### [Blending Room](https://github.com/Cognito-Distillery/Distillery-web-dashboard)

웹 대시보드. AI가 캐스킹한 지식에 사람의 판단을 더하는 인터랙티브 그래프 탐색기. 관계를 탐색하고 다듬으며, 모든 사람의 편집은 AI 생성 연결과 함께 추적됩니다.

`SvelteKit` `Cytoscape.js` `Tailwind CSS`

<br>

## 라이선스

MIT
