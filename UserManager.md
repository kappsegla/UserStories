Skapa test för en användare/lösenordhanterare med följande krav.

* Kunna kontrollera om ett användarnamn och lösenordspar är giltigt. Returnerar true eller false.
* Kunna lägga till en ny användare.
* Specialtecknen @, #, $, eller åäö är inte giltiga i användarnamn.
* När en ny användare läggs till ska ett automatgenererat lösenord returneras.
* Lösenorder som är associerat med en användare ska kunna bytas genom att skicka in gamla och nya lösenordet.
* Giltiga lösenord ska ha minst 7 tecken och både siffror och bokstäver ska ingå.
* Om verifiering av användarnamn/lösenord misslyckas 3 gånger i rad för en användare ska kontot markeras som låst och alla verifieringar ska i fortsättningen misslyckas.
* Om försök sker att byta lösenord där gamla lösenordet är felaktigt, kontot är stängt eller nya lösenordet är felaktigt ska en exception av typen ArgumentException kastas.
Extra:
* Ett hashvärde (SHA512) för den ihopslagna strängen användarnamn+lösenord ska kunna hämtas ut.
* Hashvärdet ska vara returneras som en sträng med BASE64-kodning.
