# 소프트웨어

속성: Architecture


<details>
<summary><strong>API testing tool</strong></summary>

![image.png](../assets/api-testing/image-042.png)

Postman은 실제로 어떻게 돈을 벌고 있는 걸까?

모두가 무료로 사용하고 있는 걸 봐  
요청 보내기만 하고  
API 테스트만 하고

누가 돈 내는 걸 본 적 없어  
광고 하나도 본 적 없고

그럼 Postman은 어떻게 그 모든 인프라 비용을 충당하는 거지?

- 무료 → 개인 API 테스트
- 유료 → 팀 협업, 워크스페이스, 거버넌스
- 엔터프라이즈 → 보안, 감사 로그, 통합
- API 플랫폼 → 모킹, 모니터링, 문서
- 당신은 팀들이 고객이 아닙니다.
    - 개인들은 무료로 사용하지만, 회사들은 다음을 위해 비용을 지불합니다:
    1. 협업
    2. 공유 작업 공간
    3. 거버넌스 & 보안
    4. API 모니터링 & 테스트

![image.png](../assets/api-testing/image-043.png)

![image.png](../assets/api-testing/image-045.png)

---


</details>

---


<details>
<summary><strong>Bruno v3.5.0의 새로운 기능</strong></summary>

![image.png](../assets/api-testing/image-044.png)

- 컬렉션 실행을 위한 공식 GitHub Action
- CI/CD를 위한 공식 Bruno CLI Docker 이미지
- 더 나은 가져오기: 오류 컨텍스트, 종속성 검사, 대량 Git 저장소 가져오기
- `bru.sendRequest()` / `bru.runRequest()`가 이제 타임라인에 표시됩니다
- CLI의 `--bail` 및 HTML 보고서 수정
- 자동화를 위한 더 부드러운 API 워크플로우를 위해 제작되었습니다.

![image.png](../assets/api-testing/image-046.png)

---


</details>

---


<details>
<summary><strong>학습 곡선에 따른 테스트 도구 순위</strong></summary>


🟢 Postman — 쉬움  
🟢 Jest — 쉬움  
🟢 Vitest — 쉬움  
🟢 Testing Library — 쉬움  
🟢 Unit Testing — 쉬움

🔵 Cypress — 보통  
🔵 Playwright — 보통  
🔵 Integration Testing — 보통  
🔵 API Testing — 보통  
🔵 Mock Testing — 보통

🟠 Selenium — 어려움  
🟠 Load Testing — 어려움  
🟠 Performance Testing — 어려움  
🟠 End to End Testing — 어려움  
🟠 Contract Testing — 어려움

🔴 Chaos Testing — 매우 어려움  
🔴 Distributed Load Testing — 매우 어려움  
🔴 Large Scale Performance Testing — 매우 어려움  
🔴 Fault Injection Testing — 매우 어려움  
🔴 Production Resilience Testing — 매우 어려움
</details>

---

<!-- devtrack-draft-id: 98a2be42-d8dd-4af6-a6e3-b24d942a1f70 -->
<details>
<summary><strong>실제 소프트웨어 프로그래머가 되는 3단계</strong></summary>

1. 개인 소프트웨어 만들기  
2. 내부 소프트웨어 만들기 (선택된 소규모 그룹을 위해)  
3. 대중을 대상으로 한 소프트웨어 만들기

만약 당신이 지금까지 개인 소프트웨어를 만들어본 적만 있다면, 아직 대중을 대상으로 한 소프트웨어를 만들 자격이 없습니다.

단계별로 올라갈수록 위험은 더 커지고, 제약은 더 엄격해지며, 더 철저한 QA가 필요합니다.

그래서 앱을 한 번도 만들어본 적 없는 사람들에게 드리는 제 조언은 이것입니다:

작은 그룹의 테스터(심지어 1명이라도 훌륭합니다)를 찾아서, 당신이 만든 앱을 그들의 실제 생활에서 정말로 사용하게 하세요.

그로부터 받을 피드백은 당신의 마음을 날려버릴 겁니다. 그것은 당신이 자신의 형편없는 제품에 얼마나 관대했는지를 보여줄 겁니다. 당신은 프로세스와 품질에 집중하기 시작할 것입니다.

그것은 좌절스럽고, 느리고, 힘든 작업일 겁니다.

그게 프로그래밍입니다.

</details>

---

<!-- devtrack-draft-id: 3ce35ddd-061b-4c25-b2b6-996c49ea32a5 -->
<details>
<summary><strong>소프트웨어 팩토리의 목표는 완전한 자동화에 도달하는 것이 아닙니다 </strong></summary>

