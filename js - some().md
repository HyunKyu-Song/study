- 배열의 요소 중에서 하나 이상의 요소가 주어진 조건을 만족하는지를 판별

- 요소들 중에서 하나라도 주어진 조건을 만족하면 true를 반환

- 그렇지 않으면 false를 반환

``` js
const numbers = [1, 3, 5, 7, 9];

const hasEvenNumber = numbers.some(number => number % 2 === 0);
console.log(hasEvenNumber); // 출력: false
```
