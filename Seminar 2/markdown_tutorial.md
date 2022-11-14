# Туториал по языку MarkDown

## Работа с заголовками


## Работа со списками


## Работа с изображениями


## Работа с таблицами

Для того, чтобы добавить таблицу в MarkDown, нужно будет пойти на некоторые ухищрения. Воспользуемся разметкой GFM, пример:

First Header | Second Header
------------- | -------------
Content Cell | Content Cell
Content Cell | Content Cell
Для красоты можно и по бокам линии нарисовать:

| First Header | Second Header |
| ------------- | ------------- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |
Можно управлять выравниванием столбцов при помощи
двоеточия.
| Left-Aligned | Center Aligned | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is | some wordy text | $1600 |
| col 2 is | centered | $12 |
| zebra stripes | are neat | $1 |
Внутри таблиц можно использовать ссылки, наклонный,
жирный или зачеркнутый текст.


Для всего остального есть обычный HTML. Воспользуйтесь тегом table:
HTML 
<table><td><tr></tr></td></table>