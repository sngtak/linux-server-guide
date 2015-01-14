#vsftpd(very secure FTP daemon)

##Official Site

https://security.appspot.com/vsftpd.html

##Ubuntu

###설치

```bash
$ sudo apt-get install vsftpd
```

###설정

```bash
$ sudo nano /etc/vsftpd.conf
```

anoymous(익명 사용자) 로그인 금지

```
anonymous_enable=NO
```

local user 접속 허용

```
local_enable=YES
```

local user의 파일 업로드 허용

```
write_enable=YES
```

###vsftpd 시작

```bash
$ sudo service vsftpd start
```

###vsftpd 중지

```bash
$ sudo service vsftpd stop
```

###vsftpd 재시작

```bash
$ sudo service vsftpd restart
```

###포트 변경

```bash
$ sudo nano /etc/vsftpd/vsftpd.conf
```

내용 추가

```
listen_port=1235
```

##Fedora