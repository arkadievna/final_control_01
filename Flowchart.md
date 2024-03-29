# Блок-схема алгоритма

1. Блок-схема начинается с прямоугольника, в котором текст "Начало".
2. Из прямоугольника "Начало" идёт стрелка, указывающая на ромб "Ввод массива".
3. Из ромба "Ввод массива" идут две стрелки:
   * первая стрелка идёт вниз, указывает на ромб "Проверка длины элемента строки"
   * вторая стрелка идёт вправо, указывает на прямоуголник "Формирование нового массива"
4. После проверки длины элемента строки в ромбе "Проверка длины элемента строки", есть два варианта дальнейшего пути:
   * если проверка истинна, то из ромба идет стрелка к прямоугольнику "Добавление элемента в новый массив"
   * если ложь, то из ромба стрелка возвращается к началу цикла "Ввод массива"
5. Из прямоугольника "Добавление элемента в новый массив" идет стрелка к прямоугольнику "Формирование нового массива".
6. В прямоугольнике "Формирование нового массива" выполняется добавление элементов в новый массив до конца ввода массива.
7. После завершения ввода всех элементов массива, из прямоугольника "Формирование нового массива" стрелка идёт к прямоугольнику "Вывод нового массива".
8. От прямоугольника "Вывод нового массива" стрелка идёт к прямоугольнику "Конец".
9. Прямоугольником "Конец" блок-схема завершается.