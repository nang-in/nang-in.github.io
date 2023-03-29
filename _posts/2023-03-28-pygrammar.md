---
layout: post
title: "python grammar"
subtitle: this is note about python basic grammar
cover-img: /assets/img/ptrhon.png
thumbnail-img: /assets/img/my room.jpg
share-img: /assets/img/ptrhon.png
tags: [study, python]
---

# 파이썬 자료형

## -숫자형

#### 숫자형 - int(정수형),float(실수형),complex(복소수)가 있다.

_________________________________________________________

### integer - 정수형

~~~python
a = -100
b = 0
c = 100
~~~



#### 정수형의 크기는 컴파일러가 아닌 컴퓨터 메로리로 제한된다. (파이썬 3) arbitrary-precision로 가용 메모리 사용 -> byte 늘림 (단, pydata stack을 활용하는 numpy|pandas 패키지는 오버플로우 발생 고려)

------------------------------------------------------------------------

### float - 실수형

~~~python
import math

a = 1.234
b = -1.234
c = math.pi //3.14~
~~~



#### e나E를 사용하여 지수표기법이 사용가능 한다.(지수표기법 잘 모름)
