# alkfejl-beadando

FELADAT
- Eladó autókat kezelő alkalmazás
	
KÖVETELMÉNYEK
- Funkcionális követelmények
	- Vendégként szeretnék a hirdetések között szabadon böngészni.
	- Vendégként szeretnék egy autó leírását megtekinteni.
	- Vendégként szeretnék eladó autót keresni.
	- Vendégként szeretnék tudni regisztrálni az oldalra.
	- Felhasználóként szeretnék tudni bejelentkezni az oldalra.
	- Felhasználóként szeretném tudni a profiladataimat szerkeszteni.
	- Felhasználóként szeretnék új hirdetést feladni.
	- Felhasználóként szeretném a saját hirdetéseimet módosítani vagy törölni.
	- Felhasználóként Like-olhatom a hirdetéseket.
- Nem funkcionális követelmények
	- Felhasználóbarát, ergonomikus elrendezés és kinézet.
	- Gyors működés.
	- Biztonságos működés: jelszavak tárolása, funkciókhoz való hozzáférés.
		
SZAKTERÜLETI FOGALOMJEGYZÉK
- Személygépkocsi: Személygépkocsinak minősül az a 2500 kg-ot meg nem haladó, olyan gépjármű, amely gyárilag kialakítva kettőnél több, de maximum 9 utas szállítására alkalmas.
- Tehergépkocsi: A személygépkocsit, az autóbuszt, a trolibuszt és a vontatót kivéve minden tehergépkocsi.
- Hibrid: Egynél többféle üzemanyaggal működő gépkocsi.
		
SZEREPKÖRÖK
- Vendég: Autók keresését, böngészését és megtekintését végezheti.
- Felhasználó: A vendég szerepkörén túl a saját hirdetéseinek kezelésére (új, módosít, törlés) képes.
		
HASZNÁLATI ESETEK
![Alt text](/bead1_images/uml.png?raw=true "HASZNALATIESETEK.png")

FOLYAMATOK MEGHATÁROZÁSA
- felhasználó
	- Új hirdetés felvételének folyamata
	- Bejelentkezés folyamata
- vendég
	- Keresés egy autóra
	- Regisztráció
		
OLDALTÉRKÉP
- Publikus:
	- Főoldal
	- Autók böngészése
		+ Autó megtekintése
	- Belépés
	- Regisztráció
- Felhasználó
	- Kilépés
	- Profiladatok
		+ Profiladatok szerkesztése
	- Új hirdetés felvitele
	- Egy hirdetés megtekintésénél Like
		
VÉGPONTOK
- GET /: főoldal
- GET /login: bejelentkező oldal
- POST /login: bejelentkezési adatok felküldése
- GET /profil: profiladatok
- GET /ads: hirdetések listája
- GET /ads/:id: hirdetés megtekintése
- POST /ads/:id: hirdetés like-olása
- GET /ads/create: új hirdetés felvitele, űrlap megjelenítése
- POST /ads/create: új hirdetés felvitele, adatok küldése

OLDALVÁZLATOK
![Alt text](/bead1_images/uml.jpg?raw=true "OLDALVAZLATOK_1.jpg")
![Alt text](/bead1_images/uml.jpg?raw=true "OLDALVAZLATOK_2.jpg")
![Alt text](/bead1_images/uml.jpg?raw=true "OLDALVAZLATOK_3.jpg")
![Alt text](/bead1_images/uml.jpg?raw=true "OLDALVAZLATOK_4.jpg")
![Alt text](/bead1_images/uml.jpg?raw=true "OLDALVAZLATOK_5.jpg")
![Alt text](/bead1_images/uml.jpg?raw=true "OLDALVAZLATOK_6.jpg")
![Alt text](/bead1_images/uml.jpg?raw=true "OLDALVAZLATOK_7.jpg")

ADATMODELL
![Alt text](/bead1_images/uml.png?raw=true "ADATMODELL.png")

Szerkesztette: Viczián Lilla
