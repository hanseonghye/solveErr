# fatal error: Python.h: No such file or directory

나의 경우 `psycopg2`를 설치할때 발생한 에러이다.

찾아보니 `python dev`용 헤더파일과 라이브러리들이 설치가 안되서 그렇다고 한다.

`$ yum install python3-devel`

각자의 os 와 python 버전에 맞게 설치해 주면 된다.