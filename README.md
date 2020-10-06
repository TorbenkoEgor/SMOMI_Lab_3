## Лабораторная работа №3

---

# train1.py

Тренировочные данные - Синий график

Валидационные данные - Коричневый график

Метрика точности

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_3/blob/main/logs/s1.png)

Метрика функции потерь

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_3/blob/main/logs/s2.png)

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_3/blob/main/logs/lab3-1-p.png)

Метрика точности

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_3/blob/main/logs/lab3-1-1.png)

Метрика функции потерь

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_3/blob/main/logs/lab3-1-2.png)

---

# train2.py

Модель использует 3 свёрточных слоя. В свёрточных слоях 8, 8, 8 фильтров соответсвенно.

	tf.keras.layers.Input(shape=(224,224,3)),
	tf.keras.layers.Conv2D(filters=8, kernel_size=3),
	tf.keras.layers.MaxPool2D(),
	tf.keras.layers.Conv2D(filters=8, kernel_size=3),
	tf.keras.layers.MaxPool2D(),
	tf.keras.layers.Conv2D(filters=8, kernel_size=3),
	tf.keras.layers.MaxPool2D(),
	tf.keras.layers.Flatten(),
	tf.keras.layers.Dense(NUM_CLASSES, activation=tf.keras.activations.softmax)

Тренировочные данные - Голубой график

Валидационные данные - Розовый график

Метрики точности

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_2/blob/master/logs/Screenshot_3.png)

Метрика функции потерь

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_2/blob/master/logs/Screenshot_4.png)

---

# train3.py

Модель использует 3 свёрточных слоя. В свёрточных слоях 32, 16, 8 фильтров соответсвенно.

	tf.keras.layers.Input(shape=(224,224,3)),
	tf.keras.layers.Conv2D(filters=32, kernel_size=3),
	tf.keras.layers.MaxPool2D(),
	tf.keras.layers.Conv2D(filters=16, kernel_size=3),
	tf.keras.layers.MaxPool2D(),
	tf.keras.layers.Conv2D(filters=8, kernel_size=3),
	tf.keras.layers.MaxPool2D(),
	tf.keras.layers.Flatten(),
	tf.keras.layers.Dense(NUM_CLASSES, activation=tf.keras.activations.softmax)

Тренировочные данные - Коричневый график

Валидационные данные - Голубой график

Метрика точности

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_2/blob/master/logs/Screenshot_6.png)

Метрика функции потерь

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_2/blob/master/logs/Screenshot_7.png)

---

# train4.py

Модель использует 4 свёрточных слоя. В свёрточных слоях 32, 16, 8, 8 фильтров соответсвенно.

	tf.keras.layers.Input(shape=(224,224,3)),
	tf.keras.layers.Conv2D(filters=32, kernel_size=3),
	tf.keras.layers.MaxPool2D(),
	tf.keras.layers.Conv2D(filters=16, kernel_size=3),
	tf.keras.layers.MaxPool2D(),
	tf.keras.layers.Conv2D(filters=8, kernel_size=3),
	tf.keras.layers.MaxPool2D(),
	tf.keras.layers.Conv2D(filters=8, kernel_size=3),
	tf.keras.layers.MaxPool2D(),
	tf.keras.layers.Flatten(),
	tf.keras.layers.Dense(NUM_CLASSES, activation=tf.keras.activations.softmax)

Тренировочные данные - Розовый график

Валидационные данные - Зелёный график

Метрика точности

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_2/blob/master/logs/Screenshot_8.png)

Метрика функции потерь

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_2/blob/master/logs/Screenshot_9.png)
---

# train5.py

Модель использует 4 свёрточных слоя. В свёрточных слоях 32, 32, 16, 8 фильтров соответсвенно.

	tf.keras.layers.Input(shape=(224,224,3)),
	tf.keras.layers.Conv2D(filters=32, kernel_size=3),
	tf.keras.layers.MaxPool2D(),
	tf.keras.layers.Conv2D(filters=32, kernel_size=3),
	tf.keras.layers.MaxPool2D(),
	tf.keras.layers.Conv2D(filters=16, kernel_size=3),
	tf.keras.layers.MaxPool2D(),
	tf.keras.layers.Conv2D(filters=8, kernel_size=3),
	tf.keras.layers.MaxPool2D(),
	tf.keras.layers.Flatten(),
	tf.keras.layers.Dense(NUM_CLASSES, activation=tf.keras.activations.softmax)

