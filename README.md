# 안녕하세요 👋

**AI 코딩 에이전트를 실제 개발 워크플로우에 녹여 넣는 도구**를 만듭니다.
혼자 쓰는 스크립트로 끝내지 않고, 영어 문서·테스트·CI 를 갖춰 공개합니다.

각 저장소에는 한국어 소개(`README_KOR.md`)가 함께 있습니다.

---

## 🤖 AI 에이전트 협업·운영 도구

| 프로젝트 | 한 줄 소개 | 스택 |
|---|---|---|
| [**agent-workboard**](https://github.com/oh-namgyu/agent-workboard/blob/main/README_KOR.md) | 여러 AI 에이전트가 같은 코드베이스를 동시에 작업할 때 충돌을 막는 claim 보드. `PreToolUse` 훅으로 "규약"을 "강제"로 끌어올림 | Node · Express · SQLite |
| [**claude-web-terminal**](https://github.com/oh-namgyu/claude-web-terminal/blob/main/README_KOR.md) | Claude Code 의 Agent View 를 브라우저 카드 UI 로. loopback+토큰+Origin 3중 보안 | Node · WebSocket · PTY |

## 🧭 코드베이스 이해·학습

| 프로젝트 | 한 줄 소개 | 스택 |
|---|---|---|
| [**codebase-context-mcp**](https://github.com/oh-namgyu/codebase-context-mcp/blob/main/README_KOR.md) | 저장소를 정적 분석해 AI 에이전트에게 "코드베이스 지도"(import 그래프·라우트·프론트↔백 연결)를 MCP 도구로 제공 | Node · MCP · Babel |
| [**codebase-dojo**](https://github.com/oh-namgyu/codebase-dojo/blob/main/README_KOR.md) | 답을 주지 않고 "왜?"를 캐묻는 소크라테스식 코드베이스 학습 스킬. AI 시대에 개발자가 코드의 감독자 자리를 지키게 함 | Claude Code 스킬 |

## 🔍 감사·보안

| 프로젝트 | 한 줄 소개 | 스택 |
|---|---|---|
| [**pub-project-auditor**](https://github.com/oh-namgyu/pub-project-auditor/blob/main/README_KOR.md) | 노트북에 쌓인 모든 Git 저장소를 한 명령으로 AI 코드리뷰+보안감사 → 웹 대시보드 | Python · Claude Code CLI |
| [**web-audit-kit**](https://github.com/oh-namgyu/web-audit-kit/blob/main/README_KOR.md) | 대상 URL 을 비침습적으로 점검해 보안·UX·아키텍처·기능 QA 4관점 리포트 생성 | Node · Playwright |
| [**cross-verify-cli**](https://github.com/oh-namgyu/cross-verify-cli/blob/main/README_KOR.md) | 코드를 작성한 모델이 직접 합격시키지 못하게 — 결정적 게이트(시크릿/라이선스) + 저자와 다른 모델의 독립 검증 | Node · LLM-agnostic |

## 🛠️ 앱·콘텐츠·토이

| 프로젝트 | 한 줄 소개 | 스택 |
|---|---|---|
| [**taskdeck**](https://github.com/oh-namgyu/taskdeck) | AI 비서의 할일(칸반)을 분리한 자가호스팅 보드. 코어 칸반 + experimental Claude 러너(보안 하드닝) | Python · Flask |
| [**songforge**](https://github.com/oh-namgyu/songforge) | 토픽 한 줄 → AI 작사 → ACE-Step 음악·보컬 → 후렴 탐지 → 9:16+16:9 영상 → 업로드 플랜까지 한 번에 | Python · CLI · ACE-Step |
| [**prompt-rocket**](https://github.com/oh-namgyu/prompt-rocket) | 브라우저에서 복셀 로켓을 충전·발사해 날리는 작은 토이 | Three.js · WebGL |
| [**kids-coloring**](https://github.com/oh-namgyu/kids-coloring) | 3~6세 유아용 터치 색칠놀이 PWA — 84개 도안·반짝이 펜·데칼코마니, 백엔드 없이 오프라인 동작 | Vite · TS · Canvas |

---

> 모든 프로젝트는 영어 README·LICENSE·SECURITY 와 테스트를 갖춘 공개용으로 정리되어 있습니다.

---

## 🌐 In English

Tools that fold AI coding agents into real development workflows — each shipped with English docs, tests, and CI. Korean intro (`README_KOR.md`) lives in every repo.

| Project | One-liner | Stack |
|---|---|---|
| [**agent-workboard**](https://github.com/oh-namgyu/agent-workboard) | A claim board that stops multiple AI agents from clobbering each other in one codebase — a `PreToolUse` hook turns the convention into enforcement | Node · Express · SQLite |
| [**claude-web-terminal**](https://github.com/oh-namgyu/claude-web-terminal) | Claude Code's Agent View as a browser card UI, with loopback + per-start token + Origin checks | Node · WebSocket · PTY |
| [**codebase-context-mcp**](https://github.com/oh-namgyu/codebase-context-mcp) | Static analysis as MCP tools — hands an AI agent a map of the repo (import graph, routes, frontend↔backend edges) | Node · MCP · Babel |
| [**codebase-dojo**](https://github.com/oh-namgyu/codebase-dojo) | A Socratic tutor for your codebase: asks *why* and never just tells you, so you stay the director not the operator | Claude Code skill |
| [**pub-project-auditor**](https://github.com/oh-namgyu/pub-project-auditor) | Audit every Git repo on your laptop with one command — AI code review + security audit → dashboard | Python · Claude Code CLI |
| [**web-audit-kit**](https://github.com/oh-namgyu/web-audit-kit) | Non-invasive site audit reporter across security, UX, architecture, and functional QA | Node · Playwright |
| [**cross-verify-cli**](https://github.com/oh-namgyu/cross-verify-cli) | Pre-publish verification where the model that wrote the code is never the one that approves it — deterministic gate + an independent second-model review | Node · LLM-agnostic |
| [**taskdeck**](https://github.com/oh-namgyu/taskdeck) | A self-hosted Kanban board split out from an AI secretary — core kanban + an experimental, security-hardened Claude runner | Python · Flask |
| [**songforge**](https://github.com/oh-namgyu/songforge) | One topic → AI lyrics → ACE-Step music/vocals → chorus detection → 9:16 + 16:9 video → upload plan | Python · CLI |
| [**prompt-rocket**](https://github.com/oh-namgyu/prompt-rocket) | A tiny browser toy — charge and launch a voxel rocket and watch it fly | Three.js · WebGL |
| [**kids-coloring**](https://github.com/oh-namgyu/kids-coloring) | A touch coloring PWA for young kids (ages 3–6) — 84 outlines, sparkle pens, mirror mode; no backend, works offline | Vite · TS · Canvas |
