# Specifying a namespace in include() without providing an app_name

django2.0이후 버전에서, urls파일에서 path를 설정할때 `namespace`를 설정했을 때 발생한다.

```python
path(r'^blog/', include('blog.urls', namespace='blog'))
```

`namespace`를 없애자. 그대신 `name`을 쓰면된당



<https://atez.kagamine.me/30>

