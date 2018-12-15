--EX1

--Completati urmatorul cod pentru a afisa cel mai mare numar dintre cele trei numere prezentate:


declare @N1 int , @N2 int, @N3 int;

declare @MAI_MARE int;

set @N1 = 60 * rand();

set @N2 = 60 * rand();

set @N3 = 60 * rand();

set @MAI_MARE = @N1;

if @MAI_MARE < @N2

   set @MAI_MARE = @N2;

if @MAI_MARE < @N3

   set @MAI_MARE = @N3;



print @N1;

print @N2;

print @N3;

print 'Mai mare = ' + cast(@MAI_MARE as varchar(2));




<img width="148" alt="lab 5 ex 1 executat" src="https://user-images.githubusercontent.com/43130876/50044600-c386b800-003a-11e9-9c22-2fc1931ace29.PNG">


--EX2

--Afisati primele zece date(numele, prenumele studentului) in functie de valoarea notei (cu exceptia notelor 6 si 8) 
--a studentului la primul test al disciplinei Baze de date, folosind structura de altemativa IF. .. ELSE. Sa se foloseasca variabilele


declare @Nume_Disciplina varchar(20) = 'Baze de date';

declare @Tipul_Testului varchar(20) = 'Testul 1';

declare @Nota1 int = 6;

declare @Nota2 int = 8;



if @Nota1 !=any (select  top (10) Nota

from studenti, studenti_reusita, discipline

where studenti.Id_Student = studenti_reusita.Id_Student

and discipline.Id_Disciplina = studenti_reusita.Id_Disciplina

and Disciplina = @Nume_Disciplina

and Tip_Evaluare = @Tipul_Testului)



and @Nota2 != any (select  top (10) Nota

from studenti, studenti_reusita, discipline

where studenti.Id_Student = studenti_reusita.Id_Student

and discipline.Id_Disciplina = studenti_reusita.Id_Disciplina

and Disciplina = @Nume_Disciplina

and Tip_Evaluare = @Tipul_Testului)



begin



select  top (10) Nume_Student, Prenume_Student, Nota

from studenti, studenti_reusita, discipline

where discipline.Id_Disciplina = studenti_reusita.Id_Disciplina

and studenti.Id_Student = studenti_reusita.Id_Student

and Disciplina = @Nume_Disciplina

and Tip_Evaluare = @Tipul_Testului

and Nota not in (@Nota1, @Nota2)



end


<img width="193" alt="lab 5 ex 2 executat" src="https://user-images.githubusercontent.com/43130876/50044627-152f4280-003b-11e9-885f-370b906e9c92.PNG">







