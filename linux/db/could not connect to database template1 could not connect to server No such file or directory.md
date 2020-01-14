#  could not connect to database template1: could not connect to server: No such file or directory

> centos : postgresql 



`pgsql/data/postgresql.conf` 파일에서 `listen_addresses` 를 선언해 주자. 

```txt
listen_addresses = '*'
```

- 재시작 

  `$ systemctl start postgresql.service`

---

그런데 나의 경우 `pgsql/data`하위에 아무런 파일도 없었다. pgsql 명령어로 이 폴더에 있어야할 파일을 init 시킬 수 있다.

`$ postgresql-setup initdb`