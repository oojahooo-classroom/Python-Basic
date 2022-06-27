# Basic of Python

*본 스터디의 계획서 및 내용, 과제는 [고려대학교 소프트웨어 분석 연구실 오학주 교수님](http://prl.korea.ac.kr/~pronto/home/)의 컴퓨터프로그래밍2 수업을 바탕으로 하고 있음을 밝힙니다.

## Logistics
- Tutor: [Jaeho Kim](https://oojahooo.github.io) (oojahooo@gmail.com)
- Time: TBD
- Location: TBD (대면 희망)

## Abstract
파이썬은 굉장히 쉽고 유저 친화적인 문법, 이에 뒤따르는 확장성과 범용성으로 명실상부 최고의 인기를 자랑하는 프로그래미 언어 중 하나이다.
고려대학교의 커리큘럼 기준으로 C언어를 먼저 배운 뒤 접하게 되는 파이썬은, 마치 의사코드와 같은 형태의 간결한 문법 덕에 큰 무리 없이 적응할 수 있다.
그럼에도 파이썬을 잘 활용하기 위해서 알아야 하는 개념이 많다.

본 스터디에서는 C언어와 대응되는 간단한 파이썬 문법에서부터, C언어에서 접해보지 못한 파이썬의 mutable/immutable data type, higher-order function, class 등의 개념을 명확히 이해하여 어떤 목적으로 파이썬을 활용하게 되든 더 쉽고 빠르게 생산적인 코드를 작성할 수 있도록 돕고자 한다.

## References
- [Composing Programs](https://composingprograms.com)

## Goal & Topics
파이썬 프로그램의 
자세한 주제는 다음과 같다:

- **Preliminaries:** Inductive definition, Rule of inference, Functional programming
- **Basic Concepts:** Syntax, Semantics, Naming, Binding, Scoping, Environment, Interpreters, States, Reference, Parameter passing
- **Advanced Concepts:** Type system, Typing rules, Type checking, Soundness/completeness, Type inference, Polymorphism, Objects, Classes, Methods, Inheritance, Typed object-oriented languages

## Prerequisties
본 스터디의 내용과 과제에서는 함수형 프로그래밍을 주로 다루지만, C나 Python과 같은 언어의 기본적인 프로그래밍 스킬을 자연스럽게 할 수 있는 수준이면 좋다.

프로그래밍 과제는 모두 Ocaml을 활용할 예정이다.
대표적인 함수형 프로그래밍 언어이자 선언형 프로그래밍 언어이기 때문에 공부해 두면 인생에 큰 도움이 될 것이다.

또 아주 약간의 계산이론 내용과 이산수학 내용을 알고 있으면 도움되지만, 모르는 사람을 위해 첫시간에 관련 스터디를 진행할 예정이다.

## Assignments
본 스터디의 과제는 GitHub Classroom으로 진행될 예정이다.
이에 약간의 Git, GitHub 스킬을 가지고 있으면 좋으나 이 역시 스터디에서 충분히 따라올 수 있도록 설명할 예정이다.

구체적인 과제 내용 및 제출 방식은 스터디 첫 시간에 공지하도록 하겠다.

## Schedule (Tentative)
|Weeks|Topics|Assignments|
|:---:|:---:|:---:|
|Week 1|귀납적 구조를 정의하는 법, Ocaml 기초|[Assignment 1](https://classroom.github.com/a/-ZucFpOD)|
|Week 2|OCaml을 활용한 함수형 프로그래밍|[Assignment 2](https://classroom.github.com/a/m7O-j0zq)|
|Week 3|인터프리터 만들기: 식(Expressions), 함수(Procedures)||
|Week 4|인터프리터 만들기: 재귀함수(Recursion), 유효범위 규칙(Scoping Rules)|Assignment 3|
|Week 5|인터프리터 만들기: 상태(States), 포인터(Pointers)|Assignment 4|
|Week 6|더 나은 인터프리터 만들기: 간단한 타입 체계(Type System)||
|Week 7|더 나은 인터프리터 만들기: 타입 추론(Type Inference)|Assignment 5|
|Week 8|마무리: 람다 칼큘러스(Lambda Calculus), 그래서 왜 PL인가?||
