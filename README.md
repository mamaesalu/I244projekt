# Projekt aines I244 - Ülesannete haldamise rakendus ehk "Ülesannete kodu"

Rakenduses saab pidada arvestust ühe pere ülesannete üle.

Projekti kirjutamise jooksvad commitid on leitavad minu [I244 repost](https://github.com/mamaesalu/I244) kaustast projekt.

## Olemas
Vastavalt õigustele saab kas kõigi kasutajate või ainult enda ülesandeid lisada, muuta ja kustutada.
Admin ehk lapsevanem näeb ja saab lisada ning muuta või kustutada kõikide kasutajate üleandeid. Tavakasutajad ehk lapsed näevad ja saavad muuta ning lisada või kustutada ainult iseenda ülesandeid.

##### Tuleb edaspidi ehk mis lisaks võiks olla 
Lisaks kustutamisele võimalus ülesandeid täidetuks märkida, nii et nendest tekiks tehtud ülesannete arhiiv.

Õppetund sellest projektist siis see, et input type "date" ei ole päris asjades kasutatav.
Algajale jõudis see kohale liiga hilja, mistõttu jäi edaspidiseks ülesandeks täitmise tähtaeg ehk kuupäev paremas formaadis, kasutades nt jquery datepickerit või AJAXit.
Olenevalt lehitsejast (IE11 ja vanemad lehitsejad ning Firefox) võib praegune lahendus mitte toimida või olla lihtsalt kole.

## Tabelid andmebaasis
#### Users
id, usern, passw, role
#### Tasks
id, user_id, task, deadline

## Retsenseerimiseks/testimiseks:
admin/admin (roll admin), user1/user1 (roll user)
Soovitavalt lehitseja (nt Chrome), millel on input type date tugi.


This work is licenced under [Creative Commons Non-Commercial 4.0] (https://creativecommons.org/licenses/by-nc/4.0/)

