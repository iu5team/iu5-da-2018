### Задание

Необходимо решить задачу предсказания класса нарушения в зависимости от текста сообщения о нарушении.
Предсказываемый класс находится в столбце group_title

##### 1. Провести предподготовку данных
Необходимо разбить тексты на токены, преобразовать токены, векторизовать полученные тексты.
Можно попробовать удалять стоп-слова и делать любые преобразования текстов, которые придут в голову. 
В лекции подробно разбирали все эти этапы.
Разделить данные на train/test в пропорции 70-90/30-10%

##### 2. Создать модель классификатора для задачи
Можно использовать любой классификатор (на лекции рассматривали нейронную сеть).
Точность должна быть выше 80%.

##### 3. Провести эксперименты с различными вариантами векторизации и преобразований 
Попробовать векторизовывать тексты по-разному. Например, использовать bag of words, tf-idf, etc.
Прогонять модель и смотреть на результат. Построить confusion_matrix (диаграмма правильности предсказанных классов).
Код всех вариантов, с которыми экспериментировали, нужно сохранить для защиты. 