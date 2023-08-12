- 배열에서 주어진 조건을 만족하는 첫 번째 요소를 찾아 반환

- 해당 요소를 찾으면 더 이상 검색을 진행하지 않고 검색을 종료

- 만족하는 조건이 없다면 undefined를 반환

``` js
const students = [
  { id: 1, name: 'Alice' },
  { id: 2, name: 'Bob' },
  { id: 3, name: 'Charlie' },
];

const student = students.find(student => student.id === 2);
console.log(student); // 출력: { id: 2, name: 'Bob' }
```
