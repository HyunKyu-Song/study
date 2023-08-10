객체 혹은 배열들을 펼칠 수 있게 해주는 문법
<br><br>
 

사용가능 공간

: 중괄호, 대괄호, 소괄호 안에서만 가능
<br><br>
 

 

객체인 경우
``` js
let obj1 = {
    name : 'song',
    age : 26
}

let obj2 = {...obj1};
console.log(obj1); // {name : 'song', age : 26}
console.log(obj2); // {name : 'song', age : 26}



// 객체 속성값 추가
let obj3 = {...obj2, birth : 'march'};
console.log(obj3); // {name : 'song', age : 26, birth : 'march'}



// 객체 값 합치기(concat)
let product1 = {
    name : 'water',
    price : 500,
}
console.log('product1: ', product1); // {name : 'water', price : 500}


let product2 = {
    상품명 : 'coke',
    가격 : 1200,
}
console.log('prodict2: ', product2); // {이름 : 'coke', 가격 : 1200}


let product3 = {...product1, ...product2};
console.log('product3: ', product3); // {name : 'water', price : 500, 이름 : 'coke', 가격 : 1200}
 ```
<br><br>
참고) 객체 값을 합칠 때, 값 중복이 일어나면 마지막 값이 저장
``` js
var o1 = { a : 1, b : 2 };
var o2 = { a : 2, ...o1 };
console.log(o2); //출력결과: { a : 1, b : 2 };
 ```

 
<br><br>
배열인 경우
``` js
let arr = ['apple', 'banana', 'melon'];
console.log(arr); // ['apple', 'banana', 'melon']


let arr2 = [...arr];
console.log(arr2); // ['apple', 'banana', 'melon']


// 값 추가
let arr3 = [...arr2, 'strawberry'];
console.log(arr3); // ['apple', 'banana', 'melon', 'strawberry']


// 합치기
let 상품1 = ['신발', '바지'];
let 상품2 = ['귀걸이', '반지', '목걸이'];

let 상품3 = [...상품1, ...상품2];
console.log(상품3); // ['신발', '바지', '귀걸이', '반지', '목걸이']
```

 
<br><br>
함수 파라미터에 넣을 경우

 

배열에 값이 파라미터로 각각 들어간다.
``` js
function 더하기(a, b, c){
    return a + b + c;
}

let arr = [10, 20, 30];
let 합 = 더하기(...arr);

console.log(합); // 60
```
