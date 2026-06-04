# Tehnici Web - Proiect

## Tema proiectului
Tema aleasa este **Nexus Components**, un magazin online de piese de calculator axat exclusiv pe vanzarea de componente PC: procesoare, placi video, placi de baza, memorii RAM, SSD-uri, surse, carcase si accesorii pentru upgrade. Site-ul nu include servicii de reparatii. Accentul este pus pe organizarea clara a informatiei, pe compatibilitate si pe ghidarea rapida a utilizatorului catre produsele potrivite.

## Etapa 0

### 1. Alegerea temei
Titlul site-ului este **Nexus Components**. Tema este un magazin de piese de calculator, asemanator cu PC Garage, eMAG sau Micro Center, dar concentrat strict pe componenta de magazin online pentru hardware PC.

### 2. Categorii si subcategorii
- Procesoare: AMD Ryzen, Intel Core, coolere compatibile
- Placi video: entry-level, gaming 1080p, gaming 1440p, creator/workstation
- Placi de baza: AM5, LGA1700, microATX, ATX, DDR4, DDR5
- Memorie si stocare: memorii RAM DDR4/DDR5, SSD NVMe, SSD SATA, HDD
- Alimentare si carcase: surse modulare, surse ATX 3.0, carcase airflow, carcase compacte
- Periferice si accesorii: ventilatoare, pasta termica, suporturi GPU, kit-uri de cable management

### 3. Pagini identificate si legaturi dintre ele
Au fost identificate 5 pagini principale:
- `index.html` / Acasa: prezentare magazin, promotii, evenimente, recomandari rapide, FAQ
- `catalog.html`: categorii de produse, filtre, produse populare, stocuri
- `configuratii.html`: pachete recomandate pentru office, gaming si creator
- `ghiduri.html`: explicatii despre compatibilitate, wattaj, airflow, upgrade
- `contact.html`: date de contact, program, livrare, retur

Pe pagina principala raman doar informatiile introductive, evenimentele, elementele de promovare si intrebarile frecvente. Detaliile extinse despre produse, comparatii si filtre merg in pagini separate.

### 4. Cuvinte cheie
- Cuvinte cheie generale ale site-ului: magazin piese calculator, componente PC, placi video, procesoare, SSD, memorie RAM, surse PC, carcase PC, upgrade PC, configuratii gaming
- Pagina Acasa: magazin piese calculator, componente PC, placi video, procesoare, SSD, upgrade PC
- Pagina Catalog: catalog componente PC, filtre placi video, procesoare gaming, SSD NVMe, memorii RAM
- Pagina Configuratii: configuratii gaming, PC office, PC creator, compatibilitate componente, wattaj sursa
- Pagina Ghiduri: ghid alegere componente, compatibilitate socket, airflow carcasa, upgrade PC
- Pagina Contact: livrare componente PC, suport comenzi, program magazin, retur produse IT

### 5. Site-uri similare analizate

#### PC Garage
Link: https://www.pcgarage.ro/

Pro:
- Are categorii usor de scanat pentru componente importante precum procesoare, placi video si SSD-uri
- Evidentiaza bine promotiile si produsele vedeta

Contra:
- Homepage-ul este foarte aglomerat vizual
- Bannerele si promotiile pot ascunde informatia utila

Idei de implementat:
- Evidentierea produselor vedeta
- Oferte pe categorii

#### eMAG - componente PC
Link: https://www.emag.ro/nav/componente-pc

Pro:
- Filtrarea pe criterii comerciale si tehnice este bogata
- Structura este familiara pentru utilizatori

Contra:
- Produsele pot parea amestecate din cauza marketplace-ului
- Pagina poate deveni foarte lunga si obositoare

Idei de implementat:
- Ierarhie clara de categorii
- Evidentierea filtrarii

#### CEL.ro
Link: https://www.cel.ro/

Pro:
- Acopera multe categorii si subcategorii hardware
- Ofera acces rapid spre familii de produse

Contra:
- Designul pare incarcat
- Continutul important nu este mereu prioritizat vizual

Idei de implementat:
- Adancimea buna a categorisirii

#### Micro Center
Link: https://www.microcenter.com/site/products/computer-parts.aspx

Pro:
- Comunica bine zonele de interes pentru builderi: CPU, GPU, motherboard, bundles
- Include instrumente utile pentru alegerea componentelor

Contra:
- O parte din experienta este gandita si pentru magazin fizic
- Unele zone sunt orientate spre servicii auxiliare

Idei de implementat:
- Sectiuni pentru configuratii recomandate
- Pachete/bundles

