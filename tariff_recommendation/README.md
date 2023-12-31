# Рекомендация тарифов


## Данные

Имеются данные о поведении клиентов, которые уже пользуются тарифами мобильной связи. Каждая строка в наборе данных - это информация о поведении одного пользователя за месяц:
- Количество звонков
- Длительность звонков
- Количество sms-сообщений
- Израсходованный интернет-трафик
- Каким тарифом пользовался

## Задача

Необходимо построить модель для задачи классификации, которая выберет подходящий тариф для клиентов.

## План работы

1. Выгрузка данных: Загрузка данных из файла и изучение общей информации о датафрейме.
2. Разбивка данных на выборки: Разделение исходных данных на обучающую, валидационную и тестовую выборки.
3. Исследование моделей: Исследование качества разных моделей с разными гиперпараметрами.
4. Проверка модели на тестовой выборке.

## Используемые библиотеки
*pandas, matplotlib, seaborn, sklearn*
