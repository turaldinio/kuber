само дз

![dz.png](manifests%2Fresources%2Fdz.png)


разобрался
не хватало конфига для nginx

итоговый результат:

![img.png](manifests%2Fresources%2Fimg.png)

как запускать этого шайтана:
1) установим у метку ```kubectl apply -f .\homework/1/manifests/namespace.yaml```
2) длаее последовательно применяем :

```
kubectl apply -f  .\homework\2\manifests\pvc.yaml
kubectl apply -f  .\homework\2\manifests\cm.yaml
kubectl apply -f  .\homework\2\manifests\nginx-config.yaml
kubectl apply -f  .\homework\2\manifests\deployment.yaml
kubectl apply -f  .\homework\2\manifests\service.yaml
kubectl apply -f  .\homework\2\manifests\ingress.yaml
```

![img.png](img.png)

такой вывод это значит шо все четко , молодцом и все готов к работе. 