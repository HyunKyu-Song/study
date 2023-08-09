> ## substr(), substring(), slice() 함수는 모두 문자열을 잘라주는 역할
<br>
substr()<br>
: 파라미터로 입력받은 start index부터 length 길이만큼 string을 잘라내어 반환하는 함수
<br>

``` js
let str = "apple"
let first = str.substr(0, 1);	// a
let second = str.substr(1, 1);	// p
```
<br>
substring()
<br>
: 매개변수로 자르고 싶은 문자열의 시작 idx와 마지막 idx를 전달

``` js
let str = "apple?"
let first = str.substring(0, 1);	// a
let second = str.substring(2, 4);	// pl
```
<br>
slice()
<br>
: substring() 함수처럼 시작 idx와 마지막 idx를 전달

``` js
let str = "apple?"
let first = str.slice(0, 1);	// a
let second = str.slice(2, 4);	// pl
```
