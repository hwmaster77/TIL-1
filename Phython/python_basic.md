# 파이썬(PYTHON)

## 목차

[1.문자의 표현](#문자의-표현)  
[2.통합 개발 도구](#통합-개발-도구)  
[3.조건문](#조건문-Conditional-Statements)

## 문자의 표현

문자열이란 문자,단어 등으로 구성된 문자들의 집합을 의미한다.

아래와 같이 문자열을 만들 때 큰따옴표("")만을 사용합니다.
작은따옴표를 포함시켜 출력시키고 싶다면 큰따옴표 안에 world라는 문자를 작은따옴표로 묶어준다면 Hello 'world'라는 문자열을 출력하게 된다.
![](./images/img03.png)

## 통합 개발 도구

통합 개발 도구 (IDE)를 이용하여 생산성을 늘리는 것도 중요하다.

참고사이트

- https://www.jetbrains.com/pycharm/
- https://www.jetbrains.com/ruby/

개발도구는 정보산업의 미래이다. 왜냐하면 일반인도 사용하기 쉽도록 편리하고 쉽게 가다듬어서 만든 도구들이 굉장히 많다. 고급사용자들이 모여있는 곳에서 테스트되는 도구가 바로 개발도구이기 때문에 거기에 인정받은 도구를 일반인들도 사용하게 했을 때 큰 기회를 얻을 수 있는 측면이 있다.

## 조건문 (Conditional Statements)




## 문자열 인덱싱과 슬라이싱

인덱싱(Indexing)이란 무엇이가를 '가리킨다'라는 의미이고, 슬라이싱(Slicing)은 무엇인가를 '잘라낸다'라는 의미이다.

### 1. 문자열 인덱싱 활용하기

'파이썬은 0부터 숫자를 센다' 처럼 첫번째 문자는 0부터 세어야 한다.

![](./images/img07.jpg)

### 2. 문자열 슬라이싱이란

단순히 한문자만을 뽑아내는 것이 아니라 'Lift' 또는 'you' 같은 단어를 뽑아내는 방법

![](./images/img08.jpg)

#### 응용 : Pithon이라는 문자열을 Python으로 바꾸려면?

슬라이싱을 사용하면 Pithon의 'P'부분과 'thon'부분으로 나눌 수 있기 때문에 그 사이에 'y'문자를 추가하여 'Python'이라는 새로운 문자열을 만들 수 있다.

![](./images/img09.jpg)

### 4. 문자열 포매팅

문자열 안에 어떤 값을 삽입하는 방법

### 4.1 문자열 포매팅 따라하기

#### 숫자 바로 대입

아래 결과값 처럼 정수 3을 삽입하는 방법으로, 문자열 안에 숫자를 넣고 싶은 자리에 %d문자를 넣어주고 삽입할 숫자 3은 가장 뒤에있는 %문자 다음에 써 넣었다. 여기에서 %d는 문자열 포맷코드라고 부른다.

![](./images/img10.jpg)

#### 문자열,숫자 값 나타내는 변수, 2개 이상의 값 넣기

2개 이상의 값을 넣으려면 마지막 % 다음 괄호 안에 콤마(,)로 구분하여 각각의 값에 넣어 주면 된다.

![](./images/img11.jpg)

### 4.2 문자열 포맷 코드

3이나 3.232 삽입할때 %d, %f로 구분할 필요 없이 %s 구분코드를 사용하면 한번에 포맷해주기 때문에 편리하다. 왜냐하면 %s는 자동으로 %뒤에 있는 값을 문자열로 바꾸기 때문이다.

![](https://image.slidesharecdn.com/pythonstudy2-180730214924/95/-13-638.jpg?cb=1532987640)

### 4.3 포맷코드와 숫자 함께 사용하기

#### 정렬과 공백

%10s는 전체 길이가 10개인 문자열 공간에서 대입되는 값을 오른쪽으로 정렬하여 그 앞의 나머지는 공백으로 남겨두라는 의미이다.  
 (반대쪽의 왼쪽정렬은 %-10s가 될 것이다.)

![](./images/img12.jpg)

### 4.4 format함수를 사용한 포매팅
