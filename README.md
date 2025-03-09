# TLU_ReactNative
TLÜ Mobiilirakenduste arendamise tunnis rakenduse loomine, kasutades React Native 0.77 ja TypeScripti.


React Native projekti seadistamise juhend
1. Nõuded enne alustamist

Veendu, et sul on installitud järgmised tööriistad:

    Node.js
    Git 
    VS Code (või mõni muu koodiredaktor) 
    Android Studio (kui soovid kasutada emulaatorit)

2. Projekti kloonimine

    Ava terminal (Command Prompt, PowerShell või VS Code terminal) ja klooni projekt oma arvutisse:
    
        git clone [SIIN_PROJEKTI_GITHUBI_LINK]
        cd [PROJEKTI_KAUSTA_NIMI]

3. Vajalike sõltuvuste installimine

    Paigalda projekti jaoks vajalikud paketid, käivitades järgmise käsu:

        npm install


4. Rakenduse käivitamine füüsilises seadmes

    Laadi oma telefoni Expo Go rakendus (Android/iOS).

    Ühenda telefon ja arvuti sama WiFi-võrku.

    Käivita rakendus terminalis:

        npm start

    või

        expo start

    Ilmub QR-kood – skaneeri see Expo Go rakendusega.

5. Rakenduse käivitamine emulaatoris

    Kui soovid testida rakendust emulaatoris, veendu, et sul on:

    Android Studio paigaldatud
    Virtuaalne Android seade loodud (Device Managerist)

    Seejärel käivita terminalis:

        npm run android
