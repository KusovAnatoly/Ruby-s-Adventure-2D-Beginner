# Ruby's Adventure: 2D Beginner
Лабораторная работа по дисциплине Моделирование физических процессов в приложениях

## Описание

Город оказался в опасности после того, как его дружелюбные роботы сломались! Задача Руби — исправить их! Научитесь создавать эту небольшую 2D-ролевую игру с нуля и спасите город!

## Порядок сдачи работ:
- Примите задание в GitHub Classroom
- Для вас автоматически создастся репозиторий
- Создавайте ветку devN (где N - это номер лабораторной по порядку) и выгружайте в нее каждый этап исходного кода
- В конце разработе выгрузите ветку dev14 в ветку main
- Отметьте работу выполненной в GitHub Classroom

Список лабораторных работ:
- [ ] Get Started with Ruby's Adventures 
- [ ] Character Control and Keyboard Input 
- [ ] World Design – Tilemaps 
- [ ] Decorating the World 
- [ ] World Interactions – Blocking movement 
- [ ] World Interactions – Damage Zones and Enemies 
- [ ] Sprite Animation 
- [ ] World Interactions – Projectile 
- [ ] Camera – Cinemachine 
- [ ] Visual Styling – Particles 
- [ ] Visual Styling – User Interfaces – Head-Up Display 
- [ ] World Interactions – Dialog Raycast 
- [ ] Audio 
- [ ] Build, Run, Distribute 

## git

*примечание*

в тексте команды отображены следующим образом:

`git`

```shell
git init
git checkout -b BranchName
```

если текст написан следующим образом:
YOUR-GITHUB-NAME, то нужно поставить вместо YOUR-GITHUB-NAME ваше имя пользователя на GitHub
YOUR-GITHUB-EMAIL, то нужно поставить вашу электронную почту из профиля на GitHub и т. д. и т. п.

---

*предварительные требования*:
- вам нужно [установить](https://git-scm.com/book/ru/v2/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%A3%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0-Git) **git** на ваш ПК
- вам нужно [установить](https://apps.microsoft.com/detail/9N0DX20HK701?hl=ru-ru) **Windows Terminal** на ваш ПК

1. создайте папку на вашем ПК в удобном месте (например, C:\Users\YOUR-USER\MY-FOLDER)
2. создайте новый файл или добавьте любой другой файл с разными расширениями файла (например, файлы могут иметь такие имена: text.txt, program.py, program.cs)
3. создайте **удаленный** **GitHub* репозиторий на сайте [github.com](https://github.com/) назовите его MyGithubRepository
4. создайте **локальный** ***git*** репозиторий в папке которую вы ранее создали (шаг 1). для этого кликните ПКМ (правую кнопку мыши) выберите ), выберите Открыть с помощью -> Windows Terminal, открыв терминал введиту  команду `git init` и нажмите Enter
5. добавьте конфигурацию вашей учетной записи в **локальном** репозиторий, используя следующие команды:

```pwsh
git config user.name "YOUR-GITHUB-NAME"
git config user.email "YOUR-GIHUB-EMAIL@EXAMPLE.COM"
```
6. добавьте файлы для отслеживания в *staging area* с помощью команды `git add .`
7. добавьте ссылку на удаленный репозиторий на GitHub с помощью команды `git remote add origin https://github.com/YOUR-GITHUB-NAME/MyGithubRepository.git`
8. создайте и смените ветку одной командой `git checkout -b dev`
9. создайте коммит с помощью команды `git commit -m "ANY-MESSAGE-YOU-WANT-TO-LIVE"`
10. отправьте изменения в удаленный репозиторий с помощью команды `git push -u origin dev`

*note<sup>1</sup>*: dev - имя ветки  
*note<sup>2</sup>*: verb - глагол, noun - существительное

### как внести изменения в репозиторий

Для того, чтобы добавить новые файлы или зафиксировать изменения в существующих, вам следует:
1. добавьте файлы для отслеживания в *staging area* с помощью команды `git add .`
2. выполнить комманду `git commit -m "ANY-MESSAGE-YOU-WANT-TO-LIVE"`
3. отправьте изменения в удаленный репозиторий с помощью команды `git push -u origin dev`

Для того, чтобы изменить ветку на новую, вам следует:
1. вы можете сменить ветку с помощью команды `git switch BRANCH-NAME'
2. либо вы можете создать и сменить ветку одной командой `git checkout -b BRANCH-NAME`

