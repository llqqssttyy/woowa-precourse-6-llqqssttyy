# woowa-precourse-6-llqqssttyy

> Git의 [submodule을 학습하고](https://velog.io/@llqqssttyy/GitGitHub-%EC%84%9C%EB%B8%8C%EB%AA%A8%EB%93%88%EC%9D%84-%ED%99%9C%EC%9A%A9%ED%95%B4-%ED%94%84%EB%A6%AC%EC%BD%94%EC%8A%A4-%EC%A0%80%EC%9E%A5%EC%86%8C-%EA%B4%80%EB%A6%AC%ED%95%98%EA%B8%B0) 제작한 우테코 6기 프리코스 및 최종 코딩 테스트 제출 코드 저장소입니다.

<br/>

해당 저장소는 제출 코드를 관리하는 `submit` 디렉터리와 리팩토링 코드를 저장하는 `refactor` 디렉터리로 이루어져 있습니다.

```
.
├── README.md
├── refactor
│   └── javascript-oncall-6-llqqssttyy
│
└── submit
    ├── javascript-baseball-6
    ├── javascript-christmas-6-llqqssttyy
    ├── javascript-lotto-6
    ├── javascript-oncall-6-llqqssttyy
    └── javascript-racingcar-6
```

<br/>

## 모아 보기

<table>
  <thead>
    <th>주차</th>
    <th>미션</th>
    <th>리뷰 PR</th>
    <th>회고</th>
    <th>키워드</th>
  </thead>

  <tbody>
    <tr>
      <td>5</td>
      <td>📞 개발자 비상근무</td>
      <td>
        -
      </td>
      <td>
        <a href="https://velog.io/@llqqssttyy/FE-%EC%9A%B0%ED%85%8C%EC%BD%94-6%EA%B8%B0-%EC%B5%9C%EC%A2%85-%EC%BD%94%EB%94%A9-%ED%85%8C%EC%8A%A4%ED%8A%B8-%ED%9A%8C%EA%B3%A0">[FE] 우테코 6기 최종 코딩 테스트 회고
</a>
      </td>
      <td>
        - 기록으로 내 단점 파악하기<br/>- 객체 배열 활용하기<br/>
      </td>
    </tr>
    <tr>
      <td>4</td>
      <td>🎄 크리스마스 이벤트</td>
      <td>
        <a href="https://github.com/llqqssttyy/javascript-christmas-6-llqqssttyy/pull/1">#1</a>
      </td>
      <td>
        <a href="https://velog.io/@llqqssttyy/FE-%EC%9A%B0%ED%85%8C%EC%BD%94-%ED%94%84%EB%A6%AC%EB%AF%B8%EC%85%98-4%EC%A3%BC%EC%B0%A8-%ED%94%84%EB%A6%AC%EC%BD%94%EC%8A%A4-%EB%A7%88%EB%AC%B4%EB%A6%AC">[FE] 우테코 6기 프리미션 4주차 회고</a>
      </td>
      <td>
        - 복잡한 요구사항 파악하기<br/>- 객체 생성하기(클래스 vs 객체 리터럴)<br/>  - eslint와 prettier<br/>
      </td>
    </tr>
    <tr>
      <td>3</td>
      <td>💸 로또</td>
      <td>
        <a href="https://github.com/woowacourse-precourse/javascript-lotto-6/pull/203">#203</a>
      </td>
      <td>
        <a href="https://velog.io/@llqqssttyy/FE-%EC%9A%B0%ED%85%8C%EC%BD%94-6%EA%B8%B0-%ED%94%84%EB%A6%AC%EC%BD%94%EC%8A%A4-3%EC%A3%BC%EC%B0%A8-%ED%9A%8C%EA%B3%A0-6zcqs6o1">[FE] 우테코 6기 프리코스 3주차 회고</a>
      </td>
      <td>
        - Javascript 클래스 문법<br/>- 도메인 로직과 단위 테스트<br/>- 에러 핸들링<br/>  
      </td>
    </tr>
    <tr>
      <td>2</td>
      <td>🚗 자동차 경주</td>
      <td>
        <a href="https://github.com/woowacourse-precourse/javascript-racingcar-6/pull/168">#168</a>
      </td>
      <td>
        <a href="https://velog.io/@llqqssttyy/FE-%EC%9A%B0%ED%85%8C%EC%BD%94-6%EA%B8%B0-%ED%94%84%EB%A6%AC%EC%BD%94%EC%8A%A4-2%EC%A3%BC%EC%B0%A8-%ED%9A%8C%EA%B3%A0">[FE] 우테코 6기 프리코스 2주차 회고</a>
      </td>
      <td>
        - MVC 패턴<br/>- JSDoc<br/>- Validator의 가독성과 책임<br/>
      </td>
    </tr>
    <tr>
      <td>1</td>
      <td>⚾️ 숫자 야구</td>
      <td>
        <a href="https://github.com/woowacourse-precourse/javascript-baseball-6/pull/83">#83</a>
      </td>
      <td>
        <a href="https://velog.io/@llqqssttyy/FE-%EC%9A%B0%ED%85%8C%EC%BD%94-6%EA%B8%B0-%ED%94%84%EB%A6%AC%EC%BD%94%EC%8A%A4-1%EC%A3%BC%EC%B0%A8-%ED%9A%8C%EA%B3%A0">[FE] 우테코 6기 프리코스 1주차 회고</a>
      </td>
      <td>
        - Jest mocking<br/>- Airbnb Style Guide<br/>- 객체 지향 설계(OOP)<br/>
      </td>
    </tr>
  </tbody>
</table>

<br/>

## What I Learned..

1. 도메인 로직과 서비스 로직을 분리하면 코드 가시성과 테스트 용이성이 좋아진다.
2. 테스트 코드는 코드에 대한 최소한의 검증이다. 성공 테스트에 매몰되지 말고 실패 케이스를 생각하는 훈련을 하자.
3. eslint와 prettier를 사용해 구성원 간 약속된 규칙을 만들면 더 깊은 코드 리뷰가 가능해진다.
4. 가독성에 가장 많은 영향을 미치는 건 일관적인 코드 작성이다.
