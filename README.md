# Rosbank
Rosbank ML competition.

Здесь приводятся основные элементы обработки данных, дающие 1-е место по первой задаче и 2-е место по второй.

train.csv и test.csv - начальные данные необходимо скачать САМОСТОЯТЕЛЬНО. В данных ноутбуках они везде обозначаются как init_train и init_test, в то время как train и test - уже обработанные данные.


utils.ipynb - обработка изначальных данных.

rosbank.py - содержит одну единственную функцию cashflow, преобразующую данные о пользователе в словарь

time.ipynb - обработка времени

money.ipynb - обработка денежной информации

mcc.time - обработка времени с учетом МСС-кодов. Пока без комментариев

mcc.money - обработка денег с учетом МСС-кодов. Аналогично без комментариев

файлы "handcrafted_mcc_features.npy" и "mcc_codes.npy" содержат инфу об мсс кодах. Первый словарь получен частично с помощью тематического моделирования, частично вручную. Второй массив - данные с сайта mcc-codes.ru. Это словари. Открывать с помощью np.load(путь к файлу).item()
