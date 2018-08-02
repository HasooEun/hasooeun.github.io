---
layout: post
comments: true
title:  "Python Overview"
date:   2018-08-01 12:59:45 +0900
categories: programming python
---
## 파이썬 개요


### 파이썬의 특징

1. 인터프리터 언어이다. 
인터프리터 언어란 한 줄씩 소스 코드를 읽어서 그때그때 실행한 결과를 확인할 수 있는 언어이다.

2. 접착(glue) 언어라고도 부른다. C/C++로 만든 프로그램을 파이썬에서 사용하거나, 파이썬으로 만든 프로그램을 C/C++에서 사용할 수 있다.

3. 괄호({})가 없다. 기존 언어에서는 변수나 메소드가 영향을 줄 수 있는 범위를 한정하기 위하여 괄호를 사용하였다. 하지만 파이썬에서는 들여쓰기만으로 구분한다. 따라서 개발하는 과정에서 들여쓰기에 신경을 써주어야 한다.

### 파이썬의 단점

1. 시스템을 건드려야 하는 프로그램에는 어울리지 않는다.

### 사칙연산

사칙연산은 일반 계산기 사용하듯 할 수 있다.

{% highlight python %}
>>> 1 + 2
3
>> 5 - 1
4
>>> 3 / 2.4
1.25
>>> 3 * 9
27
{% endhighlight %}

### 변수

변수란 특정한 값을 저장해두고 사용할 수 있는 공간이다.

파이썬에서는 변수를 생성할 때 선언(저장될 값이 어떤 형태인지 미리 알려주는 것) 없이 바로 사용할 수 있다.

{% highlight python %}
>>> a = 1
>>> b = 2
>>> a + b
3
>>> c = "Python"
>>> print(c)
Python
>>> d = 2+3j
>>> e = 3
>>> d * e
(6+9j)
{% endhighlight %}

### 제어문

파이썬에서 제어문과 함수를 사용할 때에는 들여쓰기에 주의한다.

이때 사용하는 들여쓰기가 다른 언어의 중괄호를 대신해 준다.

{% highlight python %}
>>> a = 3
>>> if a > 1:
    print("a is greater than 1")

a is greater than 1
>>> for a in [1, 2, 3]:
    print(a)

1

2

3
>>> def sum(a, b):
    return a+b
{% endhighlight %}

### 함수

함수는 명령어들의 집합이다.

파이썬에서 함수를 정의할 때에는 def키워드를 사용한다.

정의된 함수는 이름과 인자를 통해 사용할 수 있다.

{% highlight python %}
>>> print(sum(1,2))
3
{% endhighlight %}

### 주석

한 줄짜리 주석을 사용할 때에는 #키워드를 사용한다.

여러줄 주석을 사용할 때에는 문장의 시작과 끝을 """로 감싸준다.

{% highlight python %}
# inline comment

"""
multi-line comment
여러줄 주석 입니다
"""
{% endhighlight %}

참고도서: 박응용, '점프 투 파이썬,' 이지스 퍼블리싱, 2017년 7월 31일.

{% if page.comments %} 


{% endif %}