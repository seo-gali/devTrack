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

