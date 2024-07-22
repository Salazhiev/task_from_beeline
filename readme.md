### Добро пожаловать на кейс Beeline "Автономера"!
*** 
В представленном архиве вы можете увидеть следующие папки и файлы

1. Папка **images** --- датасет из фотографий номеров автомобилей
2. Файл **pipeline.ipynb** --- файл, содержащий функции для работы на хакатоне, а также важные инструкции. **!!!ВАЖНО!!!** Необходимо обязательно ознакомиться с этим файлом.
3. Файл **correspondance.csv** --- соответствие изображений и номеров на них. Для генерации решения необходимо воспользоваться скриптом predict.py, указав путь до папки с нормализованными изображениями.
4. Файл **sample_submission.csv** --- пример засылаемого на платформу ответа.
5. **resnet18_letters.pth** --- веса модели распознавания.

***

##### Вашей задачей будет разработка модели, осуществляющей нормализацию изображений номеров автомобилей.

На основе имеющихся ненормализованных изображений и соответствий необходимо построить модель, которая будет осуществлять нормализацию изображений под трафареты, указанные в папке **prediction**. В качестве ответа необходимо будет отправить генерируемый csv файл, с распознанным текстом от обоих шаблонов. При проверке будет выбран лучший вариант. Не забудьте про технические и отраслевые критерии.

Проверка будет осуществляться с помощью метрики средняя доля правильно распознанных симвлов. Чем ближе значение к единице - тем лучше.
**ВАЖНО!!!** Решение сдается на автоматическую проверку в формате .csv.
**ВАЖНО!!!** Обязательно проверьте разделители, заголовки и столбцы, они должны быть аналогичны формату sample_submission.csv

# ЖЕЛАЕМ УДАЧИ!

P.S. Не забудьте посетить экспертные сессии и не стесняйтесь задавать вопросы)