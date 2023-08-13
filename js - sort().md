- 배열의 요소를 주어진 함수에 따라 정렬

- 원본 배열을 변형

- 정렬된 배열을 반환

``` js
const numbers = [4, 2, 8, 5, 1];

numbers.sort((a, b) => a - b);
console.log(numbers); // [1, 2, 4, 5, 8]
```
