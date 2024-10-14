## LABORATOR NR. 2. Cereri HTTP și șablonizare în Laravel
### SCOPUL LUCRARII: Să studiez principiile de bază ale lucrului cu cererile HTTP în Laravel și șablonizarea folosind Blade, pe baza unei aplicații web „To-Do App pentru echipe” — o aplicație pentru gestionarea sarcinilor în cadrul unei echipe.

Am create o aplicatie pentru gestionarea sarcinilor "To-Do App", folosind principiile de baza ale lucrului cu cererile HTTP in Laravel si sablonizarea folosind Blade.

## Intrebari de control

1. Ce este un controller de resurse în Laravel și ce rute creează?

    In Laravel, un controller de resurse este un tip de controller care ajuta la crearea unei structuri uniforme pentru operatiile de tip CRUD (Create, Read, Update, Delete) , totodata, acesta genereaza rute pentru fiecare metoda - index, create, store, show, edit, update, destroy.

2. Explicati diferenta intre crearea manuala a rutelor si utilizarea unui controller de resurse.

   Fiecare abordare are propriile avantaje si dezavantaje, iar alegerea depinde de complexitatea aplicatiei si preferintele dezvoltatorului. Crearea manuala a rutelor este ideala pentru situatii in care anumite rute necesita functionalitati specifice, cum ar fi prefixe diferite sau URL-uri neobisnuite. In schimb, utilizarea unui controller de resurse permite generarea automata a tuturor rutelor CRUD, cu o structura si URL-uri standardizate.

3. Ce avantaje oferă utilizarea componentelor anonime Blade?

   Componentele anonime Blade in Laravel asigura modularitate si o reutilizare usoara, separand logica de prezentare si imbunatatind coerenta interfetei utilizator. Prin utilizarea directivei @props, componentele devin personalizabile, reducand astfel codul duplicat si facilitand intretinerea aplicatiei.

4. Ce metode de cereri HTTP sunt folosite pentru a executa operațiunile CRUD?

   -  `Create`- Foloseste metoda `POST` pentru a crea o noua resursa in server.
   -  `Read`- Foloseste metoda `GET` pentru a citi sau accesa o resursa existenta.
   -  `Update`- Utilizeaza metodele `PUT` sau `PATCH` pentru a actualiza o resursa existenta.
   -  `Delete`- Foloseste metoda `DELETE` pentru a sterge o resursa.
