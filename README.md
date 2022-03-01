# devops-netologyFirst string to Readme file


# Игнорировать все файлы расположенные в локальной директории .terraform
**/.terraform/*

# Игнорировать файлы с расширением .tfstate и любые файлы отвечающие маске *.tfstate.* - вместо звездочки могут быть любые символы
*.tfstate
*.tfstate.*

# Игнорировать файлы crash.log и файлы имеющие соответствующие маске crash.*.log - вместо звездочки могут быть любые символы
crash.log
crash.*.log

# Игнорировать любые файлы с расширениями *.tfvars и *.tfvars.json
*.tfvars
*.tfvars.json

# Игнорировать файлы override.tf и override.tf.json или файлы с любыми предыдущими символами для *_override.tf и *_override.tf.json
override.tf
override.tf.json
*_override.tf
*_override.tf.json

# Ниже игнорировать файлы с расширением .terrarormrc или сам файл terraform.rc
.terraformrc
terraform.rc

# Новая строчка для задания №3 - Ветки
# Задание №4 – Упрощаем себе жизнь
# Еще одна запись в README
