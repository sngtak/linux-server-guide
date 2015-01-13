#YUM(Yellodog Update Managemnt)

ReaHat 계열 리눅스 시스템에서 RPM 기반으로 패키지를 관리하는 하기 위한 자동 패키지 관리 도구이다. RPM을 이용한 패키지 설치에서 문제가 되던 패키지 의존성 문제를 해결하였으며 RPM을 통한 관리에 비해서 패키지 설치 및 삭제 또한 쉽게 간단하게 진행할 수 있다.

YUM은 패키지 저장소 URL을 /etc/yum.repos.d/ 에 저장한다. 패키지 설치를 위해 임시적으로 파일을 다운로드 받는 위치는 /var/cache/yum 이다. 패키지 설치가 완료되면 커널 업데이트 파일을 제외한 다른 파일들은 자동으로 삭제한다.

YUM을 통한 패키지 관리를 위해서는 관리자 계정(root)으로 로그인하거나 sudo 명령을 이용한다.

##설치된 패키지 목록 보기

```bash
$ sudo yum list installed
```

##설치된 패키지 검색하기

```bash
$ sudo yum list installed [package]
```

##패키지 설치

```bash
$ sudo yum install [package]
```

패키지 설치중에 설치를 물어보는 질문이 나올 때 자동으로 yes로 처리되길 원하면 다음과 같이 입력한다.

```bash
$ sudo yum install -y [package]
```

##패키지 업데이트

```bash
$ sudo yum update
```

패키지 업데이트를 위해 설치를 물어보는 질문이 나올 때 자동으로 yes로 처리되길 원하면 다음과 같이 입력한다.

```bash
$ sudo yum update -y
```

##패키지 삭제

```bash
$ sudo yum remove [package]
```
