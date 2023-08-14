- 배열의 특정 부분을 추출하여 새로운 배열로 반환

- 원본 배열은 변경 x
```js
const fruits = ['apple', 'banana', 'orange', 'grape', 'kiwi'];

const slicedFruits = fruits.slice(1, 4);

console.log(slicedFruits); // ['banana', 'orange', 'grape']
```
``` js
const slicedFruits = fruits.slice(-3, -1);

console.log(slicedFruits); // ['orange', 'grape']
```
음수 인덱스를 사용하여 배열의 뒤쪽부터 추출가능
