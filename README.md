# Анализ платформы онлайн образования
## Cтек:
Python, Pandas, Seaborn, Numpy

## В данном проекте были поставлены следующие задачи:
- проанализировать успеваемость студентов;
- составить рейтинг курсов по числу сдавших студентов, регистраций;
- проанализировать сроки сдачи экзаменов.

## Методы и подходы:
+ когортный анализ
+ RFM сегментация

## Для выполнения поставленных задач были предприняты следующие шаги:
+ С помощью библиотек requests и urllib сформированы ссылки для скачивания данных с Яндекс.диска
+ Определено количество студентов, успешно сдавших только один курс
+ Определен топ-3 среди курсов по завершаемости
+ Определено среднее время сдачи экзаменов
+ Составлены ТОП-3 рейтинги по популярности курсов, количетсву регистрации на них, а также по оттоку студентов (churn rate)
+ Составлена ad-hoc функция для построения когортного анализа и с ее помощью определены семестры с самой низкой завершаемостью курсов и самыми долгими сроками сдачи курсов
+ Построены RFM-кластеры студентов для оценки аудитории
