객체 내부의 중첩된 속성이나 메서드에 접근할 때, 해당 경로에 값이 없는 경우 에러를 발생시키지 않고 안전하게 처리할 수 있는 방법이다.
존재하지 않을 수 있는 중첩된 객체 구조를 다룰 때 유용하며, 코드의 안정성을 높이는 데 도움이 된다.

``` js
// 사용 전
var user = {
   name: 'song',
   // age: {value: 15},
}
console.log(user.age.value);	// 에러발생


// 사용 후
var user = {
   name: 'song',
   // age: {value: 15},
}
console.log(user.age?.value);	// undefined를 출력
```
