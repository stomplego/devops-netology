# Правила игнорирования файлов в .gitignore для terraform:

1. **`*.tfstate`** - игнорируются все файлы, заканчивающиеся на `.tfstate`.
2. **`*.tfstate.*`** - игнорируются файлы, содержащие в имени `.tfstate.`.
3. **`crash.log`** - игнорируется файл с именем `crash.log`.
4. **`*.tfvars`** - игнорируются все файлы с расширением `.tfvars`.
5. **`*.tfvars.json`** - игнорируются все файлы с расширением `.tfvars.json`.
6. **`.terraformrc`** - игнорируется файл с именем `.terraformrc`.
7. **`terraform.rc`** - игнорируется файл с именем `terraform.rc`.
8. **`.terraform/`** - игнорируется каталог `.terraform/` и всё его содержимое.
9. **`override.tf`** - игнорируется файл с именем `override.tf`.
10. **`override.tf.json`** - игнорируется файл с именем `override.tf.json`.
11. **`*_override.tf`** - игнорируются файлы, заканчивающиеся на `_override.tf`.
12. **`*_override.tf.json`** - игнорируются файлы, заканчивающиеся на `_override.tf.json`.
