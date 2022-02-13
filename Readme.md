### 2월 14일 과목평가 준비

---

공부해야할 내용

> Array, String 
>
> Stack, Queue
>
> Linkedlist
>
> Tree



### Array

---

재귀함수 작성법

- 팩토리얼 계산
- n개 중 k 개를 뽑는 조합의 경우의 수 계산(재귀)
- 입력값 n이 커질수록 재귀 알고리즘은 반복에 비해 비효율적일 수 있다.
- 하노이의 탑

2차원 배열

> 행 우선 탐색
>
> 열 우선 탐색
>
> 지그재그 순회
>
> 델타를 이용한 2차원 배열 4방 탐색

<br/>

<br/>

### 완전 검색(Exhaustive Search)

---



**순열(Permutaion)**

=> 일반적으로 서로다른 N개의 원소 중에서 R개를 뽑아 **한줄로 나열**하는 방법, 알고리즘 분석 기법 중 완전탐색 부분에 해당한다. 서로다른 N명의 후보 중에서 R명을 뽑아 한줄로 줄을 세우는데 뽑힌 사람이 누구인지도 중요하지만 순열에서 가장 중요하게 생각해야하는 부분은 뽑힌 사람들이 어느 위치에 배치시키느냐이다. 뽑힌 R명의 사람을 줄을 세울 때 서있는 위치가 바뀌는 경우를 모두 다른 경우로 카운팅 해야한다. 

반복문을 사용해서 코드를 작성할 수도 있지만, 뽑아야하는 사람 수에 따라서 반복문이 여러번 겹쳐야 하기 때문에 고정적이지 않은 변수에 대해서 처리하기 어려운 부분이 생긴다. 따라서 재귀적으로 줄을 세우기 위해 뽑힌 사람의 수를 체크해가며 가능한 모든 방법을 탐색해야한다.

<br/>



**조합(Combination)**

=> 일반적으로 서로다른 N개의 원소 중에서 R개를 **순서없이** 뽑는 가지수를 의미하고, 알고리즘 분석 기법 중 완전탐색 부분에 해당한다. 서로다른 N명의 후보 중에서 R명을 뽑는 경우로 

<br/>



**부분집합(Subset)**

=> 집합에 포함된 원소들을 선택하는 것이다. 다수의 중요 알고리즘들이 원소들의 그룹에서 최적의 부분 집합을 찾는 것이다.

부분집합의 수를 계산할 때 원소의 개수가 N개인 집합에서 만들 수 있는 부분집합의 개수는 2^N개 이다. 이는 각 원소를 부분집합에 포합시키거나 포합시키지 않는 2가지 경우를 모두 원소에 적용한 경우의 수 즉 아무 원소도 선택되지 않는 부분집합 부터 모든 원소가 포함되어있는 부분집합을 의미한다. 

ex) N개의 원소 중 가방에 몇가지 원소를 가방에 집어넣을 때 가방에 들어갈 수 있는 종류의 집합

<br/>

<br/>



### stack

---

stack의 특성

- 물건을 쌓아 올리듯 자료를 쌓아올린 형태의 자료구조스택에 저장된 자료는 **선형 구조**를 갖는다. 
- 선형구조 : 자료 간의 관계가 **1대 1**의 관계
- 비선형 구조 : 자료 간의 관계가 **1대 N**의 관계
- 후입선출구조(**LIFO**, Last in first out) => 나중에 들어간 원소가 먼저 나온다.

주요연산

-  push
- pop
- peek

 대표적인 문제

- 괄호 검사, Function Call, 계산기(중위표기식 => 후위표기식으로 변환)

<br/>

<br/>



### Queue

---



**Queue의 특성**

- 
