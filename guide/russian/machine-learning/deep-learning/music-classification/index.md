---
title: Music Classification
localeTitle: Музыкальная классификация
---
## Музыкальная классификация

Классификация музыки - еще одна область, где стратегии глубокого обучения могут быть применены для достижения более высокой точности классификации, чем традиционные методы машинного обучения. Глубокие нейронные сети, которые изначально использовались для распознавания изображений и задач компьютерного зрения, можно было использовать для классификации музыки с помощью спектрограмм. Спектрограмма - не что иное, как визуальное представление спектра частот, присутствующих в музыке в течение определенного периода времени. Другими словами, музыкальный сигнал, который является результирующей частотой, можно разделить на его спектр частот, а громкость в виде дБ может быть визуально представлена ​​для каждой частоты. Это изображение можно использовать для обучения нейронной сети, которая классифицирует такие спектрограммы. Отличным вариантом использования является распознавание жанра.

### Ниже приведены примеры различных спектрограмм:

![Spectrogram1](http://deepsound.io/images/new_blues_00.png)

Вышеупомянутая спектрограмма представляет собой песню из жанра блюза. Частоты идут по оси y и по оси x. Более яркие цвета означают, что звук этой частоты громкий, тогда как более темные цвета представляют собой мягкие в эти конкретные моменты времени. Такое изображение, содержащее столько данных, может быть использовано для обучения нейронной сети. Обычно мы используем мелкомасштабную спектрограмму с целью распознавания жанра, которая представляет собой масштаб шагов, оцененных слушателями, т. Е. Как мы воспринимаем такие частоты для различения компонентов разных жанров.

**Преобразования Фурье**

Важно знать, что такие спектрограммы создаются с помощью математического понятия, известного как преобразования Фурье. Преобразование Фурье разлагает функцию времени на частоты, которые ее составляют.

#### Больше информации

Если вы используете python, для обработки сигналов существует много библиотек. [Librosa](https://librosa.github.io/librosa/) - известная, другая - [скудная,](https://scipy.org/) которая также может использоваться для других научных целей. Мел-спектрограммы могут быть созданы с использованием этих библиотек.

##### Пожалуйста, ознакомьтесь со следующими ссылками для получения дополнительной информации по вышеуказанной теме:

*   [Поиск жанра](https://hackernoon.com/finding-the-genre-of-a-song-with-deep-learning-da8f59a61194)
*   [Deepsound](http://deepsound.io/music_genre_recognition.html)