Тренировочные данные - Коричневый график

Валидационные данные - Голубой график

Метрика точности

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_2/blob/master/logs/Screenshot_11.png)

Метрика функции потерь

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_2/blob/master/logs/Screenshot_12.png)

---

# train6.py

Модель использует 5 свёрточных слоев. В свёрточных слоях 32, 32, 16, 8, 8 фильтров соответсвенно.

	tf.keras.layers.Input(shape=(224,224,3)),
	tf.keras.layers.Conv2D(filters=32, kernel_size=3),
	tf.keras.layers.MaxPool2D(),
	tf.keras.layers.Conv2D(filters=16, kernel_size=3),
	tf.keras.layers.MaxPool2D(),
	tf.keras.layers.Conv2D(filters=8, kernel_size=3),
	tf.keras.layers.MaxPool2D(),
	tf.keras.layers.Conv2D(filters=8, kernel_size=3),
	tf.keras.layers.MaxPool2D(),
	tf.keras.layers.Conv2D(filters=8, kernel_size=3),
	tf.keras.layers.MaxPool2D(),
	tf.keras.layers.Flatten(),
	tf.keras.layers.Dense(NUM_CLASSES, activation=tf.keras.activations.softmax)

Тренировочные данные - Розовый график 

Валидационные данные - Зелёный график

Метрика точности

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_2/blob/master/logs/Screenshot_13.png)

Метрика функции потерь

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_2/blob/master/logs/Screenshot_14.png)

---

# train7.py

Модель использует 5 свёрточных слоев. В свёрточных слоях 32, 32, 16, 16, 8 фильтров соответсвенно.

	tf.keras.layers.Input(shape=(224,224,3)),
	tf.keras.layers.Conv2D(filters=32, kernel_size=3),
	tf.keras.layers.MaxPool2D(),
	tf.keras.layers.Conv2D(filters=32, kernel_size=3),
	tf.keras.layers.MaxPool2D(),
	tf.keras.layers.Conv2D(filters=16, kernel_size=3),
	tf.keras.layers.MaxPool2D(),
	tf.keras.layers.Conv2D(filters=16, kernel_size=3),
	tf.keras.layers.MaxPool2D(),
	tf.keras.layers.Conv2D(filters=8, kernel_size=3),
	tf.keras.layers.MaxPool2D(),
	tf.keras.layers.Flatten(),
	tf.keras.layers.Dense(NUM_CLASSES, activation=tf.keras.activations.softmax)

Тренировочные данные - Серебристый график

Валидационные данные - Оранжевый график

Метрика точности

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_2/blob/master/logs/Screenshot_15.png)

Метрика функции потерь

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_2/blob/master/logs/Screenshot_16.png)

---



![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_3/blob/main/logs/s3.png)

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_3/blob/main/logs/s4.png)

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_3/blob/main/logs/s5.png)

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_3/blob/main/logs/s6.png)

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_3/blob/main/logs/s7.png)

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_3/blob/main/logs/s8.png)

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_3/blob/main/logs/s9.png)

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_3/blob/main/logs/s10.png)

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_3/blob/main/logs/s11.png)

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_3/blob/main/logs/s12.png)

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_3/blob/main/logs/s13.png)

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_3/blob/main/logs/s14.png)

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_3/blob/main/logs/s15.png)

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_3/blob/main/logs/s16.png)

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_3/blob/main/logs/s17.png)

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_3/blob/main/logs/s18.png)

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_3/blob/main/logs/s19.png)

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_3/blob/main/logs/s20.png)

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_3/blob/main/logs/s21.png)

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_3/blob/main/logs/s22.png)

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_3/blob/main/logs/s23.png)

![Image alt](https://github.com/TorbenkoEgor/SMOMI_Lab_3/blob/main/logs/s24.png)
