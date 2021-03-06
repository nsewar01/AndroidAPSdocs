
Eksporto & importo parametrai
**************************************************
Kada turėčiau eksportuoti parametrus?
==================================================
Būkite pasirengę nenumatytiems atvejams. Galite netyčia pakeisti svarbius parametrus ir jums bus sunku anuliuoti pakeitimus. Jūsų išmanusis telefonas gali būti sugadintas arba pavogtas. Kad galėtumėte tiesiog grįžti į nustatymų statusą, kuriame buvote, nustatymus reikia reguliariai eksportuoti.

Rekomenduojama eksportuoti nustatymus atlikus pakeitimus ar įvykdžius tikslą. 

Eksportuoti nustatymai turėtų būti nukopijuoti į saugyklą debesyje arba į jūsų kompiuterį. Tuomet esate pasirengęs tam atvejui, jei prarasite ar sugadinsite savo AAPS išmanųjį telefoną ir nereikės pradėti nuo nulio.

Windows 10 kompiuteryje tai atrodo maždaug taip:
  
  .. nuotrauka:: ../images/SmartphoneRootLevelWin10.png
    :alt: AndroidAPS nuostatų failas - išmanusis telefonas prijungtas prie kompiuterio

Eksportuojama informacija
==================================================
Be kita ko, eksportuojami šie parametrai:

* `Automatizavimo įvykiai <../Usage/Automation.html>`_
* `Konfigūratoriaus <../Configuration/Config-Builder.html>`_ parametrai
* 'Vietinio profilio <../Configuration/Config-Builder.html#local-profile-recommended>`_ parametrai
* Tikslų <../Usage/Objectives.html>`_ statusas, įskaitant egzaminų rezultatus <../Usage/Objectives.html#objective-3-proof-your-knowledge>`_
* `Nustatymai <../Configuration/Preferences.html>`_, įskaitant 'NS Kliento nustatymus <../Configuration/Preferences.html#ns-client>`_




Kaip eksportuoti parametrus
==================================================
* **Eksportuoti nustatymus** senajame telefone

  * Paspauskite trijų linijų meniu (viršutiniame kairiajame kampe)
  * Servisas
  * Eksportuoti nustatymus
  * Parodoma failo saugojimo vieta
    
.. nuotrauka:: ../images/AAPS_ExportSettings.png
  :alt: AndroidAPS eksportavimo parametrai
       
* **Perkelkite** eksportuotus nustatymus iš seno išmaniojo telefono

  Eksportuotas failas vadinamas „AndroidAPSPreferences“ ir turėtų būti rastas šakniniame aplanke pagrindiniame savo išmaniojo telefono lygyje (panašiai kaip C: jūsų kompiuteryje).
  
* **Instaliuokite** AndroidAPS naujajame telefone.
* **Importuokite nustatymus** naujajame telefone

  * Paspauskite trijų linijų meniu (viršutiniame kairiajame kampe)
  * Servisas
  * Importuokite nustatymus

* **Pastaba Dana RS vartotojams:**

  * Kadangi pompos susiejimo nustatymai persikelia į naują telefoną kartu su kitais, Jūsų naujas telefonas jau "pažįsta" pompą, todėl nepradės BT paieškos. Rankiniu būdu Bluetooth ryšiu suporuokite išmanųjį telefoną ir pompą.
