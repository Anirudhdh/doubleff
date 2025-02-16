**How to 2 profile the FF(Linux)**

1. delete or rename ~/.mozilla if it exists
2. clone the repo into ~/.mozilla
3. transfer the shortcuts to the ~/Desktop and give it an access to run


**2 профиля ФФ без смс**

1. удаляем или переименовываем существующий ~/.mozilla
2. клонируем реп в ~/.mozilla
3. переносим ярлыки на рабочий стол и кликаем разрешить запуск

```
rm -fr ~/.mozilla
git clone https://github.com/Anirudhdh/doubleff.git ~/.mozilla
mv ~/.mozilla/firefox-bin* ~/Desktop/
```
