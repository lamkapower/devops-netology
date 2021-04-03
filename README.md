# devops-netology
## Описание действий файла terraform/.gitignore
1. Игнорирует дирректироии terraforn для внутреннего использования
2. Игнорирует файлы с раширением .tfstate .tfvars .terraformrc
3. Игнорирует файлы crash.log terraform.rc
4. Также игнорируются следующие файлы содержащие в названии "override.tf" и "override.tf.json":
    * override.tf
    * override.tf.json
    * *_override.tf
    * *_override.tf.json
-------------------------