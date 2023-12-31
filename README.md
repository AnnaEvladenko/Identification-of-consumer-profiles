# Проект: Выявление профилей потребления покупателей интернет-магазина товаров для дома и быта «Пока все ещё тут»

**Цель проекта**: Сформировать рекомендации для владельца интернет-магазина товаров для дома и быта для разработки персональных предложений для покупателей с целью увеличения покупательской активности и лояльности покупателей, роста продаж (увеличения выручки), удержания покупателей.   

**Выполненные задачи**:    
1) Выполнила предобработку данных (изменила тип данных, выявила и удалила дубликаты, выполнила категоризацию товаров, добавила новые столбцы с необходимыми данными)
2) Сегментировала покупателей магазина **по профилю потребления**, определила:   
- покупатели каких сегментов приносят большую часть выручки;    
- какие покупатели могут приносить в перспективе больше выручки при таргетированных рекламных предложениях;   
- какие покупатели бесперспективны.   
3) Выявила характеристики пользователей каждого сегмента;      
4) Подготовила рекомендации для разработки персональных предложений для покупателей каждого сегмента;
5) Подготовила для заказчика [презентацию](https://disk.yandex.ru/i/KQCfq1JtlrE88A);
6) Создала [дашборд](https://public.tableau.com/views/finalpr_16863795145730/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link), отображающий сумму покупок по дням и количество заказов по сумме с возможностью фильтрации по дате совершения заказа.

**Вывод:** Выполнена кластерезация пользователей на 6 сегментов: описаны характеристики сегментов, модели покупательского поведения, 
для каждого сегмента подготовлены рекомендации для разработки персональных предложений.  

Для исследования **использован датасет** со следующими столбцами:

- `date` — дата заказа;
- `customer_id` — идентификатор покупателя;
- `order_id` — идентификатор заказа;
- `product` — наименование товара;
- `quantity` — количество товара в заказе;
- `price` — цена товара.

**Используемые навыки и инструменты**:
- предобработка данных (Python, Pandas);
- исследовательский анализ данных ( Matplotlib, Plotly);
- проверка статистических гипотез (NumPy, SciPy);
- классификация, кластеризация (Python, Pandas);
- визуализация данных (Matplotlib, Plotly, Tableau).
