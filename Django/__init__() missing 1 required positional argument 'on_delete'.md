# __init__() missing 1 required positional argument: 'on_delete'

![img](./img/img8.png)

장고 2.0? 버전 부터 model 작성시 `ForeignKey`를 사용할때는 `on_delete`요소를 넣어줘야 한다고 한다.



```python
album = models.ForeignKey(Album, on_delete=models.CASCADE, )
```



### CASCADE

FK에 해당하는 값이 삭제 됐을때 어떻게 처리할지 명시해주는 것.