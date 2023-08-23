# shuf란?

문자열을 섞을때 쓰는것이다.


100까지의 숫자를 랜덤하게 출력하고 10개를 뽑아오기
``` bash
shuf -i 1-100 -n 10
```

100까지의 숫자를 랜덤하게 출력하고 10개를 뽑아오고 무한반복

``` bash
shuf -i 1-100 -n 10 -r 
```

위 내용을 무한루프가 아닌 10번 반복
``` bash
shuf -i 1-100 -n 10 -r  10
```