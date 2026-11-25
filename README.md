# Barem10 · Exàmens del temari general

**Barem10** és una aplicació web progressiva (**PWA**) en català pensada per estudiar i practicar tests d’exàmens del temari general procedents de convocatòries d’administracions públiques. Funciona tant a l’ordinador com al mòbil —fins i tot **sense connexió a internet**— i guarda tot el teu progrés localment, sense comptes ni registres.

👉 **Accedeix a l’aplicació:** [https://xguaita.github.io/barem10/](https://xguaita.github.io/barem10/)

---

## Què inclou l’aplicació

* **Inici i modes intel·ligents de repàs**:
  * Panell de cobertura de preguntes, percentatge d’encert, preguntes fallades pendents i dubtes marcats.
  * Auto-desat de sessions a mitges per poder reprendre qualsevol test exactament on l’havies deixat.
  * 6 accessos directes en un clic: **Repassar fallades**, **Preguntes no vistes**, **Més repetides en convocatòries**, **Temes més fluixos**, **Preguntes marcades** i **Test ràpid de 20**.
* **Pràctica personalitzada**:
  * Filtres combinables per blocs del temari, **organisme**, **subgrup** (`A1`, `A2`, `B`, etc.), **any**, estat de repàs (*no vistes*, *fallades*, *marcades*, *encertades*) i preguntes repetides en diverses convocatòries.
  * Correcció immediata en respondre cada pregunta o correcció al final del test.
  * Barrejament intel·ligent de les opcions (`a`, `b`, `c`, `d`) que respecta automàticament les preguntes no barrejables (com ara *«Totes les anteriors»* o *«a) i b) són correctes»*).
* **Simulacres i exàmens de convocatòries**:
  * **Simulacre aleatori** amb temporitzador, opcions ràpides per subgrup (`A1` 100 preg., `A2` 90 preg., `B` 80 preg., mini-simulacre de 50 preg.) i ponderació proporcional al pes real de cada tema.
  * **Exàmens complets de cada convocatòria** amb opció d’incloure les preguntes de reserva al final, marcar preguntes *Per revisar* i deixar respostes en blanc.
  * **Baremació fixa**: cada encert suma `+1` punt, cada **4 errors resten 1 encert (`−0,25` per error)** i les respostes en blanc no penalitzen, amb càlcul transparent de puntuació neta i nota sobre 10.
* **Estadístiques i historial**:
  * Rendiment detallat per tema (ordenat pels blocs més fluixos primer) amb botons directes per practicar un tema concret o repassar-ne només els errors.
  * Historial complet de sessions i simulacres per revisar qualsevol prova passada pregunta a pregunta.
* **Cercador de preguntes**:
  * Cerca instantània (insensible a accents) per paraula clau, llei, article, tema, organisme, subgrup o convocatòria, amb opció d’amagar/mostrar les respostes i convertir els resultats directament en un test de pràctica.

---

## Origen de les preguntes

La base de preguntes de **Barem10** prové exclusivament dels **qüestionaris i plantilles de correcció publicats en les distintes convocatòries** d’administracions públiques (actualment del Consell de Mallorca i l’IMAS).

Les preguntes s’han normalitzat en català, deduplicat (conservant el detall de totes les convocatòries on ha aparegut cada pregunta) i classificat per blocs del temari general. Quan s’ha detectat alguna possible errata o discrepància entre plantilles publicades, s’indica amb una **nota de revisió** visible a la pregunta.

> *Barem10 és una eina d’estudi independent sense vinculació amb cap administració pública.*

---

## Com instal·lar-la al mòbil (PWA)

Un cop oberta l’adreça web (**HTTPS**) de **Barem10**, la pots instal·lar com una aplicació més al mòbil i fer tests fins i tot en mode avió:

* **Android (Chrome, Edge o Brave)**:
  1. Obre la web de **Barem10** al navegador.
  2. Prem l’avís inferior **«Afegir Barem10 a la pantalla d’inici»** o obre el menú `⋮` → **«Instal·lar l’aplicació»** / **«Afegir a la pantalla d’inici»**.
  3. Apareixerà amb la seva icona pròpia i s’obrirà a pantalla completa.
* **iPhone i iPad (Safari)**:
  1. Obre la web de **Barem10** amb **Safari** (a iOS la instal·lació s’ha de fer des de Safari).
  2. Prem el botó **Compartir** (quadrat amb fletxa cap amunt).
  3. Tria **«Afegir a la pantalla d’inici»** i confirma.

Si s’afegeixen noves convocatòries a la web, l’aplicació s’actualitzarà automàticament en obrir-la amb connexió, **mantenint intacte tot el teu historial**.

---

## Com guardar i sincronitzar el progrés entre dispositius

**Barem10** desa totes les teves estadístiques, preguntes fallades, dubtes marcats i historial de simulacres directament al navegador (**IndexedDB**). No necessita cap compte ni envia les teves dades a cap servidor extern.

Si estudies des de més d’un dispositiu (per exemple, ordinador i mòbil) o vols fer una còpia de seguretat abans de canviar de telèfon:

1. Entra a l’apartat **Estadístiques** i baixa fins a **Còpia de seguretat i portabilitat (JSON)**.
2. Prem **Exportar progrés (JSON)** per descarregar el fitxer `barem10-backup-AAAA-MM-DD.json`.
3. Envia’t aquest fitxer a l’altre dispositiu (correu, Drive, AirDrop, Telegram/WhatsApp, etc.).
4. A l’altre dispositiu, entra a **Estadístiques → Importar còpia (JSON)**, selecciona el fitxer i tria:
   * **Combinar amb les dades actuals** (recomanat per sincronitzar dispositius sense perdre els tests recents de cap dels dos).
   * **Substituir-ho tot** (per restaurar una còpia exacta en un dispositiu nou).

---

## Avís i condicions d’ús

**Barem10** és una eina personal i gratuïta creada amb l’únic propòsit d’ajudar(-me) a preparar oposicions del temari general, sense vinculació amb cap administració pública.

* **S’ofereix tal com és (*as is*)**: sense cap garantia expressa ni implícita sobre el seu funcionament, disponibilitat contínua o absència d’errates de transcripció.
* **Sense compromís d’actualització ni ampliació**: la base de preguntes es pot ampliar puntualment, però no hi ha cap garantia ni obligació d’incorporar noves convocatòries, noves administracions ni futures millores.
* **Vigència normativa**: les preguntes i respostes corresponen al text publicat en la data de cada convocatòria. Com que la legislació evoluciona, és responsabilitat de qui estudia contrastar-les sempre amb la normativa vigent (BOE / BOIB).
* **Progrés local**: l’historial es desa exclusivament al navegador de cada usuari; convé exportar periòdicament una còpia de seguretat en JSON per evitar pèrdues de dades.
