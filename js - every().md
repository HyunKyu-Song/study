- 배열의 모든 요소가 주어진 조건을 만족하는지를 판별

- 배열 내의 모든 요소가 주어진 조건을 만족하면 true를 반환

- 그렇지 않으면 false를 반환

``` js
const numbers = [1, 3, 5, 7, 9];

const allPositive = numbers.every(number => number > 0);
console.log(allPositive); // 출력: true
```
