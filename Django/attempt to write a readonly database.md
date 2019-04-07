# attempt to write a readonly database

`admin`페이지에서 로그인할때 발생하는 에러로

user가 `db.sqlite3` 에 write할 권한이 없기 때문에 발생한다.

권한을 주자!

> chmod a+w db.sqlite3