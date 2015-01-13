#Pico

Pico (Pine Composer)는 Pine e-mail client 에 내장되어 있던 것을 미국 워싱턴대학에서 동일한 방식으로 개량해서 만든 유닉스와 유닉스를 기반으로 하는 시스템에서 사용되는 텍스트 에디터이다. 

##Pico 실행

```bash
$ pico 
```

```bash
$ pico {파일명}
```

##Pico 도움말

pico 프로그램은 작업에 따른 각각의 도움말을 보여준다. `Ctrl + G` 또는 `F1` 을 누르면 현재 하고 있는 작업에 따른 도움말을 볼 수 있으며 화면 아래쪽의 명령어 행이 도움말 모드에서 사용되는 명령으로 변경된다. 도움말 모드 종료는 `Ctrl + X` 이다.

Control | Key	Function | Key
--- | --- | ---
Ctrl + G | F1 | 도움말 출력


##이동 단축키

pico는 `방향키`와 `단축키`를 모두 사용할 수 있다.

Control | Key	Function | Key
--- | --- | ---
Ctrl + F | &nbsp; | 한문자 앞으로 이동
Ctrl + B | &nbsp; | 한문자 뒤로 이동
Ctrl + P | &nbsp; | 이전 행으로 이동
Ctrl + N | &nbsp; | 다음 행으로 이동
Ctrl + A | &nbsp; | 현재 행의 처음으로 이동
Ctrl + E | &nbsp; | 현재 행의 끝으로 이동
Ctrl + V | F8 | 다음 화면으로 이동
Ctrl + Y | F7 | 이전 화면으로 이동

##편집 단축키

Control | Key	Function | Key
--- | --- | ---
Ctrl + D | &nbsp; | 커서가 위치한 문자 삭제
Ctrl + ^ | &nbsp; | 블록 설정
Ctrl + K | F9 | 현재 행 삭제
Ctrl + U | F10 | `Ctrl + K` 취소, 삭제 내용 복구
Ctrl + I | F4 | 커서가 위치한 곳에 탭(Tab) 입력
Ctrl + J | F4 | 빈 줄 또는 들여쓰기로 구분 단락이 되도록 문장을 자동 정렬
Ctrl + T | F12 | 철자 검사, 철자 검사 취소는 `Ctrl + C`를 누름

##기타 단축키

Control | Key	Function | Key
--- | --- | ---
Ctrl + W | F6 | 대소문자 구별하지 않는 문자열 검색
Ctrl + L | &nbsp; | 화면 새로 고침
Ctrl + C | F11 | 커서 위치에 대한 정보(행 번호, 문자 수) 출력
Ctrl + R | F5 | 커서 위치에 외부 파일 내용을 추가
Ctrl + O | F3 | 파일 저장
Ctrl + X | F2 | 저장 및 종료
