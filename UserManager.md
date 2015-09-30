Skapa test för en användare/lösenordhanterare med följande krav.

* Kunna kontrollera om ett användarnamn och lösenordspar är giltigt. Returnerar true eller false.
* Kunna lägga till en ny användare.
* Specialtecknen @, #, $, eller åäö är inte giltiga i användarnamn.
* När en ny användare läggs till ska ett automatgenererat lösenord returneras.
* Lösenorder som är associerat med en användare ska kunna bytas genom att skicka in gamla och nya lösenordet. Returnerar true om bytet gick bra.
* Giltiga lösenord ska ha minst 7 tecken och både siffror och bokstäver ska ingå.
* Ett hashvärde för den ihopslagna strängen användarnamn+lösenord ska kunna hämtas us. 
