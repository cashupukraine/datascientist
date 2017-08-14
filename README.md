# datascientist

Тестовое задание на позицию **Data Scientist**
Присылайте на почту *hr@cashup.com.ua* резултаты выполненых заданий:
- для задания **А**: заполненный файл *output_draft.csv*
- для задания **B**: ID Джона Доу в системе и его предполагаемое место жительства (описание расследования приветствуются).

### Files

*train_ds.csv* - данные для обучения.
*test_ds.csv* - тестовые данные.
*output_draft.csv* - требуемый формат прогноза.

### Features

- *cgsettlementbufferid* - ID транзакции в системе.
- *mcc* - код категории торговой точки транзакции [Wiki](https://ru.wikipedia.org/wiki/Merchant_Category_Code).
- *tranccy* - код валюты транзакции.
- *ccy* - код валюты карты.
- *amount* - сумма транзакции в копейках.
- *location* - торговая точка транзакции.
- *trandatetime* - дата и время транзакции по ЕЕТ.
- *clientid* - ID клиента в системе.
- *sexid* - пол клиента.

### Task A

Для клиентов из *test_ds* найти значение пола (формат итогового файла *output_draft.csv*), метрика MAE.

### Task B

Предлагаем вам поиграть в детектива. Все имеющиеся у нас данные вы найдёте в *train_ds.csv*.

> Мы знаем, что Джон Доу прилетел в Украину в начале июля 2015-го.
> Также известно, что 6го июля Джон ужинал в явочном кафе в Киеве и передал секретные документы другому шпиону, но в толпе наш агент его потерял.

Отыщите место проживания Джона Доу.

