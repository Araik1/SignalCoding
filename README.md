# SignalCoding
Имитационная модель кодирования сигнала. Python 3.7.2

Цель работы: изучение методов физического и логического кодирования в вычислительной сети на физическом уровне ЭМВОС. Создание имитационной модели кодирования сигнала.

---
<table>
  <tr>
    <td>Тип входных данных</td>
    <td>Логическое кодирование</td>
    <td>Скремблер</td>
    <td>Физичекое кодирование</td>
  </tr>
  <tr>
    <td>Rar архив</td>
    <td>8B/10B</td>
    <td>Bi = Ai xor Bi–3 xor Bi–7</td>
    <td>4B/3T</td>
  </tr>
</table>

#### Этапы выполнения работы
<ul>
  <li> Сериализовать исходных данных; </li>
  <li> К полученным данным применить логическое кодирование; </li>
  <li> К кодированной последовательности применить метод избыточных кодов; </li>
  <li> Закодировать последовательность 0 и 1 при помощи одного из методов физического кодирования; </li>
  <li> Показать имитацию передачи импульсов по среде передачи данных; </li>
  <li> Декодировать импульсы в последовательности 0 и 1; </li>
  <li> Дескремблировать полученную последовательность; </li>
  <li> Декодировать последовательность логическим кодом; </li>
  <li> Дессериализовать последовательность; </li>
  <li> Вывести данные </li>
</ul>
