# CacTusEngine

Начнем с того, что я не имею никакого опыта в создании игровых движков и маленький опыт разработки на C++.
Тем не менее мне интересна эта тема и я начинаю разработку.

Параллельно с этим будет разрабатываться игра. TopDown survival с элементами RougeLike. (Дальше пока не придумал :D)

## Запуск проекта локально
1. Загрузка зависимостей. Все зависимости представлены ниже.
2. Передача права запуска скрипту stratup_project.sh:
~~~bash
chmod -x startup_project.sh
~~~
Скрипту можно передать права один раз, в поледствии передавать не обязательно.
3. Запуск скрипта:
~~~bash
./startup_project.sh
~~~

## Цели

Это будет 2D движок. Платформа PC. Поддержка скриптов.
Зависимости:
- OpenGL - для графики;
- SDL - создание окон;
- glm - математика;
- stb_image - файлы;
- Звук (позже) - Скорее всего SDL_mixer.

### Requirements
~~~bash
sudo apt update
sudo apt install libsdl2-dev libsdl2-mixer-dev libgl1-mesa-dev libglew-dev libglew-dev libsdl2-image-dev libglm-dev
~~~