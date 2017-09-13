doitR/gangbuk/sep-2017/chapter03\_04
================

<br>

Chapter3. 데이터분석을 위한 연장 챙기기
---------------------------------------

<p>
<br>

<font color='red', size=5> 03-1. 변수 만들기
</font>

<br>

<font color='black', size=4> &gt; 변수 'a'에 '1'이라는 값을 할당한다! </font>

![png002](/Users/Gs/Pictures/002.png) <br>

``` r
a <- 1   # a에 1을 할당하라
```

<font color='black', size=4> &gt; 반응이 없다? </font>

``` r
a    # a를 보여줘
```

    ## [1] 1

<font color='black', size=4> &gt; 또는 </font>

``` r
print(a)    
```

    ## [1] 1

<font color='blue', size=4> &gt; quiz! : 출력된 \#\# \[1\] 1에서 '\[1\]'은 어떤 의미일까요? </font>

``` r
#
```

<br> <font color='black', size=4> &gt; 아래의 코드를 입력하고 실행해보세요~ </font>

``` r
a <- 1
b <- 2
c <- 3

a+b
a+b+c
4/b
5*b
```

<font color='blue', size=4> &gt; 변수명은 영문으로 시작 <br> &gt; 대소문자 구분<br> &gt; 숫자/ -/ \_ 의 조합가능<br> &gt; 한글명은 지양 </font> <br>

<font color='black', size=4> &gt; 여러개의 값으로 구성된 변수 만들기 </font> <font color='black', size=4> &gt; 아래의 코드를 입력하고 실행해보세요~ </font>

``` r
# c = combine 

var1 <- c(1,2,5,7,8)     # temp <- 1,2,3,4,5     이렇게 입력하면?
var1

var2 <- c(1:5)           # temp <- 1:5     이렇게 입력하면?
var2

var3 <- seq(1, 5)        # temp <- c(seq(1,5))     이렇게 입력하면?
var3

var4 <- seq(1, 10, by=2)
var4

var1
var1 + 2

var1                     # 조금전에 'var1 + 2'을 했었는데 왜 var1의 값은 변하지 않고 그대로일까?
var2
var1 + var2
```

<br> <font color='blue', size=4> &gt; quiz! : 아래 코드를 실행하면 어떻게 될까요? </font>

``` r
temp1 <- c(1,2)
temp2 <- c(1,1,1,1,1)

temp1 + temp2
```

<br> <font color='blue', size=4> &gt; quiz! : 아래 코드를 실행하면 어떻게 될까요? </font>

``` r
temp3 <- rep(1, 5)
```