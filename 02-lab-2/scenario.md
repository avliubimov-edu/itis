# Сценарий

Поговорив с Бобом. Сьюзан поняла, что должна делать система обработки заказов, создаваемая ею для фирмы Roberton's Cabinets. Она нарисовала диаграмму Вариантов Использования. Изучив эту диаграмму, все пришли к согласию по поводу области применения системы.

Теперь наступило время анализа ее составных частей. Высший приоритет среди пользователей имеет вариант использования "Enter a new order", он же связан с наибольшим риском. Сьюзан решила заняться им в первую очередь. Она поговорила с Карлом, заведующим отделом продаж. Вдвоем они обсудили поток событий, который будет реализовываться в варианте использования. Получив нужную информацию, Сьюзан составила описание сценариев:

* Продавец вводит новый заказ.
* Продавец пытается ввести заказ, но товара нет на складе.
* Продавец пытается ввести заказ, но при его сохранении в базе данных возникает ошибка.

&#x20;Затем она приступила к созданию диаграмм Последовательности (Sequence Diagram) и Кооперативных диаграмм (Collaboration Diagram) для сценария "Enter a new order".
