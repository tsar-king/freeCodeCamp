---
id: 5900f4a71000cf542c50ffba
challengeType: 5
title: 'Problem 315: Digital root clocks'
videoUrl: ''
localeTitle: 'Задача 315: Цифровые корневые часы'
---

## Description
<section id="description"> Сэму и Максу предлагается преобразовать два цифровых такта в два «цифровых корневых» тактовых сигнала. Цифровые корневые часы - это цифровые часы, которые шаг за шагом вычисляют цифровые корни. <p> Когда на часах подается число, оно покажет его, а затем оно начнет расчет, показывая все промежуточные значения, пока не достигнет результата. Например, если на часах подается номер 137, он будет показывать: «137» → «11» → «2», а затем он станет черным, ожидая следующего номера. </p><p> Каждый цифровой номер состоит из нескольких легких сегментов: трех горизонтальных (верхний, средний, нижний) и четырех вертикальных (верхний левый, правый верхний, нижний левый, правый нижний). Номер «1» выполнен из вертикальных верхних и нижних правых, номер «4» выполнен по горизонтали и вертикали сверху-слева, справа вверху и внизу справа. Номер «8» освещает их все. </p><p> Часы потребляют энергию только тогда, когда сегменты включаются / выключаются. Включение «2» будет стоить 5 переходов, а «7» будет стоить всего 4 перехода. </p><p> Сэм и Макс построили два разных часовых механизма. </p><p> Часы Сэма подаются, например, номер 137: часы показывают «137», затем панель выключается, затем включается следующее число («11»), затем панель снова выключается и, наконец, последнее число («2 &quot;) включается и через некоторое время выключается. Для примера, с номером 137, часы Сэма требуют: «137»: (2 + 5 + 4) × 2 = 22 перехода («137» вкл / выкл). «11»: (2 + 2) × 2 = 8 переходов («11» включено / выключено). «2»: (5) × 2 = 10 переходов («2» вкл / выкл). </p><p> Всего 40 переходов. </p><p> Часы Макс работают по-разному. Вместо того, чтобы отключать всю панель, она достаточно умна, чтобы отключать только те сегменты, которые не понадобятся для следующего номера. Для числа 137 часы Max требуют: «137»: 2 + 5 + 4 = 11 переходов («137») 7 переходов (чтобы отключить сегменты, которые не нужны для номера «11»). «11»: 0 переходов (число «11» уже включено правильно) 3 перехода (для выключения первого «1» и нижней части второго «1», верхняя часть - с номером «2») , «2»: 4 перехода (чтобы включить оставшиеся сегменты, чтобы получить «2») 5 переходов (чтобы отключить номер «2»). </p><p> Всего 30 переходов. </p><p> Конечно, часы Макса потребляют меньше энергии, чем у Сэма. Два часа подают все простые числа между A = 107 и B = 2 × 107. Найдите разницу между общим количеством переходов, необходимых часам Сэма, и тем, что нужно Максу. </p></section>

## Instructions
<section id="instructions">
</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: <code>euler315()</code> должен вернуть 13625242.
    testString: 'assert.strictEqual(euler315(), 13625242, "<code>euler315()</code> should return 13625242.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
function euler315() {
  // Good luck!
  return true;
}

euler315();

```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
