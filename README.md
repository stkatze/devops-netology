# devops-netology
Проект для выполнения домашнего задания по теме "Системы контроля версий".

Папки и файлы, которые игнорируются
1. Локальные директории Terraform

.terraform/ — вся папка с локальными копиями провайдеров и модулей.

2. Файлы состояния (state)

*.tfstate — любые файлы состояния, например terraform.tfstate.

*.tfstate.* — резервные копии и связанные файлы, например terraform.tfstate.backup.

3. Файлы crash-логов

crash.log

crash.*.log — например crash.12345.log.

4. Файлы переменных (могут содержать секреты)

*.tfvars — например terraform.tfvars, prod.tfvars.

*.tfvars.json — например terraform.tfvars.json.

5. Override-файлы (локальные переопределения)

override.tf

override.tf.json

*_override.tf — например example_override.tf.

*_override.tf.json — например example_override.tf.json.

6. Файл блокировки состояния

.terraform.tfstate.lock.info — создаётся во время terraform apply.

7. Файлы конфигурации CLI

.terraformrc

terraform.rc
Новая строка, добавленная в ветке fix
