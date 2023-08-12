- array 자료 갯수만큼 함수안의 코드 실행해줌
- 함수의 파라미터는 array안에 있던 자료
- return에 반환값 적으면 array로 담아줌

``` js
let arr = [10, 20 ,30]

let a = arr.map(function (item, i) {
    return item
})
console.log(a) // [10, 20, 30]
```
item은 배열에 각 요소 (여기서는 10, 20, 30)

i는 인덱스로 0부터 시작 (여기서는 0, 1, 2)
