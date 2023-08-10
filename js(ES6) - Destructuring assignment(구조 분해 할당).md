배열 혹은 객체에서 각각에 value, property를 쉽게 분해하여 변수에 담을 수 있다.

 

 

객체에서 사용하는 법
``` js
// 객체 선언 및 할당
let std = {
    name: 'song',
    num: 12,
}

// 사용 전
let name = std.name;
let num = std.num;
console.log(name); // song
console.log(num); // 12


// 사용 후
let { name, num } = std;
console.log(name); // song
console.log(num); // 12
```

 

배열에서 사용하는 법
``` js
// 배열 선언 및 할당
let std_arr = ['song', 'kim', 'park'];


// 사용 전
let one = std_arr[0];
let two = std_arr[1];
let three = std_arr[2];
console.log(one, two, three); // song kim park


// 사용 후
let [one, two, three] = std_arr;
console.log(one, two, three); // song kim park
```
