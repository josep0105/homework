# homework

```javascript
const browser = "IE";

switch (browser) {
  case "IE":
    console.log("go away!");
    break;
  case "Chrome":
    console.log("Love you!");
    break;
  case "Firefox":
    console.log("Love you Too!");
    break;
  default:
    console.log("Same...");
    break;
}

// while

// const condition = true;

// while (condition) {
//   // condtion이 참이라면 body부분 실행
// }

let i = 0;

while (i < 10) {
  console.log(`While: ${i}`);
  i++;
}

// while: 조건이 참이여야지만 실행
// do ~ while: 무조건 한 번은 먼저 실행하고, 이후에 조건을 검사한다.

let j = 0;

do {
  console.log(`do while: ${j}`);
  j++;
} while (j < 10);

// for:
for (let k = 0; k < 10; k++) {
  console.log(`for: ${k}`);

  if (k == 5) {
    continue;
  }

  console.log(`Hello ${k}`);
}

// continue 건너뛴다
// break 강제 종료
```
