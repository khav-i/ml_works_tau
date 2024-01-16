# Прогнозирование ВВП Ганы по временному ряду

В данной работе мы решаем задачу прогнозирования некоторого числового признака в зависимости от его предыдущих изменений.
Для достижения этой цели мы используем модели ARIMA, ARCH и сравниваем получившийся результат с предсказанием линейной регрессии.

## Данные
В ходе проекта мы работали с [данными](https://lms-cdn.skillfactory.ru/assets/courseware/v1/cf3fb9ca311981f5cc6b6f0a40621388/asset-v1:SkillFactory+DSPR-2.0+14JULY2021+type@asset+block/ghana_gdp.zip) по ВВП Ганы.

## Содержание
- Дифференцирование ряда
- ARIMA
- Интерполяция и сэмплирование
- Модели прогнозирования гетероскедастичности. Валидация временных рядов
- ARCH
- Предсказание

## Результат

Предсказание динамики ВВП Ганы ARIMA-моделью:

![image](https://github.com/khav-i/ml_works_tau/assets/126453765/af23fd57-f7cc-4c75-9b96-2c6368a0f9df)

Предсказание волатильности ВВП Ганы ARCH-моделью:

![image](https://github.com/khav-i/ml_works_tau/assets/126453765/0c5f02a0-3759-4b05-882f-ba03aa722f04)

ARCH-models MSE: 2605.3542

Предсказание волатильности ВВП Ганы линейной регрессией:

![image](https://github.com/khav-i/ml_works_tau/assets/126453765/10e66d01-e05a-467d-90e5-bf95eacc6a56)

LR-models MSE: 251.4089

## [Прыжок в тетрадку](https://github.com/khav-i/ml_works_tau/blob/master/Ghana%20GDP/ghana_gdp.ipynb)
