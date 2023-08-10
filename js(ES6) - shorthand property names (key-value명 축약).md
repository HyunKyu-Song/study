객체에서 key와 value가 같다면 축약해서 사용가능

``` js
let name = 'song';
let age = 26;

// 사용 전
let obj1 = {
    name : 'song',
    age : 26
}

console.log(obj1) // {name : 'song', age : 26, from : 'korea'}
console.log(obj1.name) // song
console.log(obj1.age) // 26


// 사용 후
let obj2 = {
    name,
    age,
};

console.log(obj2) // {name : 'song', age : 26, from : 'korea'}
console.log(obj2.name) // song
console.log(obj2.age) // 26
```
