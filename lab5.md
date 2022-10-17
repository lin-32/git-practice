# IO Redirection
I=input
O=Output
---
#### Standard Output
```
1. >
다른 출력값으로 Redirect
그리고 출력된 파일은 존재하지 않을 경우 자동으로 생성되며, 
만약 이미 존재할 경우에는 기존 파일에 덮어쓰게(overwrite) 된다

2. >>
리다이렉트된 출력 데이터가 파일에 덮어씌워지는(overwritten) 것이 아니라 
기존 컨텐츠에 출력 데이터가 추가(append)되는 것을 원할 경우 사용

3. <
입력 리다이렉션(input redirection)을 위해 사용
```

#### Pipelines 
```
|
명령어의 표준 출력을 또다른 명령어의 표준 입력과 연결
ex. command1 | command2 | command3
```

#### Expansion
```
1. echo 
echo뒤 텍스트 그대로 출력
2. echo *
스타(*) 프린트 하지 않고, 모든 하위 파일명 반환 
3. echo ~ 
현재 사용자의 최상단 폴더 반환 
```

#### Backslash
```
\
가독성을 위해 사용, 긴 한 줄을 여러 줄로 표현가능 
(화면상 문자 다르게 나옴. 어쨌든 백슬래시) 
```

#### Permissions

![permission](https://t1.daumcdn.net/cfile/tistory/2021964D4E509E8605). 

문자형식 구분 (1)
```
d: 디렉토리
l: 링크
-: 파일
```
 소유자 권한 (2)
```
r = read: 읽기가능
w = write: 쓰기가능
x = excute: 실행가능
```
그룹권한 (3) / 그 외 사용자 (4)

참고 _ 퍼미션 숫자값
```
- = 0
r = 2^2 = 4
w = 2
x = 1
```

#### History
이전 커멘드 타입 확인 후 다른 파일에 저장
```
ex. 
$ history > history_command.txt
$ cat history 파일명
```
