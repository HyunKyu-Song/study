- 배열에서 특정 위치에 요소를 추가하거나 삭제하는 데 사용
  <br><br>
### 요소추가
``` js
const numbers = [1, 2, 3, 4];
numbers.splice(2, 0, 5, 6);

console.log(numbers); // [1, 2, 5, 6, 3, 4]
```
인덱스 2의 위치에 숫자 5와 6을 추가
<br><br>
### 요소 삭제
``` js
const numbers = [1, 2, 3, 4, 5];
numbers.splice(2, 2);

console.log(numbers); // [1, 2, 5]
```
인덱스 2부터 시작하여 2개의 요소를 삭제
