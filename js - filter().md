- 조건을 만족하는 요소들로 구성된 새로운 배열을 생성

- 원본 보존 (기존 배열은 변경 x)

``` js
const numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

const evenNumbers = numbers.filter(number => number % 2 === 0);
console.log(evenNumbers); // 출력: [2, 4, 6, 8, 10]
```
