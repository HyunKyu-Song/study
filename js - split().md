- 문자열을 지정한 구분자를 기준으로 나누어 배열로 반환<br><br>
### 공백을 기준으로 반환

``` js
const sentence = 'This is a sample sentence';

const words = sentence.split(' ');

console.log(words); // ['This', 'is', 'a', 'sample', 'sentence']
```
<br><br>
### 쉼표를 기준으로 반환
``` js
const numbers = '1,2,3,4,5';

const numberArray = numbers.split(',');

console.log(numberArray); // ['1', '2', '3', '4', '5']
```
