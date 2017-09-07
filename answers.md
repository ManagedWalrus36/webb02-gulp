STEG 1.

1. Pure CSS Images innebär att man skapar en bild med enbart css. Ingen Html eller annat hjälpmedel.
2. För att då om man använda procent för att placera bilden i boxen så kan man sedan bara skala om boxen så följer allt det andra med automatiskt
   storleksmässigt.
3. För annars blir inte HTML koden valid.
4. "margin: auto" centrerar elementet på den horisontella axeln.
5. När man jobbar med procent så finns det en formula. 
   top: (100 - height) / 2
   left: (100 - width) / 2
6. z-index bestämmer vilken djupnivå elementet ska ligga. detta gör man för att kunna stapla element på varandra.
7. det fungerar så att varje parameter mellan kommatecknen inom parenteserna bestämmer vart de tre punkterna i triangeln ska befinna sig inom 	  
   boxen. parametrarna fungerar så här: (left% top%, left% top%, left% top%).
   
STEG 2.
1. Du deklarerar en sass variabel med $variabelnamn. ex. $white: #FFFFFF.
2. denna preprocessor gör så att man bara behöver skriva .KLASSNAMN istället för hela div taggen. så istället för "<div class="KLASSNAMN"></div>"
   så skriver man .KLASSNAMN bara.