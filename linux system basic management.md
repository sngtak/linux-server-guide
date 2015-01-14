# 리눅스 기본

## Ubuntu

### 패키지 인덱스 정보를 업데이트

`/etc/apt/sources.list`의 정보를 업데이트한다.

```bash
$ sudo apt-get update
```

### 설치된 패키지 업그레이드

```bash
$ sudo apt-get upgrade
```

##CentOS

###패키지 업데이트 목록 확인

```bash
$ sudo yum list updates 
```

### 설치된 패키지 업그레이드

```bash
$ sudo yum update –y 
```