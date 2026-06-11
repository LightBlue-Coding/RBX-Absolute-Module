# Absolute Module

이 모듈은 Fusion스타일의 모듈입니다. 제가 어쩌다보니까 만들게 됬고요, 여러 기능이 있습니다.
This module is a Fusion-style module. I ended up creating it by chance, and it has various features.

==== 대표적인 기능 (Representative features) ====
1. Signal 기능 (Signal function)
- Signal기능은 서로간의 신호를 주고 받을수 있습니다. (단, 서버와 클라이언트 공유는 되지 않습니다.)
- The Signal function allows signals to be exchanged between each other. (However, signals are not shared between the server and the client.)

2. LB 문법 (LB_Syntax)
- 저의 닉네임 (Light_Blue)의 앞글자를 따서 만든 계산법입니다.
- This is a calculation method created using the first letter of my nickname (Light_Blue).

3. 16진수 배열 (HexArray)
- 16진수의 배열입니다. 배열의 값은 16진수의 값들의 최소공배수입니다.
- It is an array of hexadecimal numbers. The values ​​of the array are the least common multiples of the hexadecimal values.

==== 객체 (Instance) ====
1. 생성 (New)
- 인스턴스를 만듭니다.
- Creates an instance.

2. 자식(Children)
- 생성 함수에 사용되는 키입니다. (값은 테이블로 지정하셔야 됩니다.)
- This is the key used in the 'New' function. (The value must be specified as a table.)

3. 이벤트 발생 (OnEvent)
- New함수에 사용되는 키입니다. (값은 함수입니다.)
- This is the key used in the 'New' function. (The value is a function.)

4. 어트리뷰트 (Attribute)
- New함수에 사용되는 키입니다. (값은 ValueBase타입을 가집니다.)
- This is the key used in the New function. (The value is of type ValueBase.)

5. 참조 (Ref)
- 먼저 정의를 하시고 사용합니다.
  New함수에 사용되는 키이며, 값은 boolean타입을 가집니다.
- Define it first, then use it.
  It is a key used in the New function, and its value is of type boolean.

==== 유틸 (Util) ===
1. 값 (Value)
- 값을 정의합니다. (만약 값이 nil이라면, "[Abs.Value]: Value" 의 값으로 정의합니다.)
  Get, Set, Observe, Destroy 함수가 있습니다.
- Defines a value. (If the value is nil, it is defined as the value of "[Abs.Value]: Value".)
  There are Get, Set, Observe, and Destroy functions.

2. Mathf
- 여러 수학기능을 모아놨습니다.
- This has added several mathematical functions.

3. 루퍼 (Looper)
- Loop, ForValues함수가 있습니다.
- There are Loop and ForValues ​​functions.

==== 기타 기능 (Other features) ====
1. 스코프( Scoped )
- 메타테이블의 타입을 반환 합니다.
- Returns the type of the metatable.
