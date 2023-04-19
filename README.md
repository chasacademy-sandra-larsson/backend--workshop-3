
# Backendutveckling och API:er #3: Skapa REST API

👋 Se Linus Rudbecks föreläsning från 17 april ✅ 

### Innehåll denna workshop:

* Skapa REST API
* Använda Postman eller Insomnnia för att testa API:et
* Mer kunskap om Express och routing
* Testa användning av middleware (även om det inte behöver användas i REST API:et som skapas denna workshop)
* Struktera upp applikation för ett API och flera resurser och routes
* Använda npm paketet dotenv för att hantera miljövariabler smidigt och säkert

### Redovisning:
* Du redovisar resultatet av sida för en eller flera resurser med CRUD

***Om du inte kan delta på workshopen, redovisar du ovanstående nästkommande workshop***

# 👩🏽‍💻 Uppvärmning: Testa API med Postman (eller Insomnia)


Skapa en testfil, exempelvis ```routes-test.js```, använd Express och CRUD:a för HTTP-metoderna GET, POST, PUT, PATCH, DELETE och skickar ut lämplig sträng på ```res.send```. Testa med Postman att alla routes fungerar. Prova också att använda en eller flera url-parametrar.

Bonus: Testa att skapa en valfri middleware. 

Ta hjälp av dokumentation på [https://expressjs.com/](https://expressjs.com/)

Se även över HTTP-statuskoder! [https://developer.mozilla.org/en-US/docs/Web/HTTP/Status](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)


# 👩🏽‍💻 Övning: Skapa REST API för minst 2 resurser

Följetong från förra veckan! D.v.s bygga vidare på den kod du har för CRUD för resurser med Node.js/Express/MongoDB.

Målet denna workshop är att skapa ett REST API för minst 2 st resurser med CRUD mot MongoDB. Du ska testa API:et med Postman eller Insomnia. 
Du ska även strukturera din kod enligt Linus föreläsning eller enligt egna preferenser, d.v.s det som krävs för ett REST API med minst 2 resurser.

# 💬 Diskutera/Bra att kunna

* Vad är fördelen att utveckla ett API för backend?
* Vad är ett REST API?
* Ha koll på klient-server modellen, request/response-cykeln
* Ha koll på HTTP-statuskoder
* Du kanske inte använder middleware denna workshop, men vad kan det användas till?


