# JMBAG
0036492785

#Pitanje 1
Nakon što smo dodali library kao referencu u bin\ Debug folderu se stvorio ClassLibrary1.dll i ClassLibrary1.pdb
Nakon što maknemo .dll i probamo pokrenuti program javi se System.IO.FileNotFoundException
Zato što nema reference na klasu koju .exe koristi
Datoteke koje bi poslao za uporabljivu aplikaciju su .exe i .dll datoteke

#Pitanje 2
Ako izmjenim MyConsole.PrintHelloWorld() i bez prevođenja pokrenem program ispisat će mi stari string.
Zato što računalo nije prevelo promjenu

#Pittanje 3
Ispisao je Pero: Hello World

#Pitanje 4
U bin \Debug folderu konzolne aplikacije se strovio PeroClassLibrary.dll

#Pitanje 5
Ako obrišemo orginalni .dll aplikacija idalje radi
Sada .dll traži u KonzolnaAplikacija\bin\Debug\PeroClassLibrary.dll

#Pitanje 6
Pri buildanju output javi "Restoring NuGet packages...", a u packages direktorij je ponovo dodan NodaTime
