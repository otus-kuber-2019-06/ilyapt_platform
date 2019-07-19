# ilyapt_platform
ilyapt Platform repository

### Домашнее задание №1
**core-dns** в отличии от, например, **kube-apiserver**, ревлизован как deployment с двумя репликами.

- Поставил и запустил minikube.
- Создал Dockerfile, собрал image и залил его на hub.docker.com.
- Создал манифест web-pod.yaml, добавил в него initContainers и volumes.
- Запустил под и сделал для него проброс портов.
- Проверил работу.
