### Установка "black" в Pycharm:
Лучше устанавливать в уже созданное вируальное окружение проекта:
```pip install black==<need_version>``` 

Добавить "black" в External Tools проекта. 
![black_external_tools.png](img%2Fblack_external_tools.png)

Если необходимо чтобы "black" правил код мнгновенно - при изменении файла:
![black_watchers.png](img%2Fblack_watchers.png)

При дополнительной необходимости black можно конфигурировать. Пример конфига pyproject.toml