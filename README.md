1) Node Js (https://nodejs.org/en/download -> Prebuilt installer -> LTS verzió) -> 20.18.0-ás verzió

VS Code-ban terminálba: node --version

2) NPM 10.0-ás legyen (elvileg Node JS-el feltelepül) -> 
npm install -g npm@10.0.0

C:\Users\Admin\AppData\Roaming\npm -> check, hogy létezik-e

3) React telepítés (mappába!)
Hozz létre egy munkamappát! Nem lehet a mappa nevében:
- Nagybetű
- Ékezet
- Szóköz
- Nem kezdődhet úgy, hogy "react"

Mappa termináljába: npx create-react-app .

(kell a pont, ha az adott mappában vagy, máskülönben az új mappa neve kell!)

4) Bootstrap telepítés terminálba:
npm install bootstrap

index.js-be:
import 'bootstrap/dist/css/bootstrap.css';

5) Router telepítés
npm install react-router-dom

6) React indítása
npm start

7) React leállítása
node-ba: Ctrl + C


Scaffold-DbContext "server=localhost;database=**********;user=root;password=password;sslmode=none;" mysql.entityframeworkcore -outputdir Models –f