#### Newegg
Link: https://www.newegg.com/Components/Store

Pro:
- Este foarte bine aliniat cu publicul interesat strict de componente PC
- Separarea pe categorii hardware este intuitiva

Contra:
- Volumul mare de informatii poate intimida incepatorii
- Interfata este mai functionala decat prietenoasa

Idei de implementat:
- Organizarea strict tehnica pe componente

### 6. Directia proprie a proiectului
Site-ul pastreaza o structura simpla, cu 4-5 pagini, meniu clar si homepage aerisit. Sunt preluate idei bune din magazinele analizate, dar fara supraincarcare vizuala. Accentul ramane pe componente PC, compatibilitate si upgrade.

## Etapa 1

### Cum se ruleaza proiectul
Proiectul poate fi rulat local cu **Live Server** din VS Code:
1. Se deschide folderul proiectului in VS Code.
2. Se instaleaza extensia **Live Server**.
3. Se deschide fisierul `index.html`.
4. Se apasa butonul **Go Live**.

Astfel, pagina ruleaza pe un server local, ceea ce este util mai ales pentru cerinta legata de atributul `download`.

### Cerinte rezolvate

#### 1. Folder proiect + `index.html` + doctype + limba documentului
In proiect exista fisierul `index.html`, iar documentul incepe cu `<!DOCTYPE html>` si cu `<html lang="ro">`.

#### 2. `title` si meta-uri
Am adaugat:
- `meta charset`
- `meta author`
- `meta keywords`
- `meta description`
- plus `viewport`, `theme-color` si `msapplication-TileColor`

#### 3. Cuvinte cheie in continut
Toate cuvintele cheie importante pentru pagina principala apar in textul paginii: magazin piese calculator, componente PC, placi video, procesoare, SSD, upgrade PC.

#### 4. Folder `resurse` si favicon
Am creat:
- `resurse/ico`
- `resurse/img`
- `resurse/docs`

In `resurse/ico` exista fisierele de favicon si manifestul necesar. In HTML sunt legate prin tagurile `link` si meta-urile aferente.

#### 5. Impartirea in `header`, `main`, `footer`
Pagina este impartita semantic in:
- `header`
- `main`
- `footer`

#### 6. Taguri de sectionare si imbricare
Am folosit:
- `section`
- `aside`

Exista si sectiuni imbricate in interiorul sectiunii de categorii, cu heading-uri corespunzatoare nivelului de imbricare.

#### 7. `hgroup`
Am folosit `hgroup` pentru titlul principal al sectiunii de prezentare si subtitlul aferent.

#### 8. Navigare in `header`
Am realizat un `nav` cu lista neordonata. Pentru optiunea `Acasa` exista suboptiuni care duc spre sectiuni din aceeasi pagina prin id-uri.

#### 9. Taguri de grupare
Am folosit mai multe taguri de grupare, dintre care cerinta minima era doua:
- `p`
- `blockquote`
- `dl`

#### 10. Sectiune de evenimente cu `time`
Exista o sectiune de evenimente in care fiecare element contine:
- data si ora cu `time`
- atributul `datetime`
- numele evenimentului in `b`
- o descriere scurta

#### 11. Imagine cu `figure`, `figcaption`, `picture`
Am introdus o imagine relevanta pentru tema, cu:
- `figure`
- `figcaption`
- `picture`
- trei variante de imagine pentru ecran mic, mediu si mare
- atributul `title`

Imaginea este inclusa si intr-un link catre varianta mare.

#### 12. Cerinte de text special
Am folosit mai multe taguri dintre cele cerute, peste minimul necesar:
- `b`
- `i`
- `strong`
- `em`
- `s`
- `ins`
- `abbr`
- `dfn`
- `q`
- `cite`

#### 13. Cele 5 tipuri de linkuri
Am inclus toate cele 5:
- link extern care se deschide in tab nou
- link catre un element dintr-o resursa externa cu fragment `#...`
- link in footer catre inceputul paginii
- link care contine o imagine
- link de tip `download` care redenumeste fisierul descarcat

#### 14. `iframe` cu YouTube
Am creat:
- un `div` cu 3 linkuri catre videoclipuri YouTube
- un `iframe` embedded
- linkurile se deschid in acelasi `iframe` prin atributul `target`

#### 15. Tabel
Am realizat un tabel complet cu:
- `caption`
- `thead`
- `tbody`
- `tfoot`
- minimum 5 randuri
- 4 coloane
- `rowspan`
- `colspan`

