# devops-netology
# Игнорируемые файлы

В репозитории настроены правила игнорирования в файле `.gitignore`:

# Общие правила:
- Файлы IDE (`.idea/`, `.vscode/`)
- Временные файлы (`*.tmp`, `*.temp`)
- Системные файлы (`.DS_Store`, `Thumbs.db`)

# Терраформ правила (в каталоге `terraform/.gitignore`):
- Файлы состояния: `*.tfstate`, `*.tfstate.*`
- Логи аварийных завершений: `crash.log`
- Файлы переменных: `*.tfvars`, `*.tfvars.json`
- Файлы переопределений: `override.tf`, `override.tf.json`, `*_override.tf`, `*_override.tf.json`
- Файлы конфигурации: `.terraformrc`, `terraform.rc`
- Кэш-каталоги: `.terraform/`
