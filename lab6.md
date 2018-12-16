<img width="703" alt="lab 7 sarcini propuse" src="https://user-images.githubusercontent.com/43130876/50058789-5f471f80-0132-11e9-9838-1ba6d7681317.PNG">


TASK1:

Creați o diagramă a bazei de date,folosind forma de vizualizare standard, structura căreia este descrisă la începutul
sarcinilor practice din capitolul 4.


<img width="806" alt="lab 7 diagrama 1" src="https://user-images.githubusercontent.com/43130876/50058814-af25e680-0132-11e9-89b2-ff5accc9f892.PNG">


TASK2:


Să se adauge constrîngeri referențiale (legate cu tabelele studenti și profesori) necesare coloanelor Sef_grupa și
Prof_Indrumator (sarcina3, capitolul 6) din tabelul grupe.

<img width="822" alt="7 diagrama 2" src="https://user-images.githubusercontent.com/43130876/50058844-29ef0180-0133-11e9-91d1-d593ca0a277d.PNG">



<img width="819" alt="7 diagrama 3" src="https://user-images.githubusercontent.com/43130876/50058853-53a82880-0133-11e9-9cce-18f311a4cf61.PNG">


<img width="810" alt="7 diagrama 4" src="https://user-images.githubusercontent.com/43130876/50058872-89e5a800-0133-11e9-953f-ea6e43482889.PNG">


TASK3:
 
La diagrama construită, să se adauge și tabelul orarul definit în capitolul 6 al acestei lucrari:tabelul orarul conține
identificatorul disciplinei (ld_Disciplina), identificatorul profesorului(Id_Profesor) și blocul de studii (Bloc).
Cheia tabelului este constituită din trei cîmpuri:identificatorul grupei (Id_ Grupa), ziua lectiei (Z1), ora de inceput
a lectiei (Ora), sala unde are loc lectia (Auditoriu).



<img width="724" alt="lab 7 ex 3" src="https://user-images.githubusercontent.com/43130876/50058968-586ddc00-0135-11e9-97ea-c00b7314152d.PNG">


TASK4:

Tabelul orarul trebuie să conțină și 2 chei secundare: (Zi, Ora, Id_ Grupa, Id_ Profesor) și (Zi, Ora, ld_Grupa, ld_Disciplina).

<img width="824" alt="7 task 4" src="https://user-images.githubusercontent.com/43130876/50058984-923ee280-0135-11e9-88cf-0d79ad7ec6fd.PNG">


<img width="809" alt="7 task 4 -- 2" src="https://user-images.githubusercontent.com/43130876/50059008-f8c40080-0135-11e9-9cf8-4313fb631566.PNG">

TASK5:
În diagrama, de asemenea, trebuie sa se defineasca constrangerile referentiale (FK-PK) ale atributelor ld_Disciplina, ld_Profesor,
Id_ Grupa din tabelului orarul cu atributele tabelelor respective.


<img width="808" alt="task 5" src="https://user-images.githubusercontent.com/43130876/50059041-b7802080-0136-11e9-91b4-9db93d5f0f53.PNG">
 
 
 TASK6:
 
 Creați, în baza de date universitatea, trei scheme noi: cadre_didactice, plan_studii și studenti.Transferați tabelul 
 profesori din schema dbo in schema cadre didactice, ținînd cont de dependentele definite asupra tabelului menționat.
 În același mod să se trateze tabelele orarul,discipline care aparținschemei plan_studii și tabelele studenți, 
 studenti_reusita, care apartin schemei studenti. Se scrie instructiunile SQL respective.


<img width="380" alt="task 6" src="https://user-images.githubusercontent.com/43130876/50059051-d41c5880-0136-11e9-9fb3-8f5b5f026ec7.PNG">

<img width="544" alt="lab 7 task 6" src="https://user-images.githubusercontent.com/43130876/50059104-70def600-0137-11e9-8f1a-7798e160265d.PNG">



