# Lab-5
Вариант 6
Формируется матрица F следующим образом: скопировать в нее А и если А симметрична относительно побочной диагонали, то поменять местами симметрично В и  D, иначе D и Е поменять местами несимметрично. При этом матрица А не меняется. После чего если определитель матрицы А больше суммы диагональных элементов матрицы F, то вычисляется выражение: A-1 * A ^ T – K * F-1, иначе вычисляется выражение (A^Т +G-F^Т)*K, где G-нижняя треугольная матрица, полученная из А. Выводятся по мере формирования А, F и все матричные операции последовательно.
