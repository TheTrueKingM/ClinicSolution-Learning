# Библиотека ClinicCore

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)

Библиотека классов для управления данными пациентов клиники. Проект разработан в учебных целях для демонстрации **CI/CD** и **Unit-тестирования**.

## 📋 Функциональность

* Хранение данных пациента (ФИО, Дата рождения).
* Расчет точного возраста с учетом високосных годов.

## 🚀 Как использовать

Пример вызова метода расчета возраста:

```csharp
var patient = new Patient
{
    FullName = "Иванов Иван",
    BirthDate = new DateTime(2000, 1, 1)
};

int age = patient.CalculateAge();
Console.WriteLine($"Возраст пациента: {age}");
