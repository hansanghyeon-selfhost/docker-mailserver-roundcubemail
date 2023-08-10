## [docker-mailserver](https://github.com/docker-mailserver/docker-mailserver)

> 단순한 컨테이너화된 메일서버(SMTP, IMAP, LDAP, 안티스팸, 안티바이러스) 구성파일만 있고 SQL 데이터베이스는 없습니다. 간단하고 버전을 유지하십시오. 배포 및 업그레이드가 쉽습니다.

정말 핵심!

```sh
docker exec -it {CONTAINER_ID} setup help
```

```sh
docker-compose up -d
```

이렇게 컨테이너가 띄워졌을때

```sh
docker exec -it {CONTAINER_ID} setup email admin@example.com 1234
```

## [roundcubemail](https://roundcube.net/) (optional)

응용프로그램과 유사한 사용자 인터페이스가 있는 브라우저 기반 다국어 IMAP 클라이언트입니다. MIME 지원, 주소록, 폴더 조작, 메시지 검색 및 맞춤법 검사를 포함하여 이메일 클라이언트에서 기대하는 모든 기능을 제공합니다.