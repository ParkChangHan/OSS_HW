# Redux Counter Example

redux counter example

## Redux?
redux란 App의 클라이언트쪽 state를 관리하기 위한 것이다.
공식문서에 따르면 redux는 앱의 복잡성을 제어하기 위한 하나의 state제어 수단이라고 한다.
App 전체에는 store라는 커다란 하나의 state가 존재하는데 이것이 App의 state를 총괄한다.
리듀서는 단순 객체인 action 이벤트가 발생했을 때만 작동하며 이벤트를 발동시키는 방법은 dispatch라는 함수에 단순 객체인 action을 넣는 것으로 가능하다.
redux로 관리했을 때의 장점으로는 특정 액션이벤트 발생에만 리듀서가 작동했기 때문에 state 정확히 어떤 액션 이벤트로부터 변경된 것인지 알 수 있다.
