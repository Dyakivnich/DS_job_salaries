# Анализ зарплат Data Science

## Задача проекта

Исследовать [данные](https://github.com/Dyakivnich/DS_job_salaries/blob/master/ds_salaries.csv) с зарплатами Data Science за 2020-2022 года.

## Знакомство с данными

### work_year

Год, в котором была выплачена зарплата.

### experience_level

Опыт работы на этой должности в течение года со следующими возможными значениями:
* EN — Entry-level/Junior;
* MI — Mid-level/Intermediate;
* SE — Senior-level/Expert;
* EX — Executive-level/Director.

### employment_type

Тип трудоустройства для этой роли:
* PT — неполный рабочий день;
* FT — полный рабочий день;
* CT — контракт;
* FL — фриланс.

### job_title

Роль, в которой соискатель работал в течение года.

### salary

Общая выплаченная валовая сумма заработной платы.

### salary_currency

Валюта выплачиваемой заработной платы в виде кода валюты ISO 4217.

### salary_in_usd

Зарплата в долларах США (валютный курс, делённый на среднее значение курса доллара США за соответствующий год через fxdata.foorilla.com).

### employee_residence

Основная страна проживания сотрудника в течение рабочего года в виде кода страны ISO 3166.

### remote_ratio

Общий объём работы, выполняемой удалённо. Возможные значения:
* 0 — удалённой работы нет (менее 20 %);
* 50 — частично удалённая работа;
* 100 — полностью удалённая работа (более 80 %).

### company_location

Страна главного офиса работодателя или филиала по контракту в виде кода страны ISO 3166.

### company_size

Среднее количество людей, работавших в компании в течение года:
* S — менее 50 сотрудников (небольшая компания);
* M — от 50 до 250 сотрудников (средняя компания);
* L — более 250 сотрудников (крупная компания).


## Общие выводы

* Период, за который отобран датасет, равен 3 годам (2020-2022)
* Наиболее распространненый уровень квалификации - Senior-level/Expert
* Минимальная зарплата - 2859 долларов, максимальная зарплата - 600000 долларов, средняя запрлата - 112298 долларов
* Заработная плата зависит от занимаемой должности, чем выше должность, тем выше заработная плата
* Зарплаты специалистов Data Scientist в средних компаниях больше, чем в других компаниях, а зарплаты специалистов Data Scientist в крупных компаниях больше, чем в небольших компаниях
* Наибольшее распределение заработной платы в компаниях с головным офисом в US
* Зарплата в 2022 году больше, чем в 2021 и 2020, но нет оснований утверждать, что зарплата в 2021 году больше, чем в 2020
* Наибольшую заработную плату получают те, кто выполняют роли Data Architect, Data Science Manager, Principal Data Scientist, Machine Learning Scientist
* У специалистов Data Scientist наблюдается ежегодный рост заработной платы
* В 2022 году средняя зарплата специалистов Data Science больше, чем общая средняя зарплата 
* Нет оснований утверждать, что есть разница между зарплатами Data Scientist и Data Engineer в 2022 году
* Между наличием должностей Data Engineer и размером компании есть взаимосвязи (признаки зависимы), но нет оснований утверждать, что между наличием должностей Data Scientist и размером компании есть взаимосвязи (признаки независимы)
* Наибольшее количество специалистов Data Scientist и Data Engineer в средних компаниях.
