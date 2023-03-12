# pyKeksik
Библиотека для взаимодействия с API [Кексика](https://keksik.io)

[Официальная документация](https://keksik.io/api)
Библиотека была написана потому что было нечего делать, обновлять буду постоянно

# Примеры кода
```python
from pyKeksik import KeksikApi
keksik_api = KeksikApi(group_id, apikey)
# Список донатов
print(keksik_api.donates.get())
# Список краутфанденговых кампаний
print(keksik_api.campaigns.get())
# Список выплат
print(keksik_api.payments.get())
# Баланс
print(keksik_api.balance())
```
# В планах:
 > Реализовать прием callback
