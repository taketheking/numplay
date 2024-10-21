# numplay
 


## 요구사항
--- 

LV.1

### 1. 정답 숫자 생성

1) 정답은 서로 다른 3자리 수
2) 각 자리는 1~9 사이의 숫자이고 0은 사용x
3) 숫자 중복 x

### 2. 숫자 입력 받기

 1) 서로 다른 3자리 숫자 입력
 2) 숫자 중복x
  3) 문자 입력x -> 숫자만 입력o

### 3. 결과값 출력 및 게임 로직 적용

#### 1) 정답과 입력값 비교 -> 볼, 스트라이크, 아웃 표시
    
    - 스트라이크 : 입력값과 정답을 비교해 같은 자리에 같은 숫자가 있는 경우
    - 볼 : 숫자는 같지만, 자리는 다른 경우
    - 아웃 : 숫자도, 자리도 다른 경우

#### 2) 입력한 3자리 숫자가 정답과 같으면 게임 종료
    
  - ‘3 스트라이크’라면, 정답에 해당합니다

#### 3) 올바르지 않은 입력값 확인 -> 오류 문구
   1. 문자 입력
    
   2. 중복되는값
      
   3. 3자리 숫자 외의 숫자
    
