# 데이터 엔지니어링

속성: Architecture


<details>
<summary><strong>주변에 이걸로 데이터 사이언스에 입문해서 기초를 탄탄히 잡은 분도 있어요.</strong></summary>


📘 마이크로소프트 무료 > 초보자를 위한 데이터 과학 - 커리큘럼  
[https://github.com/microsoft/Data-Science-For-Beginners/blob/main/translations/ko/README.md](https://github.com/microsoft/Data-Science-For-Beginners/blob/main/translations/ko/README.md)

Data Science for Beginners..  
이건 10주 / 20개 레슨 구성의 완전 무료 커리큘럼이예요.

한국어도 잘 제공되고 있어서 더 좋으실 거예요. 커리큘럼 구성도 깔끔..

- 데이터 사이언스란 무엇인가 / 윤리
- SQL, NoSQL, Pandas로 데이터 다루기
- Matplotlib 중심의 시각화
- 데이터 사이언스 라이프사이클
- Azure 클라우드 활용
- 실제 프로젝트까지

각 레슨마다 퀴즈, 실습, 과제, 솔루션이 다 들어있어서,,

그냥 읽고 끝나는 게 아니라 손으로 해보면서 배우는 구조..

데이터 사이언스 쪽 무료 고퀄리티 자료 참고해보시길~~

첨부한 로드맵도 참고하세요!


</details>

---


<details>
<summary><strong>데이터 사이언스 궁금하거나 좀 더 깊게 파보고 싶은 분들은 여기도 좋음.</strong></summary>


모두 무료 고퀄리티 강의..  
[https://boostcourse.org/opencourse](https://boostcourse.org/opencourse)

- [MIT] 데이터 사이언스 기초
- 파이썬으로 시작하는 데이터 사이언스
- AI로 핵심 데이터를 모아 한눈에 파악하기
- 모두를 위한 데이터 사이언스
- 데이터 시각화를 위한 태블로
- 기초 데이터 분석을 위한 핵심 SQL
- Hello, 데이터 사이언스!
- DataLit : 데이터다루기
- 캐글 실습으로 배우는 데이터 사이언스
- 프로젝트로 배우는 데이터사이언스


</details>

---


<details>
<summary><strong>데이터 엔지니어링을 처음 시작하는 사람부터 실무자까지..</strong></summary>


📕 데이터 엔지니어링 핸드북  
[https://github.com/DataExpert-io/data-engineer-handbook](https://github.com/DataExpert-io/data-engineer-handbook)

데이터 엔지니어가 되기 위해 필요한 모든 자료를 한곳에 모아놓은 큐레이션 저장소.

```java
data-engineer-handbook/
├ 4주 무료 입문 부트캠프 자료
├ 6주 무료 중급 부트캠프 자료
├ Databricks AI 부트캠프 자료
├ 추천 도서 25권+
├ 커뮤니티 10개+
├ 실습용 무료 프로젝트 목록
├ 인터뷰 대비 자료
└ 뉴스레터 목록
```

코드보다는 로드맵 + 학습 리소스 링크를 많이 제안하고 있죠.

백서, 필독서, 커뮤니티, 블로그, 소셜... 아 정말 많음.


</details>

---


<details>
<summary><strong>AI를 공부하다 보면 '데이터 엔지니어'라는 직업을</strong></summary>

자주 보게 됩니다.

쉽게 말하면, AI나 데이터 분석에 필요한 데이터를  
모으고, 정리하고, 전달하는 시스템을  
만드는 사람입니다.

The Data Engineering Handbook은  
이 분야를 처음 배우는 사람을 위한  
오픈소스 학습 자료입니다.

무엇부터 공부해야 하는지,  
어떤 기술을 익혀야 하는지,  
순서대로 정리해 두었습니다.  
기초 학습부터  
실무 프로젝트,  
면접 준비 자료까지  
한곳에서 살펴볼 수 있습니다.  
특히 AI를 활용하다가  
"데이터는 어디서 오고  
어떻게 관리되는 걸까?"  
궁금했던 분들에게  
좋은 출발점이 될 수 있는 자료입니다.

[https://github.com/DataExpert-io/data-engineer-handbook](https://github.com/DataExpert-io/data-engineer-handbook)


</details>

---


<details>
<summary><strong>AI 엔지니어로서 Top-k와 Top-p의 차이를 아시나요?</strong></summary>


90%가 "둘 다 후보 잘라내는 거 아닌가요"에서 멈춥니다.  
마트 진열대로 비유하면 끝납니다 👇

A. Top-k  
→ 무조건 상위 5개만 올리는 진열대  
→ 1등이 압도적이든 다 고만고만하든 항상 5칸입니다  
→ LLM 디코딩에서 확률 상위 k개만 남깁니다. 남기는 개수가 고정입니다

B. Top-p  
→ 매출 누적 90%까지만 채우는 진열대  
→ 1등이 압도적이면 2칸, 다 비슷하면 30칸이 됩니다  
→ LLM 디코딩에서 누적 확률이 p에 닿을 때까지만 남깁니다. 개수가 매번 달라집니다

A는 개수,  
B는 비중.

Top-k는 몇 개를 남길지 미리 정하고, Top-p는 분포를 보고 몇 개를 남길지 그때그때 정합니다.

![image.png](../assets/data-engineering/image-121.png)
</details>

---


<!-- devtrack-draft-id: a0d0558e-c586-4774-a8f6-9d1b84147193 -->
<details>
<summary><strong>기술적 해자는 이 시점에서 대부분 사라졌습니다.</strong></summary>

내구성을 목표로 무언가를 구축하고 있다면, 이제 남은 유일한 해자는 다음과 같습니다:

- 독점 데이터  
- 네트워크 효과  
- 물리적 구성 요소

</details>

---

<!-- devtrack-draft-id: 1cd2e995-7d0e-4694-84b0-4a71c26f4c43 -->
<details>
<summary><strong>엔지니어가 &quot;성능 개선에서 가장 먼저 확인하는 곳&quot; 5선</strong></summary>

- DB 쿼리」 → 대체로 여기
- N+1 문제」 → 흔함
- 캐시」 → 효과 큼
- 불필요한 처리」 → 의외로 많음
- 네트워크」 → 간과하기 쉬움

</details>

---

<!-- devtrack-draft-id: 5196edc8-a6e7-47f1-821c-ce37cb4ac4f8 -->
<details>
<summary><strong>아, 이제는 데이터를 잘 다루는 것만으로는 부족하겠구나</strong></summary>

결국 데이터를 지지고 볶아 내 것으로 만들고, 그 안에서 나만의 해석과 인사이트를 뽑아내는 능력이 중요한 것 같다.

숫자를 뽑고, 유형을 나누고, 패턴을 찾는 건 AI가 점점 더 잘해줄 텐데 그 결과를 보고 무엇을 느끼고, 어떻게 판단하고, 실제 행동을 바꿀지는 결국 내 몫이니까.

문제는 매일 쏟아지는 업무를 쳐내는 것만으로도 벅찬데, 그 와중에 분석을 넘어 나만의 관점까지 만들어야 한다는 거다. 시키는 일만 잘해서는 부족하고, 그렇다고 바쁘게 일한다고 반드시 경쟁력이 쌓이는 것도 아니니.

결국 내가 쌓아야 하는 건 데이터를 다루는 기술만이 아니라, 그 데이터에서 의미를 발견하고 내 경험과 판단을 더해 실제 가치를 만들어내는 힘인 것 같다.

열심히 일하는 사람을 넘어, 내가 했기 때문에 만들어진 가치가 있는 사람.

직장인으로서 갈수록 그게 참 어렵고도 중요하게 느껴진다.

</details>

---

<!-- devtrack-draft-id: c8a63f67-125b-49a5-9317-dcff11eff0a1 -->
<details>
<summary><strong>AI 데이터센터의 “신경계 모니터링 시스템”</strong></summary>

RELIANT가 하는 일

데이터센터 전체 인터커넥트를 실시간으로 모니터링하는 플랫폼

광모듈, 전기모듈, PCIe 리타이머까지 랙 내부 + 랙 간 연결 전체를 커버

Fleet 대시보드 — 네트워크 전체 건강 상태를 한눈에 파악, 개별 링크까지 드릴다운 가능

토폴로지 뷰 — 랙 간 시스템 연결 구조를 시각화, 성능 저하 전에 문제 지점 사전 식별

Marvell이 칩 회사에서 AI 인프라 플랫폼 회사로 진화하고 있다는 신호입니다.

</details>

---

<!-- devtrack-draft-id: 5a463f67-ed67-413e-83eb-0f3d1a4bc859 -->
<details>
<summary><strong>드릴다운 분석(Drill Down Analysis ) = 문제를 여럿으로 세분화하면서 분석하는 기법</strong></summary>

• 핵심 개념: 롤업(Roll-up, 데이터를 상위 수준으로 요약)의 정반대 개념입니다.  
• 분석 방식: 큰 범주에서 출발해 점차 세부 기준(계층)으로 데이터를 쪼개어 들어갑니다.  
• 주요 활용 툴: 엑셀 피벗테이블, 태블로(Tableau), 파워BI(Power BI), 구글 로커 스튜디오(Looker Studio) 등.  
• 사용자가 자연어로 단 한 줄의 질문을 던졌을 때, AI가 대시보드나 데이터베이스의 상위 요약 정보에 머무르지 않고 하위 계층(세부 구성 요소, 원인, 데이터 레이블)으로 스스로 파고들며 분석해 주는 지능형 대화 시스템  
• 자연어 기반 자동 탐색: "이번 달 매출이 떨어진 이유는?" 같은 한 줄 질문만으로도 AI가 내부 데이터나 온톨로지(Ontology, 지식 기반 인과 맵핑)를 타고 스스로 세부 항목을 추적합니다.  
• 계층형 워크플로우: 거시적인 지표(예: 전체 매출, 시스템 에러율)에서 중간 카테고리(예: 특정 지역, 마이크로서비스 모듈), 최종 원인 데이터(예: 특정 서버 로그, 사용자 그룹)까지 단계적으로 내려갑니다.  
• 대화형 시각화 전환: 단순 텍스트 답변뿐만 아니라, 질문에 맞춰 에이전트가 실시간으로 차트나 대시보드(A2UI 패러다임 등)를 구성해 보여주기도 합니다.  
• 기업 데이터 및 비즈니스 분석: BI(Business Intelligence) 툴과 결합하여 복잡한 숫자 뒤의 진짜 원인과 인사이트를 대화하듯 찾아냅니다. 예: 스마트리온 AXIS의 자동 드릴다운  
• IT 시스템 및 MSA(마이크로서비스) 모니터링: 장애가 발생했을 때 챗봇에게 물어보면 전체 시스템 상태에서 특정 서버, 컨테이너, API 에러 로그까지 계층적으로 파고들어 원인을 진단합니다.  
• 클라우드 데이터 및 렌탈 관리: Amazon Quick 같은 지능형 분석 에이전트를 통해 전문 지식 없이도 자연어로 데이터 계층을 탐색합니다.

</details>

---
