### Front-End cource. Lessons List. part 2

12. **Построение форм**
* _[Form](https://n-lash.github.io/beetroot-projects/projects/8_Form/app/#sign)_
13. **SVG**
14. **Работа с пре- и постпроцессорами**
15. **Инструмент для сборки проекта (таск-менеджер) Gulp**
* _[Our team](https://n-lash.github.io/beetroot-projects/projects/9_Our-team/app/)_
16. **Адаптивная верстка (Responsive web design)**
* _[Cahee](https://n-lash.github.io/beetroot-projects/projects/10_Cahee/app/)_
17. **Адаптивная навигация**
18. **Адаптивная графика**
19. **Практика - верстка макета**
20. **Кроссбраузерность**
21. **SEO для разработчика**
22. **Экзамен 1. Простой вэб-сайт(desktop-версия)**
* _[Travel more](https://n-lash.github.io/beetroot-projects/projects/11_Exam_Travel-more/app/)_
**Overtime**
* _[Hexal](https://n-lash.github.io/beetroot-projects/projects/hexal/app/)_
* _[Leslie](https://n-lash.github.io/beetroot-projects/projects/Leslie/app/)_










----------------------------
# Gulp-assembler
* Install `gulp-cli`:
```
npm install gulp-cli -g
```
if MacOS
```
sudo npm install gulp-cli -g
```

**To create new project:**
* Move to assembler's directory:
```
cd assembler's_root_directory
```
* Install dependencies:
```
npm i
```
* Add your projects directory as gitmodule:
```
git submodule add -f https://github.com/{username}/{username}.github.io.git projects
```
* Start this command:
```
git rm --cached -f projects
```
* To start development run:
```
gulp ---project's_directory_name
```
or run
```
npm run help
```
