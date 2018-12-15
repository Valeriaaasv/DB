



Nr de ordine:
20.Afisati numarul de studenti care au sustinut testul (Testul 2) la disciplina Baze de date in 2018.



select count(Id_Student)
from studenti_reusita
where Tip_Evaluare = 'Testul 2' and Id_Disciplina = 107 and Data_Evaluare like '%2018%'


<img width="126" alt="lab 4 ex 1 it 20" src="https://user-images.githubusercontent.com/43130876/50044262-d5b22780-0035-11e9-8f1b-f49e752d1a9d.PNG">



Nr de ordine +16:
36.Gasiti denumirile disciplinelor  si media notelor pe disciplina. Afisati numai disciplinele cu medii mai mari de 7.0.

select d.Disciplina,AVG(cast(sr.Nota as float)) as Media
from studenti_reusita sr
inner join discipline d on sr.Id_Disciplina = d.Id_Disciplina
group by d.Disciplina
having AVG(cast(sr.Nota as float)) > 7
order by Media

<img width="252" alt="lab 4 36" src="https://user-images.githubusercontent.com/43130876/50044391-a43a5b80-0037-11e9-9b8d-5e447c42c3e8.PNG">


Random 28-39:
32. Furnizati numele, prenumele si media notelor pe grupe pentru studenti.


select s.Nume_Student,s.Prenume_Student,g.Cod_Grupa,avg(cast(Nota as float)) as Media
from studenti_reusita sr
inner join studenti s on sr.Id_Student = s.Id_Student
inner join grupe g on sr.Id_Grupa = g.Id_Grupa
group by s.Nume_Student,s.Prenume_Student,g.Cod_Grupa
order by g.Cod_Grupa

<img width="248" alt="lab 4 int 32" src="https://user-images.githubusercontent.com/43130876/50044538-cd5beb80-0039-11e9-9ad8-6f9d79f5e454.PNG">


