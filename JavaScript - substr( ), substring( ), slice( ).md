## substr(), substring(), slice() 함수는 모두 문자열을 잘라주는 역할

### substr()
- 파라미터로 입력받은 start index부터 length 길이만큼 string을 잘라내어 반환하는 함수
``` js
let str = "apple"
let first = str.substr(0, 1);	// a
let second = str.substr(1, 1);	// p
```
<br>

### substring()
- 매개변수로 자르고 싶은 문자열의 시작 idx와 마지막 idx를 전달
- 음수를 사용하면 0으로 취급
``` js
let str = "apple?"
let first = str.substring(0, 1);	// a
let second = str.substring(2, 4);	// pl
```
<br>

### slice()
- substring() 함수처럼 시작 idx와 마지막 idx를 전달
- 음수를 사용하면 문자열의 끝에서부터의 인덱스를 나타남. ex) -1은 마지막 문자를 의미함
``` js
let str = "apple?"
let first = str.slice(0, 1);	// a
let second = str.slice(2, 4);	// pl
```
