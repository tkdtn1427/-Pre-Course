## 🚀 기능 요구 사항

암호문을 좋아하는 괴짜 개발자 브라운이 이번에는 중복 문자를 이용한 새로운 암호를 만들었다. 예를 들어 "browoanoommnaon"이라는 암호문은 다음과 같은 순서로 해독할 수 있다.

1. "browoanoommnaon"
2. "browoannaon"
3. "browoaaon"
4. "browoon"
5. "brown"

임의의 문자열 cryptogram이 매개변수로 주어질 때, 연속하는 중복 문자들을 삭제한 결과를 return 하도록 solution 메서드를 완성하라.

### 제한사항

- cryptogram은 길이가 1 이상 1000 이하인 문자열이다.
- cryptogram은 알파벳 소문자로만 이루어져 있다.

### 실행 결과 예시

| cryptogram | result |
| --- | --- |
| "browoanoommnaon" | "brown" |
| "zyelleyz" | "" |

---

### 🚀 기능 목록 정리
1. 입력받은 문자열에서 연속하는 중복 문자를 제거하는 함수
2. 중복 문자를 제거한 함수와 기존 문자를 비교하여 중복된 문자열이 존재했는지 확인하는 함수
3. 1,2의 과정을 거쳐 중복된 문자열이 없거나 문자열의 길이가 0 이되면 결과를 리턴하는 함수
