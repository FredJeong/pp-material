# 채점기 사용법 #

숙제 제출하기 전에 꼭 제공된 grader를 이용하여 자가채점하세요.

## 파일 이름 ##

숙제 소문제마다 지정된 파일 이름이 있습니다. 예를 들어
```hw1-1.rkt```는 첫번째 숙제의 첫번째 문제의 파일 이름입니다. 각
파일마다 채점기가 제공됩니다. 예를 들어 ```hw1-1.rkt```의 경우
```hw1-1-grade.rkt```가 제공됩니다.

## 여러분이 해야 할 것 ##

제공된 숙제 파일, 이를테면 ```hw1-1.rkt```에는
```racket
(raise "TODO")
```
라는 부분이 있을텐데요, 여러분은 이 부분을 수정하여 제출하시면
됩니다. 다른 부분은 모두 채점이 잘 이루어지도록 작성되어 있습니다.

## 채점 ##

Racket에서 채점기 파일, 이를테면 ```hw1-1-grade.rkt```를 열고 실행하면
됩니다. ```"O"```가 나오면 성공이고, ```"X"```가 나오면 아직 정답을
찾지 못한 것입니다. ```Error: ...```는 프로그램이 잘 실행되지 않았다는
의미입니다.
