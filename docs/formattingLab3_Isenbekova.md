# Примеры форматирования текста

В Markdown можно писать **жирным текстом**, *курсивом*, ***жирным курсивом*** или использовать ~~зачеркивание~~. Также можно выделять `код внутри строки`.

## Комментированная программа на C# (FormatDemo.cs)

```csharp
using System;

class FormatDemo
{
    static void Main()
    {
        // Запрашивает у пользователя два числа
        Console.Write("Введите первое число: ");
        double number1 = Convert.ToDouble(Console.ReadLine());

        Console.Write("Введите второе число: ");
        double number2 = Convert.ToDouble(Console.ReadLine());

        // Выполняет их сложение
        double sum = number1 + number2;

        // Выводит результаты в форматированном виде
        Console.WriteLine(\$"***Результаты операции: {sum}***");
    }
}
```
