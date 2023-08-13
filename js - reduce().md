- 배열의 각 요소에 대해 주어진 함수를 사용하여 하나의 결과값을 계산

- 요소를 순회하며 누적 값을 계산하는데 유용

- 배열 내 요소들을 하나의 값으로 축약하는 작업에 활용

```js
const numbers = [1, 2, 3, 4, 5];

const sum = numbers.reduce((accumulator, currentValue) => accumulator + currentValue, 0);
console.log(sum); // 출력: 15
```
