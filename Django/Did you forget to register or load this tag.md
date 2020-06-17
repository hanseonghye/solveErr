# Did you forget to register or load this tag?

<img src=".\img\img9.png" />

`compilescss` 수행시 static 파일을 못들고오고 에러가 났다.

모든 파일에서

`{% load staticfiles %}`를 파일의 최상단에 명시해 주니 해결 됐다. (extends 다음으로 최상단 !)