# Исследование для сети фитнес-центров

## Задача

Провести анализ и подготовить план действий по удержанию клиентов сети фитнес-клубов на основе собранных данных.

Мы спрогнозируем вероятность оттока (на уровне следующего месяца) для каждого клиента;
сформируем типичные портреты клиентов;
проанализируем основные признаки, наиболее сильно влияющие на отток;
сформулируем основные выводы и рекомендации по повышению качества работы с клиентами

## Описание данных

**Набор данных включает следующие поля:**
- 'Churn' — факт оттока в текущем месяце;

**Текущие поля в датасете:** 

- Данные клиента за предыдущий до проверки факта оттока месяц:
 - 'gender' — пол;
 - 'Near_Location' — проживание или работа в районе, где находится фитнес-центр;
 - 'Partner' — сотрудник компании-партнёра клуба (сотрудничество с компаниями, чьи сотрудники могут получать скидки на абонемент — в таком случае фитнес-центр хранит информацию о работодателе клиента);
 - Promo_friends — факт первоначальной записи в рамках акции «приведи друга» (использовал промо-код от знакомого при оплате первого абонемента);
 - 'Phone' — наличие контактного телефона;
 - 'Age' — возраст;
 - 'Lifetime' — время с момента первого обращения в фитнес-центр (в месяцах).


**Информация на основе журнала посещений, покупок и информация о текущем статусе абонемента клиента:**
- 'Contract_period' — длительность текущего действующего абонемента (месяц, 3 месяца, 6 месяцев, год);
- 'Month_to_end_contract' — срок до окончания текущего действующего абонемента (в месяцах);
- 'Group_visits' — факт посещения групповых занятий;
- 'Avg_class_frequency_total' — средняя частота посещений в неделю за все время с начала действия абонемента;
- 'Avg_class_frequency_current_month' — средняя частота посещений в неделю за предыдущий месяц;
- 'Avg_additional_charges_total' — суммарная выручка от других услуг фитнес-центра: кафе, спорт-товары, косметический и массажный салон.


