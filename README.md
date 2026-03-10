================================================================================
  ______          _______             _    
 |  ____|        |__   __|           | |   
 | |__   ___ ___    | |_ __ __ _  ___| | __
 |  __| / __/ _ \   | | '__/ _` |/ __| |/ /
 | |___| (_| (_) |  | | | | (_| | (__|   < 
 |______\___\___/   |_|_|  \__,_|\___|_|\_\
                                           
================================================================================

PROJEKT ÁTTEKINTÉS
------------------
Az EcoTrack egy modern, reszponzív, böngészőből elérhető alkalmazás, amely segít nyomon követni 
és csökkenteni az ökológiai lábnyomodat. Interaktív grafikonok, játékos elemek (pontok, kihívások, 
sorozatok) és közösségi funkciók (barátok, chat) motiválnak a környezettudatosabb mindennapokra.

KÉSZÍTŐK
--------
* Vass Attila
* Mózes Dominik
* Varjas Vince

FŐBB FUNKCIÓK
-------------
* **Szén-dioxid Kalkulátor:** Napi rendszerességgel rögzítheted a közlekedési (jármű, távolság), étkezési és digitális szokásaidat. Plusz pontokat kaphatsz környezetbarát extrákért (pl. húsmentes nap, saját kulacs).
* **Pontozási és Sorozat Rendszer:** Az adataid alapján naponta 0-100 pontot szerezhetsz. Az alkalmazás motivál, hogy fenntartsd a napi kitöltési "sorozatodat" (streak).
* **Vizuális Visszajelzés:** * Dinamikus "növény" animációk az űrlapon.
    * Változó magasságú vízszint.
    * Növekvő "erdő" oszlopdiagram, amely összehasonlítja a pontszámodat a barátaidéval és a globális átlaggal.
    * Fánk (donut) diagram a lábnyomod összetételéről.
* **Kihívások és Kitűzők:** Teljesíts heti kihívásokat (pl. bringázás, környezetbarát étkezés) extra pontokért. Szerezz egyedi kitűzőket a profilodra a kitartásodért.
* **Közösség (Barátok és Chat):** * Keress és vegyél fel barátokat felhasználónév vagy e-mail cím alapján.
    * Valós idejű ranglista a barátaid között.
    * Beépített chat felület a barátokkal való kapcsolattartásra.
* **Naptár és Statisztika:** Kövesd nyomon a korábbi kitöltéseidet egy áttekinthető naptárban.
* **Testreszabás:** Sötét mód, profilkép feltöltés, értesítések beállítása.
* **Adatbiztonság:** Felhasználói fiókok kezelése Firebase Authentication segítségével, az adatok biztonságos tárolása a Firebase Firestore-ban.

HASZNÁLATI ÚTMUTATÓ
-------------------
1.  **Regisztráció/Bejelentkezés:** Első használatkor regisztrálj egy fiókot (e-mail, jelszó és egyedi felhasználónév megadásával). Később ugyanezekkel az adatokkal jelentkezhetsz be.
2.  **Napi Kalkulátor:** Töltsd ki a kalkulátort a napi tevékenységeiddel (közlekedés, étkezés, digitális lábnyom, extrák), és kattints a "Számítás" gombra. Ezt naponta egyszer teheted meg.
3.  **Eredmények:** Nézd meg az eredményeidet a grafikonokon, és ellenőrizd a helyezésedet a ranglistán.
4.  **Közösség:** Használd a "Barátok hozzáadása" gombot, hogy másokat is meghívj. A csengettyű ikon jelzi, ha új meghívód vagy üzeneted érkezett.
5.  **Profil:** A jobb felső sarokban lévő fogaskerék (Beállítások) ikonra kattintva módosíthatod a nevedet, tölthetsz fel profilképet, válthatsz sötét/világos módot, vagy engedélyezheted az emlékeztető értesítéseket.

TECHNOLÓGIAI HÁTTÉR
-------------------
* **Frontend:** HTML5, CSS3 (Tailwind CSS a reszponzív dizájnhoz, egyedi animációk), Vanilla JavaScript.
* **Backend / Adatbázis:** Firebase (Authentication a bejelentkezéshez, Firestore NoSQL adatbázis a valós idejű szinkronizációhoz és adattároláshoz).
* **Grafikonok:** Chart.js (datalabels pluginnal).
* **Ikonok:** Lucide Icons.
* **Animációk:** CSS kulcskockák (keyframes) és GSAP.

--------------------------------------------------------------------------------
EcoTrack - A zöldebb jövőért
================================================================================
