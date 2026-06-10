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

---

> 모든 프로젝트는 영어 README·LICENSE·SECURITY 와 테스트를 갖춘 공개용으로 정리되어 있습니다.
