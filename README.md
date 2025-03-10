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

    Ilmub QR-kood – skaneeri see Expo Go rakendusega.

5. Rakenduse käivitamine emulaatoris

    Kui soovid testida rakendust emulaatoris, veendu, et sul on:

    Android Studio paigaldatud
    Virtuaalne Android seade loodud (Device Managerist)

    Seejärel käivita terminalis:

        npm run android


### **Projekti loomine ja seadistamine**

- Esmalt lõin **GitHubis uue repositooriumi**, kuhu kogu projektikood salvestada. Seejärel uurisin, kuidas luua uus React Native projekt, ning leidsin ametliku juhendi:
    
    https://reactnative.dev/docs/0.77/environment-setup
    
- **Kloonisin** loodud repositooriumi oma arvutisse.
- **Lõin React Native projekti** kasutades VS Code'i.
- **Paigaldasin Android Studio** ja seadistasin sinna virtuaalse Android-seadme.

### **Rakenduse testimine seadmetes**

- Kui projekt oli loodud, katsetasin selle töötamist erinevates keskkondades:
- **Füüsilises seadmes:** Kasutasin **Expo Go** rakendust, et rakendus oma telefonis käivitada.
- **Emulaatoris:** Käivitasin rakenduse **Android Studio** emulaatoris ja veendusin, et see töötab ka seal.

Mis oli kerge?

- Olen varem sarnast projekti seadistanud, seega ei olnud React Native projekti tööle saamine ega GitHubi lisamine eriti keeruline. Samuti ei valmistanud raskusi Android Studio installimine ja füüsilise seadme ühendamine. Küll aga võttis kogu protsess aega.

Mis oli raske?
* Debuggeri tööle saamine oli keeruline.
