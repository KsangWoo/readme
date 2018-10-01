

## 1. 제목 


(h1)부터 (h6)까지 제목을 표현 (글머리)


# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6


제목1(h1)과 제목2(h2)는 다음과 같이 표현 (큰제목, 작은 제목)

제목 1
======

제목 2
------



## 2. BlockQuote
이메일에서 사용하는 ```>``` 블럭인용문자를 이용한다.
```
> This is a blockqute.
```
> This is a first blockqute.
>	> This is a second blockqute.
>	>	> This is a third blockqute.

이 안에서는 다른 마크다운 요소를 포함할 수 있다.
> ### This is a H3
> * List
>	```
>	code
>	```

## 3. 목록
### ● 순서있는 목록(번호)
순서있는 목록은 숫자와 점을 사용한다.

1. 첫번째
2. 두번째
3. 세번째

**현재까지는 어떤 번호를 입력해도 순서는 내림차순으로 정의된다.**

1. 첫번째
3. 세번째
2. 두번째

## 3. 강조
```
**
__
**double asterisks**
__double underscores__
++underline++
~~cancelline~~
```

*single asterisks*
_single underscores_
**double asterisks**
__double underscores__
++underline++
~~cancelline~~

### 4. 순서없는 목록(글머리 기호)
```
* 빨강
  * 녹색
    * 파랑

+ 빨강
  + 녹색
    + 파랑

- 빨강
  - 녹색
    - 파랑
```
* 빨강
  * 녹색
    * 파랑

+ 빨강
  + 녹색
    + 파랑

- 빨강
  - 녹색
    - 파랑

혼합해서 사용하는 것도 가능하다.
```
* 1단계
    - 2단계
    	+ 3단계
            = 4단계
```

* 1단계
    - 2단계
    	+ 3단계
			= 4단계


## 5. 코드```<pre><code></code></pre>```
4개의 공백 또는 하나의 탭으로 들여쓰기를 만나면 변환되기 시작하여 들여쓰지 않은 행을 만날때까지 변환이 계속된다.



```
This is a normal paragraph:

    This is a code block.
end code block.
```

<code>
```
This is a normal paragraph:
    This is a code block.
end code block.
```
</code>


This is a normal paragraph:

    This is a code block.
end code block.


## 6. 수평선```<hr/>```
아래 줄은 모두 수평선을 만든다. 마크다운 문서를 미리보기로 출력할 때 *페이지 나누기* 용도로 많이 사용한다.
```
* * *

***

*****

- - -

---------------------------------------
```

* * *

***

*****

- - -

---------------------------------------
