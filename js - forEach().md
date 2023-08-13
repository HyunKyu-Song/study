- 배열의 각 요소에 대해 주어진 함수를 실행하는 데 사용

- 배열을 순회하며 각 요소에 대해 작업을 수행

- 새로운 배열을 반환 x

- 기존 배열의 요소를 변형 x

``` js
const fruits = ['apple', 'banana', 'orange'];

fruits.forEach((fruit, index) => {
  console.log(`Fruit at index ${index}: ${fruit}`);
});

// 출력값
// Fruit at index 0: apple
// Fruit at index 1: banana
// Fruit at index 2: orange
```

만약 배열의 요소를 변형하거나 새로운 배열을 생성하려면 map() 메서드를 사용하는 것이 더 적합
