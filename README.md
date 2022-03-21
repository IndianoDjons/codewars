# Codewars Sum of Positive
Задача на сайте Codewars, JavaScript

// Массив чисел, возвращаете сумму всех положительных единиц. // Пример [1,-4,7,12] => 1 + 7 + 12 = 20
// Решение задачи

function positiveSum(arr) {
 var sum = 0;
 for(var i = 0; i < arr.length; i++) {
   if(arr[i] > 0) {
    sum += arr[i];
  }
 }
return sum;
}