코딩 에이전트로부터 최대한의 효과를 얻어, 가능한 한 빠르고 효율적으로 최고 품질의 소프트웨어를 출시하여 고객에게 가장 큰 영향을 미치는 것이 목표입니다.

당신은 공장을 신중하게 측정하고 조정함으로써 이것을 증명하고 싶을 것입니다. 우리는 이것을 “팩토리 엔지니어링”이라고 부릅니다.

</details>

---

<!-- devtrack-draft-id: 8e2beabd-2171-4e04-a1b8-0cb2fc571bd3 -->
<details>
<summary><strong>앞으로 3~5년 동안 소프트웨어 개발에 대한 나의 예측:</strong></summary>

AI는 소프트웨어 수요를 줄이지 않을 것입니다. 사람들이 "자신만의 시스템"을 만들지 않을 겁니다.  
정반대로, 훨씬 더 큰 시장을 창출할 것입니다.

얼마 전까지 맞춤형 소프트웨어 개발은 대부분의 비즈니스가 감당할 수 없는 사치였습니다.

이러한 비즈니스들은 소프트웨어로 해결할 수 있는 문제들이 있었지만, 개발 비용이 투자를 정당화하지 못했습니다.

이 상황이 변하고 있습니다.

AI 덕분에 훨씬 작은 팀, 심지어 한 명의 개인조차도 이전에 몇 달의 작업과 막대한 예산이 필요했던 솔루션을 만들 수 있게 될 것입니다.

그리고 바로 이런 이유로 무언가가 더 저렴해지면, 그 수요가 줄어드는 대신 증가할 수 있습니다 (제본스의 역설).

이제 어떤 중소기업(PYME)도 이전에 도달할 수 없었던 맞춤 개발, 자동화, 통합에 투자할 수 있게 될 것입니다.

이전에는 필요하지 않았기 때문이 아니라, 이제야 경제적으로 합리적이기 때문입니다.

프로그래머들에게 큰 기회는   
이전에는 개발 판매가 무의미했던 수천 개의 비즈니스에 도달하는 데 있을 것이라고 생각합니다.

더 낮은 개발 비용, 기술에 투자할 수 있는 더 많은 비즈니스, 그리고 잠재적으로 훨씬 더 큰 시장.

</details>

---

<!-- devtrack-draft-id: fa6e58fa-b849-43e3-bd0e-5010166c265b -->
<details>
<summary><strong>FDE가 SI와 같은 방식으로 접근한다면 돈받고 바이브 코딩 해주는 것일 뿐 어떤 가치도 만들어내지 못합니다.</strong></summary>

FDE 필요성의 대두와 SI의 부활은 같은 말이 아닙니다. FDE가 대두되었던 배경은 원래는 고객 맞춤형으로 하나하나 만들어주었던 SI 프로덕트들이 AI를 통해, 매우 빠르게 스케일 고려가 가능하며 반복 가능하게 만들 수 있게 되었기 때문입니다.

회사에서 유사 FDE노릇하다 든 가장 큰 생각은 엔지니어만 Forward하면 안 된다는 것입니다. 개발의 비용이 0에 수렴하게끔 되어가기 때문에 IT 서비스의 고객 전선에 뛰어들 수 있는 사람은 엔지니어 뿐만이 아니게 되었기 때문이에요

걍 모든 직군의 사람들이 엔지니어가 되서 Forward할 수 있으면 ROI가 가장 잘 나옵니다

"그래도 엔지니어가 더 잘 알지 않냐" 근시안적으로는 그럴 수도 있는데요, 직군을 파괴하는 사람들이 지금부터 회사에 많으면 어찌됐든 미래에는 다 해결될것 같습니다. 모든 프로덕트 직군들이 Forward해서 고객사 문제 다 각개격파 가능하다고 봐용

</details>

---

<!-- devtrack-draft-id: 9ac7758f-4d35-44ad-9c59-603e53e65e99 -->
<details>
<summary><strong>FDE(Forward Deployed Engineer, 전진 배치 엔지니어 / 현장 엔지니어)</strong></summary>

FDE는 고객사 현장에 전진 배치되어 고객의 요구사항에 맞춰 전체 시스템을 설계하고 구현하는 소프트웨어 엔지니어입니다.

FDE는 고객사나 현장 환경에 맞춰 시스템을 통합하고, 커스텀 아키텍처를 설계하며 기술적 문제를 해결하는 역할입니다.

명칭에 'Deployed(배포)'가 포함되는 만큼, 클라우드 환경 구축, 배포 파이프라인 관리, 인프라 연동 등의 업무 비중이 높습니다.

현장에서 솔루션을 실제로 구현하고 연동할 때 백엔드 로직, API 개발, 데이터베이스 연동 작업이 핵심입니다.

</details>

---