#### 16. `details` si `summary`
Am adaugat o sectiune de intrebari frecvente realizata cu `details` si `summary`.

#### 17. `meter`
Am folosit doua elemente `meter`:
- unul cu valoare mica, sub pragul `low`
- unul cu valoare mare, peste pragul `high`

Am setat `value`, `min`, `max`, `low`, `high`, `optimum`.

#### 18. `address` si date de contact
In footer exista un `address` care contine:
- telefon fictiv cu `tel:`
- adresa fictiva
- link spre Google Maps
- e-mail fictiv cu `mailto:`
- link spre WhatsApp

#### 19. Copyright
In footer exista:
- tagul `small`
- simbolul `&copy;`
- data in romana, in tagul `time`

#### 20. Validare HTML
Pagina a fost verificata cu validatorul HTML si se valideaza corect.

## Etapa 2

### Cerinte generale implementate
- proiectul este lucrat pe branch-ul `Etapa_2`
- prima pagina a fost refacuta cu layout responsive pe baza de grid
- a fost folosita schema cromatica individuala: `#38378C`, `#498C37`, `#8C5537`, `#282837`, `#E9FFE3`
- stilizarea foloseste variabile CSS, spatiere laterala coerenta, `gap`, `padding` uniform si delimitare vizuala clara a zonelor
- au fost adaugate un font extern prin Google Fonts si iconuri Font Awesome

### Cerinte individuale implementate

#### 1. Schema cromatica
Paleta aleasa este:
- `#38378C`
- `#498C37`
- `#8C5537`
- `#282837`
- `#E9FFE3`

Culorile sunt folosite prin variabile CSS pentru fundaluri, texte, accente, umbre si stari de hover.

#### 2. Layout responsive
Prima pagina foloseste un grid cu 8 zone, conform cerintei individuale:
- zona 1: prezentare / poster introductiv
- zona 2: tabel
- zona 3: calendar de evenimente
- zona 4: anunturi
- zona 5: utilizatori online
- zona 6: date despre utilizator si statistici
- zona 7: date despre site si server
- zona 8: continut suplimentar

Layout-ul se schimba intre:
- ecran mare: 3 coloane
- ecran mediu: 2 coloane
- ecran mic: 1 coloana

#### 3. Design rudimentar
Au fost implementate:
- spatiere laterala cu variabile CSS
- `gap` intre zonele gridului
- `padding` uniform in zonele de continut
- fundaluri diferite pe zone
- border
- colturi rotunjite
- umbre
- dimensiuni responsive pentru imagini, iframe-uri si PDF

#### 4. Font extern si iconuri
Am folosit:
- Google Fonts pentru fonturile principale
- Font Awesome pentru un icon static si unul animat

#### 5. Stilizare tabel
Tabelul este stilizat cu:
- `caption` jos
- alternanta vizuala pe coloane
- hover pe rand
- border collapse
- container cu scroll orizontal pe ecrane mai mici
- `rowspan` si `colspan`

#### 6. Stilizare taburi
Zona de videoclipuri este refacuta ca sistem de taburi cu:
- container separat pentru linkuri si iframe
- butoane stilizate pentru linkuri
- flexbox
- iframe integrat

#### 7. Link top
A fost adaugat un buton fix de revenire sus, cu:
- forma rotunjita in partea de sus
- tooltip
- opacitate redusa in starea initiala
- schimbare de culoare si scalare a sagetii la hover

#### 8. Bonusuri implementate in etapa 2
- reset CSS in fisier separat
- stilizare MathML

### Fisiere relevante pentru etapa 2
- `index.html`
- `resurse/css/reset.css`
- `resurse/css/stil.css`
- `Cerinte_Rezolvate.md`
- `Intrebari.md`

## Bonusuri
In varianta actuala sunt implementate toate bonusurile cerute:
- formula MathML cu sens in contextul alegerii sursei pentru un PC
- PDF afisat in pagina cu tagul `object`
- harta de imagine cu `map` si `area` peste imaginea principala
- iframe Google Maps pentru locatia Facultatii de Matematica si Informatica
- iframe YouTube cu playlist, controale si reluare automata

## Observatii despre imagini
Imaginile curente din `resurse/img` au fost generate local pentru a avea proiectul complet si functional. Pentru varianta finala de predare este in continuare recomandat sa fie inlocuite cu imagini alese manual, relevante pentru tema magazinului de componente PC, apoi redimensionate in trei variante:
- small
- medium
- large

Structura HTML este deja pregatita pentru aceste variante, deci imaginile se pot inlocui fara schimbari mari in cod.
