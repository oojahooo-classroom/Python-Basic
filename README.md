# Basic of Python

*본 스터디의 계획서 및 내용, 과제는 [고려대학교 소프트웨어 분석 연구실 오학주 교수님](http://prl.korea.ac.kr/~pronto/home/)의 컴퓨터프로그래밍2 수업을 바탕으로 하고 있음을 밝힙니다.

## Logistics
- Tutor: [Jaeho Kim](https://oojahooo.github.io) (oojahooo@gmail.com)
- Time: 매주 수, 목 오후 3시 ~ 4시
- Location: 정보관 예정 (대면, 자세한 장소는 확정 후 공지 예정)

## Abstract
파이썬은 굉장히 쉽고 유저 친화적인 문법, 이에 뒤따르는 확장성과 범용성으로 명실상부 최고의 인기를 자랑하는 프로그래미 언어 중 하나이다.
고려대학교의 커리큘럼 기준으로 C언어를 먼저 배운 뒤 접하게 되는 파이썬은, 마치 의사코드와 같은 형태의 간결한 문법 덕에 큰 무리 없이 적응할 수 있다.
그럼에도 파이썬을 잘 활용하기 위해서 알아야 하는 개념이 많다.

본 스터디에서는 C언어와 대응되는 간단한 파이썬 문법에서부터, C언어에서 접해보지 못한 파이썬의 mutable/immutable data type, higher-order function, class 등의 개념을 명확히 이해하여 어떤 목적으로 파이썬을 활용하게 되든 더 쉽고 빠르게 생산적인 코드를 작성할 수 있도록 돕고자 한다.

## References
- [Composing Programs](https://composingprograms.com)

## Goal & Topics
파이썬의 기본적인 특징과 문법을 C언어와 비교하여 명확히 이해하며, 더 나아가 higher-order function과 같은 함수형 언어의 특징과 class 및 class inheritance와 같은 객체지향형 프로그래밍 언어의 특징을 파이썬에서 어떻게 구현할 수 있는지 알고 규모 있는 프로그램을 구조적으로 구현할 수 있도록 하는 것이 목표이다.
자세한 주제는 다음과 같다:

- **Preliminaries:** Values and Variables, Objects, Expressions, Statements
- **Advanced Techniques:** Comprehensions, Higher-order Functions, Python Built-in Data Types(Lists, Tuples, Dict, etc.)
- **OOP:** Class, Methods, Overloading, Overriding, Inheritance, User-defined Class

## Prerequisties
컴퓨터프로그래밍1, 전산수학1을 수강했음을 가정하고 진행된다.
특히 C언어의 기본적인 문법들은 이해했다고 가정하고 진행하지만, 스터디원의 이해에 필요하다면 기본적인 개념부터 설명할 예정이다.

## Assignments
본 스터디의 과제는 GitHub Classroom으로 진행될 예정이다.
이에 약간의 Git, GitHub 스킬을 가지고 있으면 좋으나 이 역시 스터디에서 충분히 따라올 수 있도록 설명할 예정이다.

구체적인 과제 내용 및 제출 방식은 스터디 첫 시간에 공지하도록 하겠다.

## Schedule (Tentative)
|Weeks|Topics|Lecture Videos|Assignments|
|:---:|:---:|:---:|:---:|
|Week 1|파이썬이란?, 변수와 값|[1-1](https://youtu.be/UqvR2cv-9_g), [1-2(Git&GitHub Study)](https://youtu.be/8aDuMMfIlho)||
|Week 2|가장 기본적인 문법들: 식(expressions), 구문(statements), 조건문(`if`-statement), 반복문(`while`-loop, `for`-loop)|[2-1](https://youtu.be/0qDt1wc265g), [2-2](https://youtu.be/RMbl-ocKgUk)|[Assignment 1](https://classroom.github.com/a/0KSFhKpQ)|
|Week 3|Abstraction is All You Need: 함수(functions)의 선언(declare), 정의(define), 호출(call), 재귀함수(recursions)|3-1, 3-2|[Assignment 2](https://classroom.github.com/a/G4GTBeZ6)|
|Week 4|고차함수(higher-order func), 파이썬 기본 자료형들: 리스트(`list`), 문자열(`str`)|4-1, 4-2|[Assignment 3](https://classroom.github.com/a/i1r-WVe1)|
|Week 5|파이썬 기본 자료형들: 튜플(`tuple`), 딕셔너리(`dict`), 집합(`set`), comprehension|5-1, 5-2|[Assignment 4](https://classroom.github.com/a/sNAEm7hm)|
|Week 6|파이썬으로 OOP하기: 클래스(`class`)의 선언(declare), 정의(define), 생성(construct), object vs instance|6-1, 6-2|[Assignment 5](https://classroom.github.com/a/9NnlTSIz)|
|Week 7|파이썬으로 OOP하기: 클래스의 함수(method), 연산자 오버로딩(overloading), 상속(inheritance)|7-1, 7-2|[Assignment 6](https://classroom.github.com/a/i3CBszZI)|
|Week 8|마무리: 이상한, 그래서 매력적인 파이썬|8-1, 8-2||
