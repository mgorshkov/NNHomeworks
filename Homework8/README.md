# Катастрофическое забывание (необязательное)
Цель: Проверить влияние fine-tuning на исходную модель
1. Дообучить готовую модель на imagenette2 и проверить качество
2. Сохранить последний слой обученной модели и заменить его на новый для CIFAR10
2. Дообучить модель решать датасет CIFAR10 и проверить качество
3. Вернуть оригинальный последний слой модели и проверить качество на imagenette2
4. Дообучить только последний слой на imagenette2 и проверить удалось ли добиться исходного качества.