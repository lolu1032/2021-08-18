# 산술 연산자(arithmetic operator)

연산자 | 의미
--|--
(+) | 왼쪽의 피연산자에 오른쪽의 피연산자를 더함
(-) | 왼쪽의 피연산자에서 오른쪽의 피연산자를 뺌
(*) | 왼쪽의 피연산자에 오른쪽의 피연산자를 곱함
(/) | 왼쪽의 피연산자를 오른쪽의 피연산자로 나눔
(%) | 왼쪽의 피연산자를 오른쪽의 피연산자로 나눈후, 그 나머지를 반환함

출처:<a href="http://tcpschool.com/cpp/cpp_operator_arithmetic">TCPSCHOOL</a>

## 예제
```javascript
console.log(1 + 2) // 3
console.log(5 - 7) // -2
console.log(3 * 4) // 12
console.log(10 / 2) // 5
console.log(7 % 5) // 2
```

# 할당 연산자(assignment operator)

이름 | 단축 연산자 | 뜻
--|--|--
곱셉 후 할당 | a *= b | a = a * b
나눗셈 후 할당 | a /= b | a = a / b
나머지 할당 | a %= b | a = a % b
덧셈 후 할당 | a += b | a = a + b
뺄셈 후 할당 | a -= b | a = a - b

# 비교 연산자(comparison aperator)

연산자 | 의미
--|--
동등 (==) | 피연산자가 서로 같으면 true를 반환한다
일치 (===) | 두 피연산자의 값과 타입이 모두 같은경우 true를 변환한다
부등 (!=) | 피연산자가 서로 다르면 true를 반환한다
불일치 (!==) | 피연산자의 값 또는 타입이 서로 다를 경우 true를 반환한다

출처: <a href="https://developer.mozilla.org/ko/docs/Web/JavaScript/Guide/Expressions_and_Operators">MDN</a>

## 예제
```javascript
1 === '1' // false
1 == '1' // true
1 != '1' // false
1 !== '1' // true
```

