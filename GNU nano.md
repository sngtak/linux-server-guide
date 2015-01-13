#GNU nano

GNU nano 는 Pico 를 대체하기 위해서 배포되는 무료 텍스트 에디터이다. vi 편집기에 비해서 쉽고 빠르게 사용이 가능하기 때문에 간단한 시스템 설정에서부터 프로그램 소스 작성까지 널리 사용되고 있다.

##실행

```bash
$ nano {파일명}
```

시스템 설정에 관련된 설정 파일을 수정할 때는 `-w` 또는 `--nowrap` 옵션을 사용하도록 한다.

```bash
$ nano -w {파일명}
```

##단축키

Control | Key
--- | ---
Ctrl + K | 자르기
Ctrl + U | 붙여넣기
Ctrl + ^ | 블럭지정
Ctrl + G | 도움말 보기
Ctrl + R | 파일 열기
Ctrl + F | 파일리스트 보기
Ctrl + O | 저장
Ctrl + X | 끝내기
Alt + I | 자동 들여쓰기
