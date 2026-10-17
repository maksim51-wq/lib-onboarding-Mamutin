# Итоговый аналитический отчет
## 1. Резюме
Этап 1.Изучил контекст, определил 4-5 критериев, создал таблицу сравнения, назначил веса , оценил PostgreSQL и MongoDB по 5-балльной шкале, рассчитал взвешенную оценку, сделал вывод о победителе.
Этап 2.Создал репозиторий lab1-comprehensive-ВашаФамилия, ветки main, develop, feature/infrastructure. Создал .editorconfig и .github/CODEOWNERS, сделал коммит chore: setup editorconfig and codeowners. Настроил защиту develop . Создал, одобрил и слил PR в develop.
Этап 3.Создал ветку feature/qa-gates, файлы .flake8 и .github/workflows/qa.yml, коммит ci: add flake8 and github actions workflow. Создал src/discount.py с ошибками , коммит test: add code with intentional errors. Создал PR, дождался красного статуса. Исправил ошибки, коммит fix: resolve linter errors, статус стал зеленым, слил PR.
Этап 4.Изучил legacy-код, построил вdraw.ioДиаграмму деятельности (, экспортировал в uml_diagram.png. Создал ветку feature/review-plan, файл docs/review-plan.md , коммит docs: add review plan for discount module. Загрузил uml_diagram.png в docs/, коммит docs: add UML diagram for discount algorithm. Создал PR и оставил открыты
Этап 5.Создал REPORT.md в ветке develop, заполнил по шаблону со ссылками на коммиты, PR и скриншоты
## 2. Сравнительный анализ технологий
### 2.1. Матрица принятия решений
<img width="578" height="144" alt="image" src="https://github.com/user-attachments/assets/f7ae756c-f73d-4689-ac76-92e3298be7ac" />
### 2.2. Расчет и обоснование выбора
- [Формула взвешенной оценик:] =B2*C2+B3*C3+B4*C4+B5*C5
- [Победителем выбрал PostgreSQL потому что:] он быстрее работает и можно гибко настраивать схемы
## 3. Архитектура и контроль версий
### 3.1. Настройка репозитория
### 3.2. Контроль доступа
<img width="931" height="100" alt="image" src="https://github.com/user-attachments/assets/b2887167-4217-4459-b716-49fc2dec1364" />
<img width="504" height="111" alt="image" src="https://github.com/user-attachments/assets/46c0428c-de5b-4975-a2c0-501c23067f2a" />
## 4. Инструментальный контроль качества
### 4.1. Настройка CI/CD
https://github.com/maksim51-wq/lab1-comprehensive--/blob/feature/qa-gates/.github/workflows/qa.yml
### 4.2. Работа Quality Gate
<img width="505" height="275" alt="image" src="https://github.com/user-attachments/assets/0d8080b1-fb43-4e20-b23b-c59f27f443df" />
<img width="451" height="57" alt="image" src="https://github.com/user-attachments/assets/ec05c26d-8ec9-42f6-b2f9-3e65a03e566b" />
## 5. Обратное проектирование и планирование ревью
### 5.1. Анализ алгоритма
[UML Diagram](docs/uml_diagram.png)
### 5.2. План code-review
## 6. Заключение
