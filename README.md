# informacni_system_znamky
**Základní popis systému **
Cíl: 
  Spravovat údaje o studentech, jejich předmětech a známkách. 
Uživatelé systému: 
  administrátor (učitel, který zadává a upravuje data) 
  volitelně student (může vidět své známky, ale nemění data) 
Co systém eviduje 
  Studenti 
    ID studenta 
    Jméno, příjmení 
    Datum narození 
    Třída nebo skupina 
  Předměty 
    ID předmětu 
    Název předmětu (např. Matematika, Informatika) 
    Učitel 
  Známky 
    ID známky 
    Student (odkaz na tabulku Student) 
    Předmět (odkaz na tabulku Předmět) 
    Známka (např. 1–5 nebo A–F) 
    Datum 
