# :pushpin: Video-Rental-Shop-ETL-process

:small_red_triangle_down: Kako bi se kreirao sam ETL proces neophodno je korišćenje sledećih alata: dodatak za Visual Studio pod nazivom SSDT (*SQL Server Data Tools*) koji sadrži BI alate među kojima je nama trenutno od značaja *SQL Server Integration Services*, kao i sam *SQL Server* i SSMS (*SQL Server Management Studio*). Postupak ETL procesa započinje kreiranjem tabela dimenzija nizom DDL naredbi koristeći *Execute SQL Task*, a nakon toga se učitavaju podaci iz izvornih fajlova uz pomoć *Data Flow Task-ova* za svaku dimenziju. Kako bi se DDL naredbe izvršile uspešno prvo je neophodno kreirati konekciju na bazu podataka u koju ćemo da skladištimo destinacijske tabele.

:white_check_mark: Pokrenut ETL proces treba da izgleda kao na slici ispod:

![36](https://user-images.githubusercontent.com/61964257/145219747-e1618d45-ab42-429d-8f4c-fea43260362a.PNG)

:white_check_mark: Konačan izgled činjenične tabele *Rental_fact*:

![37](https://user-images.githubusercontent.com/61964257/145219749-49faa887-834b-4f77-b1ca-24c8e0c2f4d8.PNG)

## :white_check_mark: *Category_dim*:
![30](https://user-images.githubusercontent.com/61964257/145219728-74db57f5-ec21-4b16-b45d-b4ca2d04c005.PNG)

## :white_check_mark: *Actor_dim*:

![31](https://user-images.githubusercontent.com/61964257/145219732-c8653881-a9be-458f-b8a8-fdd2b8bf1ad8.PNG)

## :white_check_mark: *Customer_dim*:

![32](https://user-images.githubusercontent.com/61964257/145219734-7fb4de52-dff5-44a5-a147-fbdbf600e30f.PNG)

## :white_check_mark: *Staff_dim*:

![33](https://user-images.githubusercontent.com/61964257/145219735-080d63fe-27fb-465d-b318-adb2f3ab6373.PNG)

## :white_check_mark: *Store_dim*:

![34](https://user-images.githubusercontent.com/61964257/145219736-05789d09-f15a-4484-950a-b4f8277c549a.PNG)

## :white_check_mark: *Film_dim*:

![35](https://user-images.githubusercontent.com/61964257/145219746-fb39a24f-8e0a-4333-95c5-19811717cd66.PNG)


