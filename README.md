Scenariul temei: Se cere crearea unui sistem de gestionare a angajaților și departamentelor dintr-o companie. 
Cerințe
1. Clasa de bază Persoană 
-	Crează o clasă de bază Persoană care să conțină atributele comune oricărei persoane din companie:
-	nume (tip char*)
- varsta (tip int)
•	Constructori:
- Constructor implicit. 
-	Constructor copiere + op=.
-	Constructor cu parametrii. Validati inputul primit.
•	Destructor
•	Setteri și getteri pentru nume și varsta. Validati inputul primit.
2. Clasa Angajat (moștenire din Persoană) 
-	Clasa Angajat va moșteni clasa Persoană:
-	Atribute suplimentare pentru Angajat:
-	nume_manager (tip string)
-	salariu (tip double)
-	id_angajat (tip int, identificator unic pentru fiecare angajat).
•	Constructori:
-	Constructor implicit.
-	Constructor copiere + op=
-	Constructor cu parametri. Validati inputul primit.
•	Setteri și getteri pentru toate atributele. Validati inputul primit.
3. Clasa Programator (moștenire din Angajat) 
•	Clasa Programator va moșteni clasa Angajat:
-	Atribute suplimentare pentru Programator:
-	limbajProgramareFolosit (tip char *)
-	fullstack/backend/frontend - enumerare
•	Constructori:
-	Constructor implicit
-	Constructor copiere + op=
-	Constructor cu parametri. Validati inputul primit.
•	Destructor
•	Setteri și getteri pentru toate atributele. Validati inputul primit.
4. Clasa Departament (20% - 0.2 puncte)
•	Clasa Departament va gestiona angajați și va conține următoarele atribute:
-	denumire (tip char*)
-	angajati (un vector dinamic de pointeri la obiecte de tip Angajat).
-	nr_angajati (tip int, numărul de angajați din departament).
o	Constructori:
-	Constructor implicit
-	Constructor copiere + op=
-	Constructor cu un parametru pentru inițializarea denumirii departamentului.
o	Destructor 
•	Metoda salariuTotal care calculează salariul total al tuturor angajaților din departament.
5. Suprascrierea operatorilor << și >> (20% - 0.2 puncte)
•	Suprascrierea operatorului << pentru toate clasele.
•	Suprascrierea operatorului >> pentru toate clasele.
6. Aruncarea și prinderea excepțiilor (10% - 0.1 puncte)
•	Aruncati exceptii in setter/constructori si prindeti eroarea in main prin  blocuri try-catch.
7. Utilizarea variabilelor constante și statice (10% - 0.1 puncte)
•	Definirea unei variabile constante în clasa Angajat pentru salariul minim acceptabil.
•	Definirea unei variabile statice în clasa Departament pentru a ține evidența numărului total de angajați din toate departamentele.
8. Operatorul de atribuire (=) și constructorul de copiere (10% - 0.1 puncte)
•	Implementarea operatorului de atribuire (=) si constructorului de copiere pentru toate clasele.
