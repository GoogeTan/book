description: Подключение скина своего оффициального аккаунта при разработке модов.

# Скин с оффициального аккаунта

Если у вас есть купленная Minecraft лицензия, то вы можете указать в параметрах
запуска свою почту/пароль. В этом случае, ваш никнейм + скин автоматически загрузятся
при запуске. Отройте файл build.gralde, там найдите `run { ....`. В графе client найдите строку args добавьте `'--username=test@mail.ru', '--password=your_password'`, если такой строки нету, то добавьте: ```args '--username=test@mail.ru', '--password=your_password'```
В конце должно получиться примерно так:

![Картинка билд градла](images/build.gradle.png)

