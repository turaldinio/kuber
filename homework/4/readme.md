само дз :

![dz.png](resources%2Fdz.png)

тут вроде все понятно. для начала описал файлики crd и mysql

применяем сперва crd потом mysql

проверим что все работает :

![example_1.png](resources%2Fexample_1.png)

красиииво 

далее сделаем так :

```
kubectl proxy --port=8080
```

запустились локально и шо видим:

ожидаем что вернется json с ресурсами нашими

![example_2.png](resources%2Fexample_2.png)

veni vidi vichi - пришел увидео победил, красиво , работает 

больше с кубером общаться не хочется..