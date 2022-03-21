# Codewars Sum of Positive
<h3>Задача на сайте Codewars, JavaScript</h3>
<p>
  Массив чисел, возвращаете сумму всех положительных единиц. 
<br>
  Пример [1,-4,7,12] => 1 + 7 + 12 = 20
<br>
  Решение задачи
</p>
<br>
function positiveSum(arr) {
<br>
 var sum = 0;
 <br>
 for(var i = 0; i < arr.length; i++) {
 <br>
   if(arr[i] > 0) {
   <br>
    sum += arr[i];
    <br>
  }
  <br>
 }
 <br>
return sum;
}
