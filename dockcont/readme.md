
![задача 5 пункт 7](https://github.com/Drewplonq/netology/assets/173098668/5a29812a-1d1f-4873-a99c-552ebfcfa8b5)
![задача 5 пункт 6](https://github.com/Drewplonq/netology/assets/173098668/34d10a0d-2f0c-446c-a241-853abfa001c7)
    
<!DOCTYPE html>
<html>
 <head>
  <meta charset="utf-8">
  <title>Увеличение изображения</title>
  <style>
   .scale {
    display: inline-block; /* Строчно-блочный элемент */
    overflow: hidden; /* Скрываем всё за контуром */
   }
   .scale img {
    transition: 1s; /* Время эффекта */
    display: block; /* Убираем небольшой отступ снизу */
   }
   .scale img:hover {
    transform: scale(1.2); /* Увеличиваем масштаб */
   }
  </style>
 </head>
 <body>
  <div class="scale"><img src="dockcont/task5.7.jpg" alt="" class="scale"></div>
  <div class="scale"><img src="dockcont/task5.7.jpg" alt="" class="scale"></div>
  <div class="scale"><img src="dockcont/task5.7.jpg" alt="" class="scale"></div>
 </body>
</html>
