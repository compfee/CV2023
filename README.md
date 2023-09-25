# Задача выделения бинарной маски переднего плана
В ходе работы было проведено выделение бинарной маски изображения с помощью различных математических операций, без использования методов машинного обучения
# Ход работы
1. Преобразование изображения в оттенки серого
2. Применение гауссовского размытия для уменьшения шума
3. Вычисление градиентов с использованием операторов Собеля
4. Определение порога для величины градиента
5. Создание двоичной маски на основе порога величины градиента
6. Нахождение контуров
7. Заполнение области на изображении переднего плана белым цветом
8. Нахождение координат точек переднего плана
# Результаты
<p align="center">
  <img src="https://user-images.githubusercontent.com/55783463/270391264-fd6a47c1-45bf-4798-a237-cb5662e36658.png" width="256" height="256">
  <img src="https://user-images.githubusercontent.com/55783463/270390783-816a292c-4b1b-48cf-89e3-8c291cd753a2.png" width="256" height="256">
  <img src="https://user-images.githubusercontent.com/55783463/270390880-1fc62142-467c-479b-9db8-4ea4dd19bca9.png" width="256" height="256">
</p>  
<p align="center">
  <img src="https://user-images.githubusercontent.com/55783463/270392304-28ee8b5c-33de-4a10-9ae1-3b3993458392.png" width="256" height="256">
  <img src="https://user-images.githubusercontent.com/55783463/270392011-0a2504b1-d5bb-4237-a18d-63d8ebdf2ec1.png" width="256" height="256">
  <img src="https://user-images.githubusercontent.com/55783463/270391963-55742d03-f07a-44e7-b2be-0bbf34782f1d.png" width="256" height="256">
</p>

