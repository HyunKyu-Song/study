- 배열에서 특정 요소의 인덱스를 검색

- 만약 배열 내에 해당 요소가 존재하지 않으면 -1을 반환

``` js
const fruits = ['apple', 'banana', 'orange', 'apple', 'grape'];

const appleIndex = fruits.indexOf('apple');
console.log(appleIndex); // 출력: 0

const orangeIndex = fruits.indexOf('orange');
console.log(orangeIndex); // 출력: 2

const nonExistentIndex = fruits.indexOf('pear');
console.log(nonExistentIndex); // 출력: -1
```
