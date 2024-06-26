## Дана платформа онлайн образования, с которой выгружены следующие данные:
  * информация об оценках в тестах по предметам
  * список предметов по семестрам
  * результаты тестов студентов
  * информация о времени, когда студент зарегистрировался для прохождения курса

## Необходимо проанализировать данные и ответить на следующие вопросы:
1. Сколько студентов успешно сдали только один курс? (Успешная сдача — это зачёт по курсу на экзамене)
2. Выявить самый сложный и самый простой экзамен: найди курсы и экзамены в рамках курса, которые обладают самой низкой и самой высокой завершаемостью 
  (*завершаемость= кол-во успешных экзаменов / кол-во всех попыток сдать экзамен)
3. По каждому предмету определить средний срок сдачи экзаменов (под сдачей понимаем последнее успешное прохождение экзамена студентом). 
4. Выявить самые популярные курсы (ТОП-3) по количеству регистраций на них. А также курсы с самым большим оттоком (ТОП-3).
5. Написать функцию, позволяющую строить когортный (семестровый) анализ. В период с начала 2013 по конец 2014 выявить семестр с самой низкой завершаемостью курсов
  и самыми долгими средними сроками сдачи курсов.
6. Построить адаптированные RFM-кластеры студентов, для качественной оценки аудитории.

Анализ проведен на Python, выводы в файле E-learning_project_aa_ryzhakina.ipynb.
