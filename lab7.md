
TASK1:


Sa se scrie o instructiune T-SQL,care ar popula coloana Adresa _ Postala _ Profesor din tabelul
profesori cu valoarea 'mun. Chisinau', unde adresa este necunoscută.


<img width="490" alt="lab 6 ex 1" src="https://user-images.githubusercontent.com/43130876/50059570-9111b380-013d-11e9-8890-20050b8316b7.PNG">


<img width="384" alt="lab 6 ex 1 executat" src="https://user-images.githubusercontent.com/43130876/50059575-a25ac000-013d-11e9-9a67-5d64d0dc0898.PNG">


TASK2:

Sa se modifice schema tabelului grupe, ca sa corespunda urmatoarelor cerinte:
a) Campul Cod_ Grupa sa accepte numai valorile unice și să nu accepte valori necunoscute. 
b) Să se țină cont că cheie primară, deja, este definită asupra coloanei Id_ Grupa. 


<img width="490" alt="lab 6 ex 1" src="https://user-images.githubusercontent.com/43130876/50059593-d504b880-013d-11e9-9d26-913a949dbf55.PNG">

<img width="139" alt="lab 6 ex 2 executat" src="https://user-images.githubusercontent.com/43130876/50059599-e4840180-013d-11e9-9eb3-3622667c35bc.PNG">

TASK3:

La tabelul grupe, să se adauge 2 coloane noi Sef_grupa și Prof_Indrumator, ambele de tip INT. Să se populeze câmpurile 
nou-create cu cele mai potrivite candidaturi în baza criteriilor de mai jos:

a) Șeful grupei trebuie să aibă cea mai bună reușită (medie) din grupă la toate formele de evaluare și la toate disciplinele.
Un student nu poate fi șef de grupa la mai multe grupe.

b) Profesorul îndrumător trebuie să predea un număr maximal posibil de discipline la grupa data. Daca nu există o singură 
candidatură, care corespunde primei cerințe, atunci este ales din grupul de candidați acel cu identificatorul (Id_Profesor) minimal.
Un profesor nu poate fi indrumător la mai multe grupe.

c) Să se scrie instructiunile ALTER, SELECT, UPDATE necesare pentru crearea coloanelor în tabelul grupe, pentru selectarea
candidaților și înserarea datelor.

<img width="528" alt="lab 6 ex 3" src="https://user-images.githubusercontent.com/43130876/50059669-c66ad100-013e-11e9-9f35-29831592b52d.PNG">

<img width="448" alt="sql lab 6 ex 3" src="https://user-images.githubusercontent.com/43130876/50059683-e3070900-013e-11e9-8b57-56808541bbe9.PNG">



TASK4:

Să se scrie o instrucțiune T-SQL, care ar mări toate notele de evaluare șefilor
de grupe cu un punct. Nota maximală (10) nu poate fi mărită.


<img width="425" alt="lab 6 ex 4" src="https://user-images.githubusercontent.com/43130876/50059731-50b33500-013f-11e9-85fe-a1f0be4dd3e1.PNG">


<img width="374" alt="sql lab 6 ex4" src="https://user-images.githubusercontent.com/43130876/50059738-6c1e4000-013f-11e9-8492-129d8fb317f4.PNG">


TASK5:

Sa se creeze un tabel profesori_new, care include urmatoarele coloane: Id_Profesor,Nume _ Profesor,
Prenume _ Profesor, Localitate, Adresa _ 1, Adresa _ 2.
a) Coloana Id_Profesor trebuie sa fie definita drept cheie primara și, în baza ei, sa fie construit un index CLUSTERED.
b) Cîmpul Localitate trebuie sa posede proprietatea DEFAULT= 'mun. Chisinau'.
c) Să se insereze toate datele din tabelul profesori în tabelul profesori_new. Să se scrie, cu acest scop,
un număr potrivit de instrucțiuni T-SQL.
Datele trebuie să fie transferate în felul următor:

<img width="369" alt="sarcini 6" src="https://user-images.githubusercontent.com/43130876/50059748-a25bbf80-013f-11e9-9244-12ded0a6e6f4.PNG">

În coloana Localitate să fie inserata doar informatia despre denumirea localității din coloana-sursă Adresa_Postala_Profesor.
În coloana Adresa_l, doar denumirea străzii. În coloana Adresa_2, să se păstreze numărul casei și (posibil) a apartamentului.


<img width="836" alt="lab 6 ex 5" src="https://user-images.githubusercontent.com/43130876/50059757-d636e500-013f-11e9-9f02-3de3f81c9dee.PNG">


TASK6:

Să se insereze datele in tabelul orarul pentru Grupa= 'CIBJ 71' (Id_ Grupa= 1)pentru ziua de luni. 
Toate lectiile vor avea loc în blocul de studii 'B'. Mai jos, sunt prezentate detaliile de inserare:
(ld_Disciplina = 107, Id_Profesor= 101, Ora ='08:00', Auditoriu = 202);
(Id_Disciplina = 108, Id_Profesor= 101, Ora ='11:30', Auditoriu = 501);
(ld_Disciplina = 119, Id_Profesor= 117, Ora ='13:00', Auditoriu = 501);


<img width="705" alt="lab 6 ex 6" src="https://user-images.githubusercontent.com/43130876/50059779-2150f800-0140-11e9-9202-04941e62969b.PNG">

<img width="349" alt="sql lab 6 ex 6" src="https://user-images.githubusercontent.com/43130876/50059790-3594f500-0140-11e9-912c-62b2bda08e4c.PNG">


TASK7:

Să se scrie expresiile T-SQL necesare pentru a popula tabelul orarul pentru grupa INF171 ,ziua de luni.
Datele necesare pentru inserare trebuie sa fie colectate cu ajutorul instructiunii/instructiunilor SELECT
și introduse in tabelul-destinație, știind că:
lectie #1 (Ora ='08:00', Disciplina = 'Structuri de date si algoritmi', Profesor ='Bivol Ion')
lectie #2 (Ora ='11 :30', Disciplina = 'Programe aplicative', Profesor ='Mircea Sorin')
lectie #3 (Ora ='13:00', Disciplina ='Baze de date', Profesor = 'Micu Elena')


<img width="622" alt="lab 6 ex 7" src="https://user-images.githubusercontent.com/43130876/50059816-860c5280-0140-11e9-827d-5e1c97bd2cc8.PNG">


<img width="325" alt="sql lab 6 ex 7" src="https://user-images.githubusercontent.com/43130876/50059818-91f81480-0140-11e9-9752-d81bfe47d229.PNG">


