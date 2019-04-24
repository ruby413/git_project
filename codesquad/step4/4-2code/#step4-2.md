# node.js

Node.js 는 자바크스립트를 실행시킬 수 있는 chrome 엔진입니다. 

node.js 홈페이지 참고 : Node.js는 Chrome V8 JavaScript 엔진으로 빌드된 JavaScript 런타임입니다.

*책참고 : os? oh yes? 

메모리공간 

- 데이터 영역
- 코드 영역
    - 번역된 기계어 (코드) 가 들어감
- 힙
    - 동적할당객체 (객체, 배열, new, 표준입력)
- 스택
    - 쌓이는 공간, 함수를 실행시킬 때 쌓이는 공간
    - 함수 호출할 때 생기고 끝날 때 사라진다. (1mb 1000-2000번)
- 비동기 호출
    - settimeout 이벤트 스택 콜스택, 콜스택에 없을 때 이벤트 큐에 있는 콜백함수를 스택에 올린다.
    - 콜백함수는 이벤트큐에 있는 함수. settimeout와 같은 이벤트 후에 실행됨.

자바스크립트의 동작원리;