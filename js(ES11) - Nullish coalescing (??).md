?? 왼쪽값이 null or undefined이면 오른쪽 값이 선택된다.

``` js
let data = {
    name : 'song',
    age : 26,
    job : null
}
console.log(data.name ?? '정보없음') // song
console.log(data.age ?? '정보없음') // 26
console.log(data.job ?? '정보없음') // 정보없음

console.log(null ?? '로딩중...'); // 로딩중...
console.log(undefined ?? '로딩중...'); // 로딩중...
console.log('실행' ?? '로딩중...'); // 실행
```
<br>
언제 사용할까?<br>
: ajax 요청 등 때문에 값이 늦게 도착할 때 (특히, React나 Vue 쓸 때 유용)
