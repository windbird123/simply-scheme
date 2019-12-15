## 개요 
[simply-scheme](https://people.eecs.berkeley.edu/~bh/ss-toc2.html) 정리
## 연습 환경
### 기본 (simply.scm)
* windows dr.racket 설치
* file > install package 에서 "simply-scheme" 설치
* 코드
  ```scheme
  #lang simply-scheme
  
  (word 'a 'b)
  ```
### simply-scheme 에서 제공하는 다른 .scm 파일 로드
* dr.racket 에서는 load 가 잘 안되는 것 같으니, 그냥 ubuntu 에 환경을 구성
* ubuntu 에서 아래와 같이 mit-scheme 설치
  > apt-get install mit-scheme
* scheme 명령어로 실행 후
  ```scheme
  (load "simply.scm")
  (load "match.scm")
  
  (match '(*start me *end) '(love me do))
  ```