<img width="405" alt="--3" src="https://user-images.githubusercontent.com/43130876/50059107-85bb8980-0137-11e9-86db-552316770e9a.PNG">


<img width="463" alt="task 6 result" src="https://user-images.githubusercontent.com/43130876/50059119-a8e63900-0137-11e9-938e-3bf9bbc344ec.PNG">

<img width="380" alt="0" src="https://user-images.githubusercontent.com/43130876/50059127-c0bdbd00-0137-11e9-9547-e280550ebcc3.PNG">


<img width="523" alt="results" src="https://user-images.githubusercontent.com/43130876/50059135-d4692380-0137-11e9-823c-70d21404bc84.PNG">

<img width="423" alt="--" src="https://user-images.githubusercontent.com/43130876/50059154-067a8580-0138-11e9-90c4-24b257d3d71d.PNG">

<img width="669" alt="rez" src="https://user-images.githubusercontent.com/43130876/50059161-1c884600-0138-11e9-9b6b-df4bfbc2a886.PNG">

TASK7:

Modificati 2-3 interogari asupra bazei de date universitatea prezentate in capitolul 4 astfel ca numele tabelelor
accesate sa fie descrise in mod explicit, ținînd cont de faptul ca tabelele au fost mutate in scheme noi.
Interogarea Nr. 19 Gasiti Numele si Prenumele profesorilor, care au predat discipline, in care studentul
"Cosovanu" a fost respins (nota<5) la cel putin o proba.


<img width="810" alt="task 7" src="https://user-images.githubusercontent.com/43130876/50059263-6c1b4180-0139-11e9-82fb-c7066f343f30.PNG">


<img width="288" alt="lab 7 --1" src="https://user-images.githubusercontent.com/43130876/50059273-aedd1980-0139-11e9-8a45-c1ddbd7b77a5.PNG">

<img width="758" alt="task 7 --2" src="https://user-images.githubusercontent.com/43130876/50059284-c9af8e00-0139-11e9-8058-3c5fda5da238.PNG">

<img width="109" alt="lab7 --2" src="https://user-images.githubusercontent.com/43130876/50059296-e3e96c00-0139-11e9-8ddb-25a576147704.PNG">

<img width="537" alt="task 7 --3" src="https://user-images.githubusercontent.com/43130876/50059305-024f6780-013a-11e9-8882-956314b01f98.PNG">

 <img width="270" alt="lab 7 --3" src="https://user-images.githubusercontent.com/43130876/50059311-1004ed00-013a-11e9-8f83-1cf2b385bce0.PNG">



TASK8:

Creați sinonimele respective pentru a simplifica interogările construite în exercițiul precedent 
și reformulați interogările, folosind sinonimele create.

<img width="238" alt="7 task 8" src="https://user-images.githubusercontent.com/43130876/50059328-5eb28700-013a-11e9-9e99-db4f48dad2ef.PNG">

<img width="657" alt="lab 7 t 8 --1" src="https://user-images.githubusercontent.com/43130876/50059343-7a1d9200-013a-11e9-90b0-b0ff808b502b.PNG">

<img width="295" alt="lab 7 task 8 --1" src="https://user-images.githubusercontent.com/43130876/50059353-a0dbc880-013a-11e9-8690-2001fe2e9da7.PNG">

<img width="663" alt="7 t 2" src="https://user-images.githubusercontent.com/43130876/50059358-be109700-013a-11e9-8fe6-6da83b798ddf.PNG">

<img width="114" alt="lab 7 task 8 --2" src="https://user-images.githubusercontent.com/43130876/50059368-cff23a00-013a-11e9-87cf-fcb74fcb6800.PNG">

<img width="655" alt="7 t 3" src="https://user-images.githubusercontent.com/43130876/50059383-eef0cc00-013a-11e9-8a90-c48740c1158c.PNG">

<img width="249" alt="lab 7 task 8 --3" src="https://user-images.githubusercontent.com/43130876/50059390-03cd5f80-013b-11e9-8b6a-7c779371b942.PNG">









