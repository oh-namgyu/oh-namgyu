# 안녕하세요 👋

**AI 코딩 에이전트를 실제 개발 워크플로우에 녹여 넣는 도구**를 만듭니다.
혼자 쓰는 스크립트로 끝내지 않고, 영어 문서·테스트·CI 를 갖춰 공개합니다.

모든 저장소 README 맨 위에 한글 요약이 있습니다. 전체 한국어 문서(`README_KOR.md`)가 있는 저장소는 그 문서로 바로 연결했습니다.

🗂️ 카드로 한눈에 보기 → [showfolio-nine.vercel.app](https://showfolio-nine.vercel.app) (새 저장소는 자동으로 추가됩니다)

---

## 🤖 AI 에이전트 협업·운영

| 프로젝트 | 한 줄 소개 | 스택 |
|---|---|---|
| [**agent-workboard**](https://github.com/oh-namgyu/agent-workboard/blob/main/README_KOR.md) | 여러 AI 에이전트가 같은 코드베이스를 동시에 작업할 때 충돌을 막는 claim 보드. `PreToolUse` 훅으로 "규약"을 "강제"로 끌어올림 | Node · Express · SQLite |
| [**claude-web-terminal**](https://github.com/oh-namgyu/claude-web-terminal/blob/main/README_KOR.md) | Claude Code 의 Agent View 를 브라우저 카드 UI 로. loopback+토큰+Origin 3중 보안 | Node · WebSocket · PTY |
| [**docfleet**](https://github.com/oh-namgyu/docfleet/blob/main/README_KOR.md) | 여러 컴퓨터에서 쓰는 AI 에이전트의 문서·메모리를 git 저장소 하나로 동기화하는 폴더 규약 + CLI. 자기 폴더만 쓰고 남의 폴더는 읽기 전용임을 커밋 직전에 강제 | Python · 의존성 0 |

## 🧩 Claude Code 기록·메모리·스킬

| 프로젝트 | 한 줄 소개 | 스택 |
|---|---|---|
| [**cc-memory-index**](https://github.com/oh-namgyu/cc-memory-index) | Claude Code 자동 메모리의 `MEMORY.md` 를 각 메모리 파일 frontmatter 에서 생성 — 로드 상한(200줄·25KB) 안에 항상 맞추고, Claude 가 손으로 넣은 줄도 잃지 않음. 링크·경합·충돌에 안전한 쓰기 | Python · Claude Code 플러그인 |
| [**cc-replay**](https://github.com/oh-namgyu/cc-replay) | Claude Code 세션 기록(`.jsonl`)을 재생 가능한 HTML 타임라인 한 장으로. 외부 요청 0, 비밀정보 마스킹 기본 ON | Python · 의존성 0 |
| [**cc-stats**](https://github.com/oh-namgyu/cc-stats) | 전체 세션 기록을 토큰·도구 분포·오류율·활동 히트맵 대시보드 HTML 한 장으로. 대화 내용은 담지 않고 JS 도 없음 | Python · 의존성 0 |
| [**agent-standup**](https://github.com/oh-namgyu/agent-standup) | 세션 기록과 `git log` 를 나란히 모아 붙여넣기용 스탠드업 리포트를 생성. AI-assisted 커밋을 구분해 보여줌 | Python · 의존성 0 |
| [**skill-forge**](https://github.com/oh-namgyu/skill-forge) | 스킬·커맨드 파일의 조용한 로드 실패(BOM, 깨진 frontmatter, 약한 트리거 설명)를 규칙 기반으로 잡아내는 린터 + 뼈대 생성 | Python · 의존성 0 |
| [**why-log**](https://github.com/oh-namgyu/why-log) | git 히스토리에서 설계 결정(ADR)을 역설계. 원문 인용이 직접 뒷받침할 때만 이유를 적고, 근거가 없으면 지어내지 않고 사람에게 물음 | Claude Code 플러그인 |

## 🧭 코드베이스·시스템 이해

| 프로젝트 | 한 줄 소개 | 스택 |
|---|---|---|
| [**codebase-context-mcp**](https://github.com/oh-namgyu/codebase-context-mcp/blob/main/README_KOR.md) | 저장소를 정적 분석해 AI 에이전트에게 "코드베이스 지도"(import 그래프·라우트·프론트↔백 연결)를 MCP 도구로 제공 | Node · MCP · Babel |
| [**codebase-dojo**](https://github.com/oh-namgyu/codebase-dojo/blob/main/README_KOR.md) | 답을 주지 않고 "왜?"를 캐묻는 소크라테스식 코드베이스 학습 스킬. AI 시대에 개발자가 코드의 감독자 자리를 지키게 함 | Claude Code 스킬 |
| [**cc-anatomy**](https://github.com/oh-namgyu/cc-anatomy/blob/main/README_KOR.md) · [데모](https://cc-anatomy.vercel.app) | Claude Code 의 에이전트 루프·슬래시 명령·훅·스킬을 입력을 바꿔가며 단계별 애니메이션으로 배우는 웹앱. 모든 스텝에 공식 문서 인용 | JS · 정적 사이트 |
| [**pipeline-anatomy**](https://github.com/oh-namgyu/pipeline-anatomy/blob/main/README_KOR.md) · [데모](https://pipeline-anatomy.vercel.app) | 실제 운영 중인 콘텐츠 자동화 파이프라인 3종의 아키텍처를 단계별 다이어그램과 설계 결정 카드로 해설하는 케이스 스터디(식별 정보는 전부 일반화) | JS · 정적 사이트 |

## 🔍 감사·검증·보안

| 프로젝트 | 한 줄 소개 | 스택 |
|---|---|---|
| [**pub-project-auditor**](https://github.com/oh-namgyu/pub-project-auditor/blob/main/README_KOR.md) | 노트북에 쌓인 모든 Git 저장소를 한 명령으로 AI 코드리뷰+보안감사 → 웹 대시보드 | Python · Claude Code CLI |
| [**web-audit-kit**](https://github.com/oh-namgyu/web-audit-kit/blob/main/README_KOR.md) | 대상 URL 을 비침습적으로 점검해 보안·UX·아키텍처·기능 QA 4관점 리포트 생성 | Node · Playwright |
| [**cross-verify-cli**](https://github.com/oh-namgyu/cross-verify-cli) | 코드를 작성한 모델이 직접 합격시키지 못하게 — 결정적 게이트(시크릿/라이선스) + 저자와 다른 모델의 독립 검증 | Node · LLM-agnostic |
| [**plandelta**](https://github.com/oh-namgyu/plandelta) | 계획서와 완료 보고서를 항목 단위로 대조해 지킨 것·부분·못 지킨 것·계획 외 추가분을 근거 인용과 함께 판정. 바뀐 항목만 재판정 | Python · LLM 선택형 |

## ⚙️ 로컬 개발 환경

| 프로젝트 | 한 줄 소개 | 스택 |
|---|---|---|
| [**launchdeck**](https://github.com/oh-namgyu/launchdeck) | macOS 개인 LaunchAgent 를 표 하나로 보고 기억하기 쉬운 동사로 관리하는 CLI(`ldm`). 쓰기는 전부 백업 우선 트랜잭션 | Python · 의존성 0 |
| [**portdeck**](https://github.com/oh-namgyu/portdeck) | 코드가 선언한 포트를 근거(파일:줄)와 함께 찾아 등록부를 만들고, 실제 점유 프로세스와 대조해 충돌·표류를 진단. 서비스 간 호출 그래프까지 | Python · 의존성 0 |

## ✍️ 콘텐츠 생성 스튜디오

| 프로젝트 | 한 줄 소개 | 스택 |
|---|---|---|
| [**loreforge**](https://github.com/oh-namgyu/loreforge/blob/main/README_KOR.md) | 한 줄 컨셉 → 캐릭터·세계관 설정집(성격·대사·컬러 팔레트·마스터 이미지 프롬프트). 선택적 비주얼 보드 렌더, 단일 HTML 내보내기 | Python · Flask · LLM |
| [**sketchforge**](https://github.com/oh-namgyu/sketchforge/blob/main/README_KOR.md) | 한 줄 의도 → LLM 이 Mermaid 다이어그램 초안 → 말로 수정 반복(diff 미리보기·버전 관리) → SVG/PNG. API 키 없이도 Mermaid 편집기로 동작 | Python · Flask · Mermaid |
| [**janusline**](https://github.com/oh-namgyu/janusline/blob/main/README_KOR.md) | 검색어 하나로 뉴스 양면 타임라인 — 왼쪽 긍정·오른쪽 부정 기사, 양측 서사 종합과 근거 인용 IF 시나리오. 키 없는 RSS 수집 | Python · Flask · LLM |
| [**walkforge**](https://github.com/oh-namgyu/walkforge) | 상태 기계 명세(JSON) → 한 단계씩 눌러가며 따라가는 단일 HTML 워크스루. 네트워크 요청 0, LLM 초안 생성은 선택 | Python · 의존성 0 |
| [**songforge**](https://github.com/oh-namgyu/songforge) | 토픽 한 줄 → AI 작사 → ACE-Step 음악·보컬 → 후렴 탐지 → 9:16+16:9 영상 → 업로드 플랜까지 한 번에 | Python · CLI · ACE-Step |

## 🎨 앱·토이

| 프로젝트 | 한 줄 소개 | 스택 |
|---|---|---|
| [**taskdeck**](https://github.com/oh-namgyu/taskdeck) | AI 비서의 할일(칸반)을 분리한 자가호스팅 보드. 코어 칸반 + experimental Claude 러너(보안 하드닝) | Python · Flask |
| [**sealboard**](https://github.com/oh-namgyu/sealboard) | 내 서버에 띄우는 스티커 메모판 — 메모·이미지를 브라우저에서만 암호화·복호화하고 서버엔 암호문만 남김. 영지식 인증·키 회전·로컬 클라이언트 모드 | Python · Flask · WebCrypto |
| [**showfolio**](https://github.com/oh-namgyu/showfolio/blob/main/README_KOR.md) · [데모](https://showfolio-nine.vercel.app) | GitHub 계정명 하나로 공개 저장소를 런타임에 불러와 카드로 보여주는 정적 쇼케이스. 새 저장소는 재배포 없이 자동 편입, README 한글 요약 파싱 | JS · 무빌드 |
| [**prompt-rocket**](https://github.com/oh-namgyu/prompt-rocket) | 브라우저에서 복셀 로켓을 충전·발사해 날리는 작은 토이 | Three.js · WebGL |
| [**kids-coloring**](https://github.com/oh-namgyu/kids-coloring) · [데모](https://kids-coloring-demo.vercel.app) | 3~6세 유아용 터치 색칠놀이 PWA — 84개 도안·반짝이 펜·데칼코마니, 백엔드 없이 오프라인 동작 | Vite · TS · Canvas |

---

> 모든 프로젝트는 영어 README·LICENSE·SECURITY·테스트·CI 를 갖춘 공개용으로 정리되어 있습니다.

---

## 🌐 In English

Tools that fold AI coding agents into real development workflows — each shipped with English docs, tests, and CI. Every README opens with a Korean summary. Browse them as cards at [showfolio-nine.vercel.app](https://showfolio-nine.vercel.app).

#### AI agent collaboration & operations

| Project | One-liner | Stack |
|---|---|---|
| [**agent-workboard**](https://github.com/oh-namgyu/agent-workboard) | A claim board that stops multiple AI agents from clobbering each other in one codebase — a `PreToolUse` hook turns the convention into enforcement | Node · Express · SQLite |
| [**claude-web-terminal**](https://github.com/oh-namgyu/claude-web-terminal) | Claude Code's Agent View as a browser card UI, with loopback + per-start token + Origin checks | Node · WebSocket · PTY |
| [**docfleet**](https://github.com/oh-namgyu/docfleet) | Keep AI-agent docs and memory in sync across your machines with one git repo — a layout convention plus a CLI that enforces "write your own folder, read everyone else's" | Python · zero-dep |

#### Claude Code sessions, memory & skills

| Project | One-liner | Stack |
|---|---|---|
| [**cc-memory-index**](https://github.com/oh-namgyu/cc-memory-index) | Generates Claude Code's auto-memory `MEMORY.md` from each memory file's frontmatter — always within the load limit, without losing the lines Claude adds by hand; crash- and race-safe writes | Python · Claude Code plugin |
| [**cc-replay**](https://github.com/oh-namgyu/cc-replay) | Replay Claude Code sessions as a single self-contained HTML timeline — redaction on by default | Python · zero-dep |
| [**cc-stats**](https://github.com/oh-namgyu/cc-stats) | Your Claude Code usage as a single-file HTML dashboard — tokens, tools, error rate, activity heatmap; zero JS | Python · zero-dep |
| [**agent-standup**](https://github.com/oh-namgyu/agent-standup) | Turn Claude Code transcripts + git history into a paste-ready standup report, with AI-assisted commits called out | Python · zero-dep |
| [**skill-forge**](https://github.com/oh-namgyu/skill-forge) | Lint Claude Code skills and commands for silent load failures (BOM, broken frontmatter, weak triggers) — plus scaffolding | Python · zero-dep |
| [**why-log**](https://github.com/oh-namgyu/why-log) | Reconstruct a repo's design decisions (ADRs) from git history — reasons only from verbatim evidence, questions instead of guesses | Claude Code plugin |

#### Understanding codebases & systems

| Project | One-liner | Stack |
|---|---|---|
| [**codebase-context-mcp**](https://github.com/oh-namgyu/codebase-context-mcp) | Static analysis as MCP tools — hands an AI agent a map of the repo (import graph, routes, frontend↔backend edges) | Node · MCP · Babel |
| [**codebase-dojo**](https://github.com/oh-namgyu/codebase-dojo) | A Socratic tutor for your codebase: asks *why* and never just tells you, so you stay the director not the operator | Claude Code skill |
| [**cc-anatomy**](https://github.com/oh-namgyu/cc-anatomy) · [demo](https://cc-anatomy.vercel.app) | Interactive step-by-step simulations of how Claude Code runs — agent loop, slash commands, hooks, skills; every step cites the official docs | JS · static |
| [**pipeline-anatomy**](https://github.com/oh-namgyu/pipeline-anatomy) · [demo](https://pipeline-anatomy.vercel.app) | An interactive case study of three real content-automation pipelines — animated diagrams and design-decision cards, fully generalized | JS · static |

#### Audit, verification & security

| Project | One-liner | Stack |
|---|---|---|
| [**pub-project-auditor**](https://github.com/oh-namgyu/pub-project-auditor) | Audit every Git repo on your laptop with one command — AI code review + security audit → dashboard | Python · Claude Code CLI |
| [**web-audit-kit**](https://github.com/oh-namgyu/web-audit-kit) | Non-invasive site audit reporter across security, UX, architecture, and functional QA | Node · Playwright |
| [**cross-verify-cli**](https://github.com/oh-namgyu/cross-verify-cli) | Pre-publish verification where the model that wrote the code is never the one that approves it — deterministic gate + an independent second-model review | Node · LLM-agnostic |
| [**plandelta**](https://github.com/oh-namgyu/plandelta) | Compare a plan document against what actually shipped, item by item, with cited evidence — re-judges only what changed | Python · pluggable LLM |

#### Local dev environment

| Project | One-liner | Stack |
|---|---|---|
| [**launchdeck**](https://github.com/oh-namgyu/launchdeck) | A CLI (`ldm`) for your personal macOS launchd agents — one-screen status, humane verbs, backup-first transactions | Python · zero-dep |
| [**portdeck**](https://github.com/oh-namgyu/portdeck) | A registry and map for your local dev ports — discover them from source, see who actually holds them, graph how services call each other | Python · zero-dep |

#### Content studios

| Project | One-liner | Stack |
|---|---|---|
| [**loreforge**](https://github.com/oh-namgyu/loreforge) | One-line concept → a character & world bible with palette, signature lines and a master image prompt; optional visual board, single-HTML export | Python · Flask · LLM |
| [**sketchforge**](https://github.com/oh-namgyu/sketchforge) | A self-hosted Mermaid studio — an LLM drafts the diagram, you refine it conversationally with diff previews and version history; works keyless as a live editor | Python · Flask · Mermaid |
| [**janusline**](https://github.com/oh-namgyu/janusline) | Both sides of the story — a dual-sided news timeline with a two-sided synthesis and cited IF scenarios; keyless RSS collection | Python · Flask · LLM |
| [**walkforge**](https://github.com/oh-namgyu/walkforge) | Turn a state-machine spec into a self-contained interactive walkthrough HTML, with optional LLM drafting | Python · zero-dep |
| [**songforge**](https://github.com/oh-namgyu/songforge) | One topic → AI lyrics → ACE-Step music/vocals → chorus detection → 9:16 + 16:9 video → upload plan | Python · CLI |

#### Apps & toys

| Project | One-liner | Stack |
|---|---|---|
| [**taskdeck**](https://github.com/oh-namgyu/taskdeck) | A self-hosted Kanban board split out from an AI secretary — core kanban + an experimental, security-hardened Claude runner | Python · Flask |
| [**sealboard**](https://github.com/oh-namgyu/sealboard) | A self-hosted sticky-note board whose notes and images are encrypted in your browser — the server only stores ciphertext; zero-knowledge login, key rotation, local client mode | Python · Flask · WebCrypto |
| [**showfolio**](https://github.com/oh-namgyu/showfolio) · [demo](https://showfolio-nine.vercel.app) | A static portfolio that loads your public GitHub repos at runtime — new repos appear with no rebuild; parses each README's Korean summary for bilingual cards | JS · no build |
| [**prompt-rocket**](https://github.com/oh-namgyu/prompt-rocket) | A tiny browser toy — charge and launch a voxel rocket and watch it fly | Three.js · WebGL |
| [**kids-coloring**](https://github.com/oh-namgyu/kids-coloring) · [demo](https://kids-coloring-demo.vercel.app) | A touch coloring PWA for young kids (ages 3–6) — 84 outlines, sparkle pens, mirror mode; no backend, works offline | Vite · TS · Canvas |
