# Модули
## Пример реализации
### Файл экспорта (./export.duck)
```
pow = a => a * a
printPow = a => print(pow(a):toString())

< {
  pow
  printPow
}
```
### Файл импорта
```
pow = @import('./export.duck')

twoPows = a => pow.pow(a) * 2
```
Экспорт производится также как и возврат из функции<br>
Импорт производится вызовом compile-time функции