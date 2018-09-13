#### Добавяне на DrawRatings метода

Добавяме метод **`DrawRatings`** в контролера **`HomeController`**. Отваряме файла **`Controllers/HomeController.cs`** и добавяме следния код:

![](/assets/chapter-6-images/11.Ratings-05.png)

Горният код взима въведеното число **`rating`**, прави малко пресмятания и изчислява броя **пълни звездички**, броя **празни звездички** и броя **половинки звездички**, след което генерира HTML код, който нарежда няколко картинки със звездички една след друга, за да сглоби от тях картинката с рейтинга. Подготвеният HTML код се записва във **`ViewBag.Stars`** за визуализация от изгледа **`Index.cshtml`**. Допълнително се запазва и изпратеният рейтинг (като число) във **`ViewBag.Rating`**, за да се зададе в полето за рейтинг в изгледа. За да се ориентирате по-добре в проекта, може да си помогнете с картинката от Visual Studio по-долу:

![](/assets/chapter-6-images/11.Ratings-06.png)