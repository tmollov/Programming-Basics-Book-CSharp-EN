### Други методи за закръгляне

В случай, че искаме винаги да закръгляме надолу можем вместо **`Math.Round(…)`** да използваме друг метод - **`Math.Floor(…)`**, който винаги закръгля надолу, но също така винаги закръгля до цяло число. Например, ако имаме числото 5.99 и използваме **`Math.Floor(5.99)`**, ще получим числото **5**.

Можем и да направим точно обратното - винаги да закръгляме нагоре, използвайки метода **`Math.Ceiling(…)`**. Отново, ако имаме число примерно 5.11 и използваме **`Math.Ceiling(5.11)`**, ще получим 6. Ето и няколко примера:

```csharp
var numberToFloor = 5.99;
Console.WriteLine(Math.Floor(numberToFloor));
// Tова ще отпечата на конзолата 5

var numberToCeiling = 5.11;
Console.WriteLine(Math.Ceiling(numberToCiling));
// Tова ще отпечата на конзолата 6
```