## Данные

В наличии были следующие входные данные.

Данные клиента за предыдущий до проверки факта оттока месяц:
- 'gender' — пол;
- 'Near_Location' — проживание или работа в районе, где находится фитнес-центр;
- 'Partner' — сотрудник компании-партнёра клуба (сотрудничество с компаниями, чьи сотрудники могут получать скидки на абонемент — в таком случае фитнес-центр хранит информацию о работодателе клиента);
- Promo_friends — факт первоначальной записи в рамках акции «приведи друга» (использовал промо-код от знакомого при оплате первого абонемента);
- 'Phone' — наличие контактного телефона;
- 'Age' — возраст;
- 'Lifetime' — время с момента первого обращения в фитнес-центр (в месяцах).

Информация на основе журнала посещений, покупок и информация о текущем статусе абонемента клиента:
- 'Contract_period' — длительность текущего действующего абонемента (месяц, 6 месяцев, год);
- 'Month_to_end_contract' — срок до окончания текущего действующего абонемента (в месяцах);
- 'Group_visits' — факт посещения групповых занятий;
- 'Avg_class_frequency_total' — средняя частота посещений в неделю за все время с начала действия абонемента;
- 'Avg_class_frequency_current_month' — средняя частота посещений в неделю за предыдущий месяц;
- 'Avg_additional_charges_total' — суммарная выручка от других услуг фитнес-центра: кафе, спорттовары, косметический и массажный салон.
- 'Churn' — факт оттока в текущем месяце.


## Задача

Изучить распределение признаков, сформировать портреты ушедшего и оставшегося пользователей. Построить матрицу корреляции. Выявить наиболее коррелирующие с целевым признаки. Проанализировать основные признаки, наиболее сильно влияющие на отток.
Выполнить кластеризацию клиентов и охарактеризовать их.
Выбрать модель для прогнозирования оттока клиентов. 
Сформулировать основные выводы и разработать рекомендации по повышению качества работы с клиентами: 
- выделить целевые группы клиентов;
- предложить меры по снижению оттока;
- определить другие особенности взаимодействия с клиентами.


## Используемые библиотеки
*pandas*
*matplotlib*
*warnings*
*plotly*
*seaborn*
*sklearn*
*scipy*
*itertools*