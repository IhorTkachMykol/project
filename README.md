Development of DCGAN for CAPTCHA Bypass Detection - 2024

Primary task is to develop a system to identify and block custom machine vision models that attempt to bypass the CAPTCHA system. Our tool in this fight will be a Deep Convolutional Generative Adversarial Network (DCGAN) and a dataset that will be used to generate images that simulate potential bypass attempts and their subsequent identification.

1. Introduction
This project involves creating a DCGAN system capable of generating and identifying images. The system has two main components: a generative network for creating synthetic images and a discriminative network for determining whether an image is real or fake.

2. System Architecture

Generative Network
Objective: Generate fake images based on the dataset.
Architecture: Convolutional layers with batch normalization and ReLU activation.

Discriminative Network
Objective: Differentiate between real CAPTCHA images and synthetic bypass attempts.
Architecture: Convolutional layers with LeakyReLU activation and batch normalization.

3. Training Process
Dataset: Using CAPTCHA images to train the discriminative network, including both real and fake images.
Training Loop: Dynamic adjustment of learning rate to optimize the training process.

4. Interactive Image Input Mechanism
Objective: Allow users to upload arbitrary images to the model, which will then generate a fake version of the image, and both the generative and discriminative models will provide their results.
Implementation: Developing a web interface or API through which images can be uploaded. The system will automatically process the image and return the generated fake image along with the verdict from the discriminative network.

#

Розробка DCGAN для Виявлення Спроб Обходу Капчі - 2024
Задачею є розробка системи для ідентифікації та блокування кастомних моделей машинного зору, які намагаються обійти систему CAPTCHA. Нашим інструментом у цій боротьбі стане глибока згорткова генеративно-суперницька мережа (DCGAN) та датасет, яка буде використовуватися для генерації зображень, що імітують потенційні спроби обходу, та їх подальшої ідентифікації.
1. Вступ
Цей проєкт передбачає створення DCGAN системи, здатної генерувати та ідентифікувати зображення. Система має дві основні компоненти: генеративну мережу для створення синтетичних зображень і дискримінативну мережу для визначення, чи є зображення справжнім, чи підробленим.
2. Архітектура Системи
Генеративна Мережа
Мета: Генерація підроблених зображень на основі датасету 
Архітектура: Згорткові шари з нормалізацією пакетів та активацією ReLU.
Дискримінативна Мережа
Мета: Відсіювання справжніх зображень капчі від синтетичних спроб обходу.
Архітектура: Згорткові шари з активацією LeakyReLU і нормалізацією пакетів.
3. Процес Навчання
Набір даних: Використання зображень капчі для тренування дискримінативної мережі, включаючи як справжні, так і підроблені зображення.
Цикл Навчання: Динамічне регулювання швидкості навчання для оптимізації процесу.
4. Інтерактивний Механізм Введення Зображення
Мета: Дозволити користувачам передавати довільне зображення на модель, після чого модель підробляє це зображення, і обидві моделі (генеративна та дискримінативна) надають свої результати.
Реалізація: Розробка вебінтерфейсу або API, через який можна завантажувати зображення. Система автоматично обробляє зображення і повертає підроблене зображення разом із вердиктом дискримінативної мережі.
