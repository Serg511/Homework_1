## Homework_1 - Первый Terraform скрипт

Данный Terraform-стенд развертывает одну виртуальную машину в Yandex Cloud, внутри которой с помощью Ansible запускается Nginx.

### Используемые инструменты:

* Git
* Ansible
* Terraform

### Порядок запуска:

1. Скопировать данный репозиторий ```git clone <this repo>```
2. Сгенерировать открытый и закрытый ключ для доступа к виртуальной машине ```ssh-keygen``` 
3. Отредактировать файлы ```meta.txt``` и ```terraform.tfvars```
4. Последовательно выполнить команды ```terraform init``` ```terraform plan``` ```terraform apply```