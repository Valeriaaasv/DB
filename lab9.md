
TASK1:
  
  Sa se creeze proceduri stocate in baza exercitiilor (2 exercitii) din capitolul 4. 
  Parametrii de intrare trebuie sa corespunda criteriilor din clauzele WHERE ale exercitiilor respective .
  
  
  <img width="662" alt="lab 9 111111" src="https://user-images.githubusercontent.com/43130876/50060204-c4f0d700-0145-11e9-98d3-51defb3f6ecb.PNG">



TASK2:


Sa se creeze o procedura stocata, care nu are niciun parametru de intrare si poseda un parametru de iesire.
 Parametrul de ie~ire trebuie sa returneze numarul de studenti,care nu au sustinut eel putin o forma de evaluare
 (nota mai mica de 5 sau valoare NULL).


<img width="717" alt="9 task 2" src="https://user-images.githubusercontent.com/43130876/50060224-0d0ff980-0146-11e9-8867-c17687da1e05.PNG">



TASK3:


Sa se creeze o procedura stocata, care ar insera in baza de date informatii despre un student nou.
In calitate de parametri de intrare sa serveasca datele personale ale studentului nou si Cod_Grupa.
Sa se genereze toate intrarile-cheie necesare in tabelul studenti_reusita.
Notele de evaluare sa fie inserate ca NULL.


<img width="809" alt="9 task 3" src="https://user-images.githubusercontent.com/43130876/50060233-40eb1f00-0146-11e9-87ba-53a336c4bb22.PNG">




TASK4:



Fie ca un profesor se elibereaza din functie la mijlocul semestrului.
Sa se creeze o procedura stocata care ar reatribui inregistrarile din tabelul studenti_reusita unui alt profesor.
Parametri de intrare: numele si prenumele profesorului vechi, numele si prenumele profesorului nou, disciplina. 
in cazul in care datele inserate sunt incorecte sau incomplete, sa se afi~eze un mesaj de avertizare.



<img width="742" alt="9 task 4" src="https://user-images.githubusercontent.com/43130876/50060249-814a9d00-0146-11e9-851f-f54d9a27d223.PNG">



TASK5:


Sa se creeze o procedura stocata care ar forma o lista cu primii 3 cei mai buni studenti la o disciplina,
si acestor studenti sa le fie marita nota la examenul final cu un punct (nota maximala posibila este 10).
In calitate de parametru de intrare, va servi denumirea disciplinei.
Procedura sa returneze urmatoarele campuri: Cod_Grupa, Nume_Prenume_Student, Disciplina, Nota_ Veche, Nota_Noua.


<img width="829" alt="9 task 5" src="https://user-images.githubusercontent.com/43130876/50060264-b0610e80-0146-11e9-818f-ff0b7f512367.PNG">




TASK6:


Sa se creeze functii definite de utilizator in baza exercitiilor (2 exercitii) din capitolul 4.
Parametrii de intrare trebuie sa corespunda criteriilor din clauzele WHERE ale exercitiilor respective.



<img width="765" alt="9 task 6" src="https://user-images.githubusercontent.com/43130876/50060285-e7cfbb00-0146-11e9-9d10-002e355aec48.PNG">





TASK7:

Sa se scrie functia care ar calcula varsta studentului. 
Sa se defineasca urmatorul format al functiei: <nume_functie>(<Data_Nastere_Student>).





<img width="797" alt="9 task 7" src="https://user-images.githubusercontent.com/43130876/50060306-282f3900-0147-11e9-9aa8-87729649c582.PNG">

<img width="283" alt="9 task 7--2" src="https://user-images.githubusercontent.com/43130876/50060313-33826480-0147-11e9-8392-c1cb9bb4176c.PNG">







TASK8:



Sa se creeze o functie definita de utilizator, care ar returna datele referitoare la reusita unui student. 
Se defineste urmatorul format al functiei : < nume_functie > (<Nume_Prenume_Student>).
Sa fie afisat tabelul cu urmatoarele campuri: Nume_Prenume_Student, Disticplina, Nota, Data_Evaluare.




<img width="625" alt="9 task 8" src="https://user-images.githubusercontent.com/43130876/50060331-70e6f200-0147-11e9-9d1a-a42242a1c4ec.PNG">

<img width="433" alt="9 t 8" src="https://user-images.githubusercontent.com/43130876/50060335-79d7c380-0147-11e9-8472-b6ec970242cd.PNG">





TASK9:

Se cere realizarea unei functii definite de utilizator, care ar gasi cel mai sarguincios sau cel mai slab
student dintr-o grupa. Se defineste urmatorul format al functiei: <nume_functie> (<Cod_Grupa>, <is_good>).
Parametrul <is_good> poate accepta valorile "sarguincios" sau "slab", respectiv. Functia sa returneze un 
tabel cu urmatoarele campuri Grupa,Nume_Prenume_Student, Nota Medie , is_good.
Nota Medie sa fie cu precizie de 2 zecimale.




<img width="730" alt="9 t 9" src="https://user-images.githubusercontent.com/43130876/50060360-c7ecc700-0147-11e9-9ef7-efee8a3d41e7.PNG">

<img width="357" alt="9 t 9 --2" src="https://user-images.githubusercontent.com/43130876/50060369-d76c1000-0147-11e9-8654-526b40d2e0db.PNG">





