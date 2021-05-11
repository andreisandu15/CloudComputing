PROIECT CLOUD COMPUTING

Definitie API:
API reprezinta acronimul în limba engleza pentru Application Programming Interface, adica interfata de programare a unei aplicatii. O librarie API poate fi privita ca un set de functii puse la dispozitia programatorilor in sensul efectuarii unor anumite operatii sau sarcini. 
Un API este o colectie de functii continute in librarii statice sau dinamice, ce pot fi folosite la unmoment dat intr-o aplicatie pentru a efectua diverse sarcini.
Librariile API  contin fisierele cu definitiile functiilor utilizate de producatorul respectiv, librariile statice necesare în momentul compilarii, sau librariile dinamice necesare in monentul rularii. API-urile contin de asemenea instructiuni necesare programatorilor in ceea ce priveste apelul functiilor sau compilarea codului sursa.
TheCocktailDB : un serviciu deschis de bauturi si cocktailuri
Puteți utiliza cheia API de testare „1” în timpul dezvoltării aplicației dvs. sau pentru utilizare educațională (consultați linkurile de testare de mai jos)
Cu toate acestea, trebuie să vă înscrieți la Patreon dacă doriți o cheie API de producție dacă o lansați public într-un magazin de aplicații.
Metodele permise de acest site pentru developeri sunt multe si diverse:
Search cocktail by name:
www.thecocktaildb.com/api/json/v1/1/search.php?s=margarita:
List all cocktails by first letter:
www.thecocktaildb.com/api/json/v1/1/search.php?f=a
Search ingredient by name:
www.thecocktaildb.com/api/json/v1/1/search.php?i=vodka
Lookup a random cocktail:
www.thecocktaildb.com/api/json/v1/1/random.php
Lookup a selection of 10 random cocktails (only available to $2+ Patreon supporters):
www.thecocktaildb.com/api/json/v1/1/randomselection.php


JokeAPI:
JokeAPI este un API REST care servește glume uniform și bine formatate. Poate fi folosit fără jeton API, membru, înregistrare sau plată. Suportă o varietate de filtre care pot fi aplicate pentru a obține doar glumele potrivite de care aveți nevoie. Utilizarea este foarte simplă și similară cu alte API-uri RESTful și necesită doar cunoștințe de bază despre solicitările HTTP și JSON, XML, YAML sau text simplu.
O bibliotecă de împachetare traduce unele API într-o interfață mai ușor de utilizat pentru o anumită limbă sau mediu.
În cazul API-urilor RESTful, cum ar fi JokeAPI, o bibliotecă wrapper o face astfel încât să puteți utiliza caracteristicile limbii dvs. pentru a comunica cu API-ul, în timp ce wrapperul va face toate cererile HTTP pentru dvs. în fundal.

 
 
 


Aplicatia propriu-zisa:
Am utilizat un modul de node.js simplu in Cloud9 IDE unde au fost creat scriptul index.js, dupa care am instalat pachetele necesare, adica cele de JSON, iar pt jQurey am folosit api-ul public al celor de la Google care contine libraria.
 
 
Dupa ce am terminat de lucrat la aplicatie, sau chiar in timp, am impins fisierele in Git, astfel:
 
 
 
 
 
Referinte:
https://www.thecocktaildb.com/
https://jokeapi.dev/
https://aws.amazon.com/
