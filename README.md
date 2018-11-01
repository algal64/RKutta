# Variant 19 (Sukach Maxim, BS17-03)

#### Содержание:
1. [Уравнение](#eq)
2. [Решение](#solution)
2. [Метод Эйлера](#euler)
3. [Усовершенствованный метод Эйлера](#imp_euler)
4. [Классический метод Рунге-Кутты](#runge_kutta)
5. [Сравнение методов для заданной задачи](#comparing)
6. [Заключение](#conclusion)
7. [Запуск](#launch)
8. [Ссылки](#links)

## <a name="eq"></a>Уравнение
№19:

<img src="https://latex.codecogs.com/gif.latex?\frac{dy}{dx}&space;=&space;2y^{1/2}&space;&plus;&space;2y">

## <a name="solution"></a>Решение
<img src="https://latex.codecogs.com/gif.latex?\newline\frac{dy}{dx}&space;=&space;2y^{1/2}&plus;2y&space;\newline&space;\newline&space;\frac{dy}{2(y^{1/2}&plus;y)}=dx&space;\newline&space;\newline&space;\int&space;\frac{dy}{2(y^{1/2}&plus;y)}=\int&space;dx&space;\newline&space;\newline&space;\ln&space;(\sqrt&space;y&space;&plus;&space;1)&space;=&space;x&space;&plus;&space;C_{1}&space;\newline&space;\newline&space;\sqrt&space;y&space;&plus;&space;1&space;=&space;e^{x&space;&plus;&space;C_{1}}&space;\newline&space;\newline&space;y&space;=&space;(e^{x&plus;C_{1}}&space;-&space;1)^{2}" title="\frac{dy}{dx} = 2y^{1/2}+2y \newline \newline \frac{dy}{2(y^{1/2}+y)}=dx \newline \newline \int \frac{dy}{2(y^{1/2}+y)}=\int dx \newline \newline \ln (\sqrt y + 1) = x + C_{1} \newline \newline \sqrt y + 1 = e^{x + C_{1}} \newline \newline y = (e^{x+C_{1}} - 1)^{2}">

Найдем <img src="https://latex.codecogs.com/gif.latex?C_{1}">

<img src="https://latex.codecogs.com/gif.latex?\newline&space;x_{0}&space;=&space;0,&space;y_{0}&space;=&space;1&space;\newline&space;\newline&space;1=(e^{C_{1}}-1)^{2}&space;\newline&space;\newline&space;e^{2C_{1}}=2e^{C_{1}}&space;\newline&space;\newline&space;e^{C_{1}}&space;=&space;2&space;\newline&space;\newline&space;C_{1}&space;=&space;ln(2)&space;\approx&space;0.693">

Отлично, наше решение принимает вид:

<img src="https://latex.codecogs.com/gif.latex?y&space;=&space;(e^{x&plus;0.693}&space;-&space;1)^{2}">


## <a name="euler"></a>Метод Эйлера

## <a name="imp_euler"></a>Усовершенствованный метод Эйлера

## <a name="runge_kutta"></a>Классический метод Рунге-Кутты

## <a name="comparing"></a>Сравнение методов для заданной задачи

## <a name="conclusion"></a>Заключение

## <a name="launch"></a>Запуск

### <a name="links"></a>Ссылки
