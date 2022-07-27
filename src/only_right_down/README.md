<h1 class="title">Только вправо или вниз (32%)</h1>
<p><a href="https://acmp.ru/index.asp?main=task&id_task=165" target="_blank">Ссылка на задачу</a></p>
<p><b>Время: 1 сек.<br>Память: 16 Мб<br>Сложность: 32%</b></p>
<p>Игровое поле N×M заполняется целыми числами, одно неотрицательное целое число в каждой клетке. Цель игры состоит в том, чтобы пройти по любому разрешенному пути от верхнего левого угла до правого нижнего. Целое число в каждой клетке указывает, какой длины шаг должен быть из текущей клетки. Все шаги могут быть или направо или вниз. Если в результате какого-либо шага игрок покидает пределы поля, такой шаг запрещается.</p>
<p>На рис. 1 приведен пример игрового поля 3×4, где сплошная окружность показывает положение начала, а пунктирная окружность – цель. Рис. 2 показывает три возможных пути от начала до цели для рассматриваемого примера игрового поля, с удаленными промежуточными числами.</p>
<p>Требуется написать программу, которая определит число различных вариантов путей от верхнего левого угла до правого нижнего.</p>
<h2>Формат ввода</h2>
<p class=text>
Входной файл INPUT.TXT содержит в первой строке размеры поля N (1 ≤ N ≤ 70) и M (1 ≤ M ≤ 70). В последующих N строках входного файла, каждая из которых описывает отдельную строку игрового поля, записаны через пробел по M целых чисел от 0 до 100 – длины шагов из клеток данной строки.
</p>
<h2>Формат вывода</h2>
<p class=text>
Выходной файл OUTPUT.TXT должен содержать одно число - число различных вариантов путей от верхнего левого угла до правого нижнего. Для каждого поля будет менее чем 2<sup>31</sup> различных путей.
</p>
<h3>Примеры</h3>
<table class="sample-tests">
  <thead>
     <tr>
        <th>Ввод</th>
        <th>Вывод</th>
     </tr>
  </thead>
  <tbody>
     <tr>
        <td>3 4<br>
            2 1 1 2<br>
            3 2 1 44<br>
            3 1 1 0</td>
        <td>3</td>
     </tr>
  </tbody>
</table>