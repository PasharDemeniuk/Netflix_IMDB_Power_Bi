# Netflix_IMDB_Power_BI
Учебный проект https://stepik.org/course/101689/syllabus  
Данные стриминговой платформы Netflix и данные сайта IMDB, на котором пользователи могут комментировать и выставлять оценки контенту.
Данные Netflix: 
id – идентификатор фильма;
title – название фильма;
director – режиссер;
cast – актеры;
country – страна, где снят фильтм;
release_year – дата добавления;
rating – телевизионный рейтинг;
description – описание;
Runtime - продолжительность в минутах
Данные IMDB: 
id– идентификатор фильма;
type – тип конента;
genres - жанр;
average_rating – средневзвешенная оценка;
num_votes – количество оценивших 

Была проведена следующая работа: 
1. Загрузили данные из источника «интернет»
2. При помощи редактора Power Query обработали пропуски в данных, на значение «UNKW»
3. Построили связь между двумя датасетами по id.
4. Создали вычисляемые столбцы в Netflix при помощи формул на языке dax.
Созданы следующие столбцы: 
- год (извлекли из даты), 
- количество лет между созданием и выпуском на платформе Netflix
5. Создали меру: 
- уникальное количество режиссеров Netflix,
- средняя продолжительность контента, а именно фильма (контекст-фильтр)
- среднее количество проголосовавших,
- среднее количество лет между созданием и выпуском на платформе Netflix
6. Проведена визуализация. 


