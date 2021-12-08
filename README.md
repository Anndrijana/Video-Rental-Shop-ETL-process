# Video-Rental-Shop-ETL-process

Kako bi se kreirao sam ETL proces neophodno je korišćenje sledećih alata: dodatak za Visual Studio pod nazivom SSDT (*SQL Server Data Tools*) koji sadrži BI alate među kojima je nama trenutno od značaja *SQL Server Integration Services*, kao i sam *SQL Server* i SSMS (*SQL Server Management Studio*). Postupak ETL procesa započinje kreiranjem tabela dimenzija nizom DDL naredbi koristeći *Execute SQL Task*, a nakon toga se učitavaju podaci iz izvornih fajlova uz pomoć *Data Flow Task-ova* za svaku dimenziju. Kako bi se DDL naredbe izvršile uspešno prvo je neophodno kreirati konekciju na bazu podataka u koju ćemo da skladištimo destinacijske tabele.

Pokrenut ETL proces treba da izgleda kao na slici ispod:

Konačan izgled činjenične tabele *Rental_fact*:

