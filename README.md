# 조대흠

서강대학교에서 미국문화와 인공지능을 공부하고 있습니다. LLM을 서비스에 연결하면서 모델에 맡길 판단과 코드로 검증할 부분을 나눠 설계해 왔습니다.

[포트폴리오 PDF](https://damisoda.github.io/portfolio.pdf)　[이력서 PDF](https://damisoda.github.io/resume.pdf)　[웹 포트폴리오](https://damisoda.github.io/)　[이메일](mailto:jodaeheum800@gmail.com)

## 대표 프로젝트

### [돌아오길](https://damisoda.github.io/projects/come-back-home/)

보호자의 설명과 시민 제보를 수색 구역 계산에 반영하는 서비스입니다. 6인 팀의 개발 팀장으로 모델 역할 분리, LoRA 학습과 서빙, 배포 후 운영을 맡았습니다.

신규 모델의 혼란도 평가가 100%로 나와 채점 코드를 확인했습니다. 평가기는 서비스 규칙이 보정한 결과를 채점하고 있었습니다. 저장된 모델 원응답 32건을 다시 채점하니 정확도는 75%였고, 항상 ‘중’으로 답하는 단순 기준은 88%였습니다. 이 결과를 근거로 혼란도 계산에는 기존 규칙을 유지하고, 평가 리포트에는 원응답 점수와 단순 기준을 함께 표시했습니다.

인공지능 루키대회 국내 AI 트랙 1차 결선 진출

[저장소](https://github.com/Donghaeng-AI-ROOKIE/Come-back-home)　[평가기 수정](https://github.com/Donghaeng-AI-ROOKIE/Come-back-home/pull/144)　[앱 실행 검증](https://github.com/Donghaeng-AI-ROOKIE/Come-back-home/blob/main/docs/verification/app-flow-20261010/README.md)

### [Dev-Hive](https://damisoda.github.io/projects/dev-hive/)

흩어진 AI 자료를 주제와 선행관계로 묶어 학습자가 다음에 읽을 글을 추천하는 서비스입니다. 팀 리드로 콘텐츠의 그래프 편입과 추천 흐름을 설계했습니다.

새 글마다 주제 노드가 생겨 관련 자료가 흩어졌습니다. 기존 주제에 먼저 편입하고 남은 글을 묶어 새 주제를 만드는 2패스 구조로 바꿨습니다. 콘텐츠 924건을 재구축했을 때 자동 생성 주제는 825개에서 24개로 줄었습니다. 이후 새 소스가 들어오면서 유사도 분포가 달라지는 문제에는 주제별 동적 임계값을 적용해 비교했습니다. 별도의 902건 시간순 유입 실험에서 기존 주제에 편입되지 않아 후속 군집화로 넘어간 글은 717건에서 534건으로 줄었습니다.

[저장소](https://github.com/damisoda/Dev-Hive)　[2패스 구조](https://github.com/damisoda/Dev-Hive/pull/45)　[동적 임계값 실험](https://github.com/damisoda/Dev-Hive/pull/89)

### [커리어 저금통](https://damisoda.github.io/projects/career-piggybank/)

입금이 불규칙한 긱워커에게 예산 배분을 제안하는 생활금융 데모입니다. 4인 팀의 개발 담당으로 Expo 앱, FastAPI 백엔드와 로컬 모델을 연결했습니다.

로컬 모델이 거래 기록에서 인용한 근거와 반대 방향의 성향 점수를 내는 경우가 있었습니다. 백엔드에서 근거와 점수의 방향을 확인하고, 오류가 나면 이유를 전달해 한 번 교정한 뒤 재실패하면 판단을 보류하도록 구현했습니다. 합성 페르소나 13명의 성향 라벨 22개를 평가한 결과, 최종 구성은 방향 오류 0건, 판단 보류 8건이었습니다. 정확도는 63.6%로 같은 평가의 규칙 대조군 90.9%보다 낮았습니다.

하나 청년 금융인재 양성 프로젝트 우수상

[저장소](https://github.com/Geek-Sogang/Career-Piggybank)　[판독 교정 실험](https://github.com/Geek-Sogang/Career-Piggybank/pull/47)　[예제 데이터 데모](https://damisoda.github.io/demos/career-piggybank/)

## 인턴십

[LearnCraft](https://github.com/damisoda/LearnCraft-quiz_generator), 샤이닝라이언 인턴, 2026.03–04

강의 자료에서 퀴즈를 만드는 기능을 맡았습니다. 난이도별로 문항 유형을 지정하고, 생성 결과의 JSON 구조가 검증에 실패하면 오류 이유를 전달해 모델이 한 번 수정하도록 구현했습니다. Python과 SQL 답안은 Judge0로 실행해 기대 출력과 비교했습니다.
