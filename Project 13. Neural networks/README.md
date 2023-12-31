# **Обработка фотографий покупателя**
## Задачи проекта  
1. Определение возраста покупателя для рекомендации ему товаров
2. Определение возраста покупателя с целью установки его совершеннолетия 
## Описание проекта
Сетевой супермаркет внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы и контролировать добросовестность кассиров при продаже алкоголя. Строится модель, которая по фотографии определит приблизительный возраст человека. В распоряжении имеется набор фотографий людей с указанием возраста.
## Вывод
Я получил модель показавшую неплохой результат (`MAE` < 8). Данная ошибка вполне допустима при алгоритмах рекомендации (первая задача), но, я думаю, не самая лучшая при верификации возраста (задача 2). В целом, модель неплохая, особенно для рекомендации товаров, но в вопросе оценки совершеннолетия, думаю, необходима либо доработка программы на детях-подростках-молодых людях, либо коллаборация с человеком.
# Ключевые слова проекта
обработка изображений, CNN
# Используемые библиотеки и навыки
Python, Keras
