# 산술 연산자(arithmetic operator)

| 연산자 | 의미                                                             |
| ------ | ---------------------------------------------------------------- |
| +      | 왼쪽의 피연산자에 오른쪽의 피연산자를 더함                       |
| -      | 왼쪽의 피연산자에서 오른쪽의 피연산자를 뺌                       |
| \*     | 왼쪽의 피연산자에 오른쪽의 피연산자를 곱함                       |
| /      | 왼쪽의 피연산자를 오른쪽의 피연산자로 나눔                       |
| %      | 왼쪽의 피연산자를 오른쪽의 피연산자로 나눈후, 그 나머지를 반환함 |

출처:<a href="http://tcpschool.com/cpp/cpp_operator_arithmetic">TCPSCHOOL</a>

## 예

```javascript
console.log(1 + 2); // 3
console.log(5 - 7); // -2
console.log(3 * 4); // 12
console.log(10 / 2); // 5
console.log(7 % 5); // 2
```

# 할당 연산자(assignment operator)

| 이름           | 단축 연산자 | 뜻         |
| -------------- | ----------- | ---------- |
| 곱셉 후 할당   | a \*= b     | a = a \* b |
| 나눗셈 후 할당 | a /= b      | a = a / b  |
| 나머지 할당    | a %= b      | a = a % b  |
| 덧셈 후 할당   | a += b      | a = a + b  |
| 뺄셈 후 할당   | a -= b      | a = a - b  |

# 비교 연산자(comparison aperator)

| 연산자       | 의미                                                     |
| ------------ | -------------------------------------------------------- |
| 동등 (==)    | 피연산자가 서로 같으면 true를 반환한다                   |
| 일치 (===)   | 두 피연산자의 값과 타입이 모두 같은경우 true를 변환한다  |
| 부등 (!=)    | 피연산자가 서로 다르면 true를 반환한다                   |
| 불일치 (!==) | 피연산자의 값 또는 타입이 서로 다를 경우 true를 반환한다 |

출처: <a href="https://developer.mozilla.org/ko/docs/Web/JavaScript/Guide/Expressions_and_Operators">MDN</a>

## 예

```javascript
1 === "1"; // false
1 == "1"; // true
1 != "1"; // false
1 !== "1"; // true
```

# 논리 연산자(logical operator)

| 논리 연산자 | 설명                                                |
| ----------- | --------------------------------------------------- |
| and         | 논리식이 모두 참이면 참을 반환함                    |
| or          | 논리식 중에서 하나라도 참이면 참을 반환함           |
| xor         | 논리식이 서로 다르면 참을 반환함                    |
| &&          | 논리식이 모두 참이면 참을 반환함                    |
| ㅣㅣ        | 논리식 중에서 하나라도 참이면 참을 반환함           |
| !           | 논리식의 결과가 참이면 거짓을, 거짓이면 참을 반환함 |

출처:<a href="http://tcpschool.com/php/php_operator_logic">TCPSCHOOL</a>

## 예

```javascript
const a = 1 === 123;
const b = "AB" === "ABC";
const c = false;

console.log(a); // false
console.log(b); // false
console.log(c); //false

console.log("&&: ", a && c); // &&: false
// &&: 그리고
console.log("||: ", a || b || c); // ||: false
// ||: 또는 // true가 하나라도있으면 true가됨
console.log("!: ", !a); // !: true
```

# 삼항 연산자(ternary operator)

조건부 삼항 연산자는 JavaScript에서 세 개의 피연산자를 취할 수 있는 유일한 연산자입니다. 맨 앞에 조건문 들어가고. 그 뒤로 물음표(?)와 조건이 참truthy이라면 실행할 식이 물음표 뒤로 들어갑니다. 바로 뒤로 콜론(:)이 들어가며 조건이 거짓falsy이라면 실행할 식이 마지막에 들어갑니다. 보통 if 명령문의 단축 형태로 쓰입니다.

출처:<a herf="https://developer.mozilla.org/ko/docs/Web/JavaScript/Reference/Operators/Conditional_Operator">MDN</a>

```javascript
const a = 1 < 2;

if (a) {
  console.log("참");
} else {
  console.log("거짓");
}

console.log(a ? "참" : "거짓"); // a가 true면 참 false면 거짓으로 나옴
```
