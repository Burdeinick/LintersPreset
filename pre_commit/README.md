### Установка "pre-commit":
Установить pre-commit:
- ```pip install pre-commit==<need_version>```
- положить в корень проекта ```.pre-commit-config.yaml```
- выполнить команду: ```pre-commit install```

Чтобы не "дёргать" сommit можно выполнять команду для проверки:
```pre-commit run --show-diff-on-failure --color=always --all-files```