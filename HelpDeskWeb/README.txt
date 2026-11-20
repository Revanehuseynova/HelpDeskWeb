HelpDeskWeb - Laboratoriya işi № 9 (ASP.NET Core MVC)

İşə salmaq:
1. HelpDeskWeb.sln faylını Visual Studio 2022-də açın.
2. NuGet paketləri avtomatik bərpa olunacaq (internet lazımdır).
3. F5 basın. helpdesk.db faylı ilk işə düşəndə avtomatik yaradılır.

Qeyd: .NET 8 SDK üçün hazırlanıb. Başqa .NET versiyası istifadə edirsinizsə,
HelpDeskWeb.csproj-da TargetFramework və EF Core paketlərinin versiyasını dəyişin
(məs. .NET 10 üçün net10.0 və 10.0.*).

Əlavə fərdi tapşırıqlar:
- Ana səhifədə ümumi müraciət sayı
- High prioritetli müraciətlərin fərqli rənglə göstərilməsi
- Başlığa görə axtarış və kateqoriyaya görə filtr
