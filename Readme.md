Scopul acestei lucrări de laborator este de a rezolva următoarea problemă: un pescar trebuie să aleagă dintr-un set de homari pe aceia care au suma valorii lor maximă, dar cu suma dimensiunilor mai mică decât capacitatea plasei sale. Problema diferă de clasică problemă a rucsacului prin faptul că homarii ales,i trebuie enumerat,i.
În mod specific, se consideră că pescarul dispune de o plasă cu o capacitate maximă dată. El are la dispozit,ie un număr nedeterminat de homari, fiecare având asociate trei caracteristici esent,iale: nume, dimensiune s,i valoare. Programul trebuie să primească ca date de intrare capacitatea maximă a plasei s,i informat,ii detaliate despre fiecare homar în parte. Obiectivul este de a determina combinat,ia optimă de homari care să maximizeze valoarea totală, respectând în acelas,i timp constrângerea de capacitate a plasei. Formularea problemei poate fi prezentată matematic astfel:
•	Date de intrare:
–	C - capacitatea maximă a plasei (o constantă pozitivă).
–	n - numărul de homari disponibili.
–	Pentru fiecare homar i (i = 1,2,...,n):
∗ numei - numele homarului i (un s,ir de caractere).
∗ dimensiunei - dimensiunea homarului i (un număr real pozitiv).
∗ valoarei - valoarea homarului i (un număr real pozitiv).
•	Date de ies,ire:
–	Un subset de homari selectat,i astfel încât:
∗ Suma dimensiunilor homarilor selectat,i să fie mai mică sau egală cu C.
∗ Suma valorilor homarilor selectat,i să fie maximă. ∗ Homarii selectat,i să fie enumerat,i.
Astfel, problema se încadrează în clasa problemelor de optimizare combinatorie, fiind o variat,ie a problemei rucsacului, dar cu o cerint,ă suplimentară de a enumera homarii selectat,i. Implementarea unui algoritm eficient pentru această problemă va trebui să t,ină cont de complexitatea combinatorie, asigurânduse totodată că solut,ia obt,inută este optimală în raport cu constrângerile date.
