# Netology_K8S_1.2 (Моисеенко А.Н.)
  
## Задание 1. Создать Pod с именем hello-world
- Установить MicroK8S на локальную машину или на удалённую виртуальную машину.
- Установить dashboard.
- Сгенерировать сертификат для подключения к внешнему ip-адресу.

### Cкриншот вывода команд kubectl get pods.    
<img width="475" height="74" alt="image" src="https://github.com/user-attachments/assets/235d1589-5156-4ff0-9568-dfb2e0cf01ea" />

### Cкриншот вывода команд curl http://127.0.0.1:8080
<img width="553" height="320" alt="image" src="https://github.com/user-attachments/assets/a37ce0ea-3fa4-4653-8831-9423a2a46617" />


## Задание 2. Создать Service и подключить его к Pod
- Создать Pod с именем netology-web.
- Использовать image — gcr.io/kubernetes-e2e-test-images/echoserver:2.2.
- Создать Service с именем netology-svc и подключить к netology-web.
- Подключиться локально к Service с помощью kubectl port-forward и вывести значение (curl или в браузере).

### Cкриншот вывода команд kubectl get pods. 
<img width="516" height="91" alt="image" src="https://github.com/user-attachments/assets/7e4417c3-a4ed-4267-a2f2-77c002c26095" />

### Cкриншот вывода команд kubectl get svc.
<img width="771" height="89" alt="image" src="https://github.com/user-attachments/assets/19d79423-d428-4c97-97cb-b10ee8138237" />

### Cкриншот вывода команд kubectl describe svc netology-svc.
<img width="644" height="295" alt="image" src="https://github.com/user-attachments/assets/3002d3a9-f067-41af-905b-c695f44f352a" />

### Cкриншот вывода команд kubectl describe svc netology-svc.





