#JMBAG
0036483688

#Pitanje 1:
stvorena su dva nova fajla, ClassLibrary1.dll i ClassLibrary1.
nakon brisanja nije moguce pokrenuti .exe jer aplikacija ne pronalazi .dll.
potrebno je poslati .exe i .dll.

#Pitanje 2:
prvo se prevodi ClassLibrary i onda ispis bude jednak onome iz ClassLibrary projekta.
ako promijenimo string u ClassLibrary, a konzolnu aplikaciju pokrenemo s .exe prikazat ce se stari string.

#Pitanje 3:
"Pero: Hello World"

#Pitanje 4:
pojavila se PeroClassLibrary.dll

#Pitanje 5:
nakon sto se .dll obrise sa diska aplikaciju je moguce pokrenuti zato sto se kopija .dll-a i dalje nalazi u debug folderu, ali build ne radi.
na references listi se jos uvijek referencira datoteka na disku, a posto je ona obrisana dolazi do greske.

#Pitanje 6:
dok se aplikacija buildala ponovno se skinuo package NodaTime te se pojavio u packages folderu.

