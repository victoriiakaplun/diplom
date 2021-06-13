В данном репозитории лежат jupyter notebook тетради,
в которых проводились исследования в ходе дипломной работы.

Навигация:

папка MNIST: исходный датасет MNSIT

папка data: тренировочная, тестовая и валидационные выборки:
1. valid.pt - исходные данные
2. binarized.pt - бинаризованная валидационная выборка
3. canny_contours.pt - контуры полученные с помощью детектора Кэнни
4. morphology-contours.pt - контуры, полученные методами математической морфологии

папка models: содержит обученные модели:
1. mnist-cnn-model.pth - обученная сверточная сеть
2. mnist-fcnn-model.pth - обученная полносвязная сеть

Можно просматривать ноутбуки в следующем порядке:
mnist-visual-analysys.ipynb - визуальный анализ данных, примеры картинок датасета,
                              графики сбалансированности данных
                              
data-splitting.ipynb -  разделение датасета на тренировочную, тестовую и валидационную выборки

cnn-training.ipynb - обучение и сохранение сверточной сети

fcnn-training.ipynb - обучение и сохранение полносвязной сети

binarize.ipynb - получение бинаризованных изображений

canny-contours.ipynb - получение контуров с помощью детектора Кэнни

getting-morphology-contours.ipynb - получение контуров методами математической морфологии

binarized-inference.ipynb - предсказания и метрики для бинаризованных изображений

canny-inference.ipynb - предсказания и метрики для контуров, полученных с помощью
                  детектора Кэнни
                  
morphology_contours_inference.ipynb - получение предсказаний и метрики для контуров, 
                                полученных с помощью методов мат. морфологии


