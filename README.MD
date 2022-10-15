# Modern deep learning course.  
# Современные нейросетевые технологии.   

Based on dlcourse.ai and Stanford CS230n, CS231n.

Assignment results see @ RESULTS.csv

Экзамен будет проходить в письменном виде, у вас будет 90 минут на оформление РУКОПИСНОГО ответа и решения задания в Google Colab. В конце экзамена листы с ответами сдаются, ноутбуки высылаются на почту ailabintsev@fa.ru. Работы будут проверены в течение трех суток. При необходимости индивидуальной беседы будет назначен созвон с видеозаписью.  
Билет будет включать в себя три вопроса: по основам DL, по фреймворку Keras и практическое задание в Google Colab.

Примерные вопросы по основам нейросетевых технологий:  

- Краткая история нейросетей.  
- Задачи, решаемые с помощью нейросетей.  
- Жизненный цикл DL проекта и основные роли исполнителей.  
- Линейный классификатор изображений.
- Преобразование Softmax.
- Функция потерь Cross Entropy loss.
- Линейное отображение. Векторно-матричное дифференцирование.
- Градиент функции многих переменных. Физический смысл. Методы вычисления.
- Стохастический градиентный спуск (SGD).
- Регуляризация параметров W.
- Механизм обратного распространения ошибки (backpropagation).
- Нелинейные функции (слои)
- Продвинутые методы оптимизации.
- Метрики качества классификации.
- Кросс-валидация. Выборки train, validation, test.
- Операции свертки 1D, 2D, 3D.
- Сверточные слои. 
- Pooling слой.
- Препроцессинг данных и инициализация весов
- Поиск гиперпараметров
- Продвинутая регуляризация
- Transfer learning
- Архитектуры классификации изображений
- Семантическая сегментация 
- Детекция объектов
- Архитектура RNN
- Описание изображений с помощью RNN
- Архитектура LSTM.  
  
Примерные практические задания:  
Создайте модель заданной архитектуры и обучите на встроенном датасете tf.keras.datasets.cifar10.load_data().  
Гиперпараметры подберите самостоятельно:  
- Dense - Dense - Dense, Model subclassing.
- Conv - Dense - Dense, Model subclassing.
- Conv - Conv - Dense, Model subclassing.
- Dense - Dense - Dense, Sequential subclassing.
- Conv - Dense - Dense, Sequential subclassing.
- Conv - Conv - Dense, Sequential subclassing.
- Dense - Dense - Dense, Functional API.
- Conv - Dense - Dense, Functional API.
- Conv - Conv - Dense, Functional API.

CS 231n web demos:  
- http://vision.stanford.edu/teaching/cs231n-demos/linear-classify/  
- https://cs.stanford.edu/people/karpathy/convnetjs/demo/classify2d.html  

