# 3. Выполнение программы

## 3.1 Загрузка и запуск

1. Подключить библиотеку `ClinicCore.dll`.
2. Создать объект `Patient`.

## 3.2 Порядок работы

Для расчета возраста:

1. Заполнить `BirthDate`
2. Вызвать `CalculateAge()`

Пример:

```csharp
var p = new Patient
{
    BirthDate = DateTime.Parse("1990-01-01")
};

int age = p.CalculateAge();
```
