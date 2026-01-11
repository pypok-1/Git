# Git
[![Snimok-ekrana-2026-01-11-214546.png](https://i.postimg.cc/44wZvRtT/Snimok-ekrana-2026-01-11-214546.png)](https://postimg.cc/dD7zvX4W)

# Помилка
- Помилку була у гілці feature-payment під час коміту Update payment logic. У процесі я випадково видалила Project: Git Practice.
- За допомогою команди git log знайшов хеш коміту, що передував помилковому. Виконала команду git reset --hard (e1b727d). Це повернуло гілку до стану до помилкового коміту
[![Snimok-ekrana-2026-01-11-220439.png](https://i.postimg.cc/cJZ0MxDS/Snimok-ekrana-2026-01-11-220439.png)](https://postimg.cc/JsTfRLV6)
- При --soft зміни залишилися в staged, при --mixed  в робочій директорії, але не staged, та при --hard - зміни були повністю видалені, і стан репозиторію збігся зі станом цільового коміту.
