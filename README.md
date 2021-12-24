# im-sprint-tree-ui

이번 과제에서는, 기업용 애플리케이션에서 흔히 볼 수 있는 트리구조를 표현한 UI를 직접 구현해봅니다.

### Getting Started

- 우리가 최종적으로 만들어야 할 결과물은 `result.html` 을 통해 미리 확인할 수 있습니다. HTML 구조 역시 `result.html`과 동일할 것입니다.
- Tree UI를 작성할 파일은 `fix_me.js` 파일입니다.
- 테스트 케이스는 `__test__/index.test.js` 파일에서 확인할 수 있습니다.

## Bare minimum Requirements
- `fix_me.js`에서 `createTreeView` 함수를 직접 구현해보고 테스트를 통과시키세요.

### 더 생각해볼 주제 - Advanced

(아래 과제는 Advanced 과제로, 수료 필수 조건은 아닙니다.)

아래 키워드는 재귀함수를 더 효율적이고 멋지게 쓸 수 있는 방법에 대한 키워드입니다. 위의 모든 레슨을 충분히 이해하고, 코플릿 문제를 모두 다 푸셨다면 아래 키워드를 직접 구글링하여, TIL을 작성해보시는 게 어떨까요?

- 재귀 함수와 메모리 사용량 간의 관계 (javascript recursion memory leak)
꼬리 재귀 (tail recursion in js)
- 하노이의 탑 재귀 (js tower of hanoi in recursion)
- 조합 재귀함수 (js combination in recursion)

---------

### Sprint 진행 후 느낀 점

createTreeView(menu, currentNode) 함수를 2가지 버전으로 만들어 봤다. 처음에는 버전2로 완성하고 끝낼 생각이었지만, 고차함수를 이용할 수 있지 않을 까하는 생각으로 map을 사용하여, 재구성해봤다.
