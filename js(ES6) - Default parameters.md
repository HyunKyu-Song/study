함수를 사용할 때, 파라미터에 값이 없다면 undefined가 출력된다.

Default parameters를 사용하면 파라미터에 값이 없을 때, 출력하는 초기값을 설정할 수 있다.
<br><br>
``` js
let func = function(res){
    console.log(res);
}

// 사용 전
func() // undefined


// 사용 후
func(res = 'hello') // hello
 ```
<br><br>
 

파라미터가 여러 개 있는 함수지만 1개만 써도 에러가 발생하지 않는다.
``` js
function 더하기(a, b, c){
    console.log(a);
}
더하기(1); // 1
 ```
<br><br>
 

함수의 defalut 값을 줄 수 있다.
``` js
function 더하기(a, b, c=3){
    console.log(a + b + c);
}

더하기(600, 10); // 613
```
더하기 함수에 필요한 인자가 3개지만 2개만 적고 실행하면 c는 defalut값 3이 들어가서 600+10+3=613이 출력된다.
