# Сервис рекомендаций Boojum :cactus:
### После каждого пула затираем бд
```
#!mongo
use boojom
db.dropDatabase()
```
регистрируем юзера, добавляем пару тегов и объектов из вики или ластфм(оттуда текст моет парситься заметно долго после клика на submit)

## Зависимости

flask
pymongo
bson.json_util
werkzeug
faker


## Сгенерисровать временные данные базы для тесирования (осторожно, сначала стирает базу тегов и объектов)

python fixtures.py