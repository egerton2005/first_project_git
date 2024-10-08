# Общее описание решения
Данный проект реализован на языке **python** для вычесления площадей и преиметров геометрических фигур:
* Окружность
* Прямоугольник
* Квадрат
* Треугольник
## Функции для вычесления площади
- Окружность: *S = πR²*
  ```
  def area(r):
    return math.pi * r * r
  ```
  > Пример вызова: area(4) - вернет площадь окружности с радиусом 4
- Прямоугольник: *S = ab*
  ```
  def area(a, b): 
    return a * b 
  ```
  > Пример вызова: area(3, 4) - вернет площадь прямоугольника со сторонами 3 и 4
- Квадрат: *S = a²*
  ```
  def area(a):
    return a * a
  ```
  > Пример вызова: area(4) - вернет площадь квадрата со стороной 4
- Треугольник: *S = a*h/2*
  ```
  def area(a, h): 
    return a * h / 2 
  ```
  > Пример вызова: area(4, 2) - вернет площадь треугольника со стороной 4 и высотой 2

## Функции для вычесления периметра
- Окружность: *P = 2πR*
  ```
  def perimeter(r):
    return 2 * math.pi * r
  ```
  > Пример вызова: perimeter(4) - вернет периметр окружности с радиусом 4
- Прямоугольник: *P = 2a + 2b*
  ```
  def perimeter(a, b):
    return (a + b)*2
  ```
  > Пример вызова: perimeter(4, 5) - вернет периметр прямоугольника со сторонами 4 и 5
- Квадрат: *P = 4a*
  ```
  def perimeter(a):
    return 4 * a
  ```
  > Пример вызова: perimeter(4) - вернет периметр квадрата со стороной 4
- Треугольник: *P = a + b + c*
  ```
  def perimeter(a, b, c): 
    return a + b + c 
  ```
  > Пример вызова: perimeter(4, 5, 6) - вернет периметр треугольника со сторонами 4, 5 и 6
  # История коммитов и их хэшей
    1) L-03: Circle and square added - 8ba9aeb3cea847b63a91ac378a2a6db758682460
    2) L-03: Docs added - d078c8d9ee6155f3cb0e577d28d337b791de28e2
    3) Add_file(rectangle.py) - e8254ad640fcb8c6725e7daa1fc71bea607934bb
    4) Fix_file(rectangle.py), Add_file(triangle.py) - d4eb086ebf4c9fd022329d9df598e92ccb35c9fc
    5) Merge pull request #1 - 123e7e7a56f14c5ed6b5e1b7d825e5e923e16fb7
    6) Add_comments(all files) - fca4d783cf95f00aa84db6bbecce1ed73137f194
    7) Merge pull request #2 - dfacf8bf73bc0b80a8259e152e7eecf830bb6242
all
