<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img src="assets/header.svg" width="100%" alt="Daeheum Cho — AI service development. Build, connect, verify.">
</picture>

<p align="center">
  <strong>AI 서비스를 만들고, 실제 동작을 검증하는 개발자를 지향합니다.</strong><br>
  서강대학교 미국문화 전공 · 인공지능 연계전공
</p>

<p align="center">
  <a href="https://damisoda.github.io/">Portfolio</a>&nbsp;&nbsp; / &nbsp;&nbsp;
  <a href="mailto:jodaeheum800@gmail.com">Email</a>&nbsp;&nbsp; / &nbsp;&nbsp;
  <a href="https://github.com/damisoda?tab=repositories">Repositories</a>
</p>

LLM을 데이터·API·사용자 화면과 연결하는 프로젝트를 진행하고 있습니다.
최근에는 **모델의 역할 분리, 실패 처리, 재현 가능한 평가**를 공부하고 있습니다.

## Selected projects

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/damisoda/design-qa-agent"><img src="assets/dqa.svg" width="100%" alt="dqa — 디자인 검수·수정 에이전트"></a>
      <p>Figma 기준과 구현 화면을 비교하고, 모델의 코드 수정을 사본에서 재검증합니다.</p>
      <p><strong>개인 프로젝트</strong> · Dify·브라우저 측정·로컬 LLM 연결</p>
      <p><a href="https://github.com/damisoda/design-qa-agent/blob/main/docs/performance-20261021.md">검증 기록</a> · 같은 통제 사례 전후 각 3회, 실행 시간 중앙값 143.8초 → 98.8초. 화면 크기 5개를 유지했습니다.</p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Donghaeng-AI-ROOKIE/Come-back-home"><img src="assets/cbh.svg" width="100%" alt="돌아오길 — 개인화 동선 예측·수색 지원"></a>
      <p>생활사·수색 통계·도로망으로 위치 확률지도를 만들고, 해당 구역 시민의 제보를 받습니다.</p>
      <p><strong>팀 프로젝트</strong> · EXAONE LoRA 학습·서빙, 예측·알림 흐름 통합과 화면 검증에 참여</p>
      <p>2026 인공지능 루키대회 <strong>1차 결선 진출</strong><br><a href="https://github.com/Donghaeng-AI-ROOKIE/Come-back-home/pull/367">예측 접수 실패 처리 PR</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Geek-Sogang/Career-Piggybank"><img src="assets/piggybank.svg" width="100%" alt="커리어 저금통 — 긱워커 AI 생활금융"></a>
      <p>불규칙한 소득을 받는 긱워커의 커리어 이력·예산 배분·은퇴 준비를 연결합니다.</p>
      <p><strong>팀 프로젝트</strong> · FastAPI·Expo 서비스 구현과 데모 흐름, 봉투 UI·미션 개선에 참여</p>
      <p>하나 청년 금융인재 양성 프로젝트 <strong>우수상</strong><br><a href="https://github.com/Geek-Sogang/Career-Piggybank#readme">구조·AI 평가 기록</a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/damisoda/Dev-Hive"><img src="assets/dev-hive.svg" width="100%" alt="Dev-Hive — 지식그래프 기반 AI 학습 추천"></a>
      <p>AI 콘텐츠를 수집·태깅하고, 지식그래프와 검색으로 학습 콘텐츠를 추천합니다.</p>
      <p><strong>팀 리드</strong> · 콘텐츠 처리·추천 파이프라인, PR·티켓 관리와 Mac mini 배포</p>
      <p><a href="https://github.com/damisoda/Dev-Hive#readme">구현 상태·평가 기록</a><br>GraphSAGE는 학습 파이프라인까지만 구축했으며 추천에는 미반영했습니다.</p>
    </td>
  </tr>
</table>

## Other work

| 프로젝트 | 다룬 문제 |
|---|---|
| [Paper-Digest](https://github.com/damisoda/Paper-Digest) | 논문 수집 → 로컬 요약 → Obsidian·Discord 자동화. AI 코딩 도구와 함께 구현한 개인 프로젝트 |
| [LearnCraft](https://github.com/damisoda/LearnCraft-quiz_generator) | 인턴십에서 퀴즈 생성 파이프라인·난이도 선택·코드 완성형 퀴즈·자동 채점 구현 참여 |
| [LOVELOP agent simulator](https://github.com/damisoda/LOVELOP-commercial-agent-simulator) | 생성형 에이전트 상권 시뮬레이션의 비동기 실행과 전략 전후 비교 |
| [text-recovery](https://github.com/damisoda/text-recovery) | 자모 분리와 KoBART 기반 한국어 텍스트 복원 팀 프로젝트 |
| [Paw Patrol Network](https://github.com/damisoda/TECH4GOOD_Hackerthon) | 보도·점자블록 파손 탐지와 민원 문안 생성 해커톤 프로젝트 |

## Technologies used in projects

| AI | Service | Data & delivery |
|---|---|---|
| PyTorch · Hugging Face · LoRA | Python · FastAPI | PostgreSQL · pgvector |
| vLLM · Ollama · RAG | JavaScript·TypeScript · Next.js · Expo | SQLite · Docker · GitHub Actions |

## Activity & recognition

| 기간 | 활동 | 역할·결과 |
|---|---|---|
| 2026.03–현재<br>2026.12 종료 예정 | [서강대학교 경영데이터사이언스학회 INSIGHT](https://insight.oopy.io/) | **15기 · 교육팀** / Dev-Hive 팀 리드 |
| 2026.07 | 하나 청년 금융인재 양성 프로젝트 · 커리어 저금통 | **우수상** · 팀 짱사이트 |
| 2026 | 인공지능 루키대회 · 돌아오길 | **1차 결선 진출** · 팀 동행 · 활동 종료 |
| 2026.03–04 | 멋사 로켓단 인턴십 · LearnCraft | 퀴즈 생성·자동 채점 구현 참여 |
| 2025.12–2026.02 | 멋쟁이사자처럼 AI NLP 3기 | NLP·생성형 에이전트 팀 프로젝트 |

INSIGHT에서는 데이터 분석·ML/DL 정규세션과 교육팀 활동에 참여하고 있습니다.
Dev-Hive에서는 콘텐츠 처리·추천 파이프라인과 팀 협업을 진행했습니다.

[공식 회원 명단](https://insight.oopy.io/ecbeedca-f6b1-40aa-b6e4-990ab94179e1) · [학회 프로젝트 소개](https://insight.oopy.io/8a312ab9-7d49-49c3-95e2-bf2ad786af2c) · [하나 프로젝트 수상 기록](https://insight.oopy.io/a87f8c6b-2a84-4478-9c67-626820a4ec29)

AI 코딩 도구를 활용하며, 설계 선택과 실행·평가 결과를 문서로 남기고 있습니다.

<details>
  <summary>A little off duty</summary>
  <p align="center"><a href="https://github.com/git-goods/gitanimals"><img src="https://render.gitanimals.org/farms/damisoda" width="600" alt="damisoda's Git Animals"></a></p>
</details>
