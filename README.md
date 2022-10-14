## infinite scroll

- 무한스크롤 구현
- 컨텐츠의 끝이 화면 끝에 닿으면 api가 호출되게 구현
- fetch, async, await 사용해봄

## API 연동

https://jsonplaceholder.typicode.com/

- 프로토타이핑용 api
- /posts 활용
- [json-server](https://www.npmjs.com/package/json-server)

### removeEventListener

https://developer.mozilla.org/ko/docs/Web/API/EventTarget/removeEventListener

- addEventListener()로 등록했던 이벤트 리스너를 제거
- 더이상 필요가 없는데 이벤트가 계속 발생하는 경우 메모리 누수가 일어날 수 있음
- 따라서 명시적으로 해제
