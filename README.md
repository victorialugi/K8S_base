# Домашнее задание к занятию "`Базовые объекты K8S`" - `Лугинина Виктория`
   
### Задание 1

**Манифест:** [hello-world.yaml](./hello-world.yaml)

Команды:
```bash
kubectl apply -f hello-world.yaml
kubectl get pods

![]()

Подключение:
Bashkubectl port-forward pod/hello-world 8080:8080
curl localhost:8080

![]()


---

### Задание 2

**Манифесты:**
- [netology-web.yaml](./netology-web.yaml)
- [netology-svc.yaml](./netology-svc.yaml)

Команды:
```bash
kubectl apply -f netology-web.yaml
kubectl apply -f netology-svc.yaml
kubectl get pods
kubectl get svc

![]()

kubectl port-forward service/netology-svc 8080:80
curl localhost:8080

![]()
