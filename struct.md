# Структура
## Примеры реализации
```
mystruct = {
  key1 = 1
  key2 = 2
  key3 = 3
  key4 = 4
}
```
Простая структура
<br><br>
```
mystruct = {
  key1 = 1
  key2 = 2
}
anotherstruct = {
  key1 = 2
  key2 = 3
  key3 = 4
  key4 = 5
}
printStruct = (s: myStruct) => {
  print(s.key1:toString())
}

printStruct(anotherStruct)
```
Данный пример компилируется и валиден
<br><br>