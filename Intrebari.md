# Intrebari si explicatii detaliate

Acest fisier este facut ca suport de invatare. Explicatiile sunt intentionat foarte directe si simple.

## 1. Cum rulez site-ul?
Deschizi proiectul in VS Code si folosesti extensia **Live Server**.

Pasii:
1. Deschizi folderul `Tehnici_web`.
2. Deschizi `index.html`.
3. Apesi `Go Live`.

De ce nu este suficient doar dublu click pe fisier?
- Unele lucruri merg si asa.
- Dar cerinta cu `download` este mai sigura cand fisierul ruleaza printr-un server local.
- Profesorul a mentionat explicit Live Server, deci e bine sa faci exact asa.

## 2. Ce este `<!DOCTYPE html>`?
Este declaratia care spune browserului ca documentul este HTML5.

## 3. Ce face `lang="ro"`?
Spune ca limba documentului este romana.

## 4. Ce este diferenta dintre `title` si `h1`?
`title` apare in tabul browserului, iar `h1` este titlul principal vizibil din pagina.

## 5. Ce fac meta-urile?
- `meta charset` spune codarea paginii
- `meta author` spune autorul
- `meta keywords` contine cuvintele cheie
- `meta description` descrie pe scurt pagina

## 6. De ce trebuie sa pun cuvintele cheie si in text?
Pentru ca profesorul cere coerenta intre meta-uri si continutul real al paginii.

## 7. Ce este diferenta dintre `header`, `main`, `footer`?
- `header` = inceputul paginii
- `main` = continutul principal
- `footer` = finalul paginii

## 8. Ce inseamna HTML semantic?
Inseamna sa folosesti taguri care descriu rolul continutului, nu doar aspectul lui.

## 9. Care este diferenta dintre `section`, `article` si `aside`?
- `section` = sectiune tematica
- `article` = continut independent
- `aside` = continut secundar

## 10. Ce inseamna sectiuni imbricate?
O sectiune aflata in interiorul altei sectiuni. De aceea folosesti `h2`, apoi `h3`.

## 11. Ce este `hgroup`?
Grupeaza titlul unei sectiuni cu subtitlul lui.

## 12. Care este diferenta dintre `b` si `strong`?
- `b` = accent vizual
- `strong` = importanta semantica

## 13. Care este diferenta dintre `i` si `em`?
- `i` = termen tehnic, strain sau idiomatic
- `em` = accent de sens la citire

## 14. Ce fac `s` si `ins`?
- `s` = ceva care nu mai este valabil
- `ins` = text introdus in locul celui vechi

## 15. Ce face `abbr`?
Marcheaza o abreviere si poate afisa forma lunga prin `title`.

## 16. Ce face `dfn`?
Marcheaza termenul care este definit.

## 17. Ce fac `q` si `blockquote`?
- `q` = citat scurt in linie
- `blockquote` = citat sau pasaj separat

## 18. Ce face `cite`?
Marcheaza titlul unei lucrari citate.

## 19. De ce meniul este facut cu `nav` si liste?
Pentru ca acesta este modul semantic corect de a construi navigarea.

## 20. Ce face `id`?
Identifica unic un element si permite linkuri interne de tip `#ceva`.

## 21. Ce este `figure` si `figcaption`?
- `figure` grupeaza o resursa media
- `figcaption` este descrierea ei

## 22. Ce este `picture`?
Permite incarcarea unor imagini diferite in functie de dimensiunea ecranului.

## 23. Imaginile trebuie alese de mine?
Ideal, da. Eu am generat local imagini placeholder ca proiectul sa fie complet, dar pentru predare e mai bine sa le inlocuiesti cu imagini alese de tine.

## 24. Ce face atributul `title` la imagine?
Arata un mic tooltip cand stai cu mouse-ul peste imagine.

## 25. Ce face `time`?
Marcheaza date si ore intr-un format clar pentru oameni si browsere.

## 26. De ce numele evenimentului este in `b`?
Pentru ca cerinta spune explicit ca numele evenimentului trebuie pus in `b`.

## 27. Ce este `iframe`?
Incarca o alta pagina sau resursa in interiorul paginii tale.

## 28. Cum functioneaza linkurile care se deschid in iframe?
Linkurile folosesc `target`, iar iframe-ul are `name` cu aceeasi valoare.

## 29. Ce este `wbr`?
Ii spune browserului unde poate rupe un cuvant sau un URL foarte lung pe rand nou.

## 30. Ce este atributul `download`?
Spune browserului sa descarce resursa si poate propune un alt nume pentru fisier.

## 31. Ce este `table` si de ce are `thead`, `tbody`, `tfoot`?
- `thead` = capul tabelului
- `tbody` = datele principale
- `tfoot` = observatii finale

## 32. Ce sunt `rowspan` si `colspan`?
- `rowspan` face o celula sa ocupe mai multe randuri
- `colspan` face o celula sa ocupe mai multe coloane

## 33. Ce sunt `details` si `summary`?
- `summary` este titlul vizibil
- `details` este continutul care se deschide/inchide

## 34. Ce este `meter`?
Reprezinta o valoare masurata intr-un interval cunoscut.

## 35. Ce fac `low`, `high` si `optimum` la `meter`?
- `low` = prag de valoare mica
- `high` = prag de valoare mare
- `optimum` = valoarea ideala

## 36. Ce este `address`?
Tag semantic pentru date de contact.

## 37. Ce este `tel:`?
Schema de URL pentru numere de telefon.

## 38. Ce este `mailto:`?
Schema de URL pentru e-mail.

## 39. Ce este `wa.me`?
Link simplu pentru deschiderea unui chat WhatsApp.

## 40. Ce face `small`?
Este pentru informatii secundare sau detalii fine, cum este copyright-ul.

## 41. Ce este `&copy;`?
Este entitatea HTML pentru simbolul ©.

## 42. Ce inseamna ca pagina este valida HTML?
Inseamna ca respecta regulile sintactice HTML si trece validatorul.

## 43. Ce bonusuri sunt facute?
Sunt facute toate bonusurile mentionate:
- MathML
- PDF in pagina cu `object`
- image map cu `map` si `area`
- iframe Google Maps
- playlist YouTube in iframe

## 44. Ce este MathML?
MathML este un limbaj pentru scrierea formulelor matematice direct in HTML.

In proiect, formula estimeaza puterea recomandata a sursei:
- consum CPU
- plus consum GPU
- plus restul componentelor
- totul inmultit cu o rezerva de siguranta

## 45. Ce este `object` pentru PDF?
Tagul `object` poate afisa un fisier PDF direct in pagina. Daca browserul nu il poate afisa, apare continutul de rezerva din interiorul tagului.

## 46. Ce este un image map?
Este o imagine in care diferite zone pot fi apasate separat si pot duce spre locuri diferite.

## 47. Ce este `area`?
Defineste o zona interactiva din imagine. Poate fi dreptunghi, cerc sau poligon.

## 48. Cum functioneaza Google Maps in iframe?
Se foloseste un URL de tip embed in atributul `src`, iar harta apare direct in pagina.

## 49. Cum functioneaza playlistul YouTube in iframe?
Din parametrii URL:
- `autoplay=1`
- `controls=1`
- `loop=1`
- `playlist=id1,id2`

## 50. Ce ar trebui sa schimb eu manual inainte de predare?
Ideal:
- sa inlocuiesti imaginile generate cu imagini alese de tine
- sa verifici daca vrei sa schimbi numele autorului din meta
- sa rulezi inca o data cu Live Server
- sa ai deschis validatorul HTML la prezentare

## 51. Ce sa spun daca ma intreaba profesorul de ce am folosit un anumit tag?
Raspunsul bun este mereu:
- pentru semantica
- pentru accesibilitate
- pentru cerinta
- pentru structura corecta a informatiei

## 52. Cum sa gandesc pe viitor diferenta dintre taguri asemanatoare?
Intreaba-te:
- tagul asta doar arata ceva diferit?
- sau spune si ce rol are acel continut?

## 53. Ce sunt variabilele CSS si de ce le-am folosit?
Variabilele CSS sunt valori reutilizabile declarate de obicei in `:root`.

Le-am folosit pentru:
- culori
- spatiere laterala
- gap
- padding
- raze de border
- umbre

Avantajul este ca daca schimbi o valoare intr-un singur loc, se actualizeaza tot stilul dependent de ea.

## 54. Ce face `:root`?
Este selectorul folosit de obicei pentru variabile globale CSS, valabile in toata pagina.

## 55. Ce este `clamp()`?
`clamp(minim, preferat, maxim)` permite o valoare responsiva care nu coboara sub un minim si nu urca peste un maxim.

Este foarte util pentru:
- font-size
- padding
- gap
- latimi

## 56. Ce este CSS Grid?
Este un sistem de layout bidimensional.

Cu Grid poti controla:
- randuri
- coloane
- zone numite

In proiect, gridul este folosit pentru impartirea primei pagini in 8 zone.

## 57. Ce este `grid-template-areas`?
Este metoda prin care dai nume zonelor din grid si le asezi vizual mai clar in CSS.

Avantaj:
- layout-ul devine mai usor de citit
- schimbi mai simplu structura intre desktop, tablet si mobil

## 58. Ce este `gap`?
`gap` controleaza spatiul dintre elementele din grid sau flex.

Este preferabil fata de multe margini manuale pentru ca:
- este mai curat
- este mai usor de controlat
- se adapteaza bine in layout-uri responsive

## 59. Ce este un media query?
Un media query aplica stiluri diferite in functie de dimensiunea ecranului.

In proiect exista stiluri diferite pentru:
- ecran mare
- ecran mediu
- ecran mic

## 60. De ce am schimbat si `font-size` intre breakpoint-uri?
Pentru ca cerinta spune ca pe ecran mic textul trebuie sa fie putin mai mic, iar pe ecran mare putin mai mare.

## 61. De ce folosim `overflow-x: auto` la tabel?
Ca scroll-ul orizontal sa apara doar pe containerul tabelului, nu pe toata pagina.

## 62. Cum functioneaza alternanta de culori la tabel?
Am folosit doua idei:
- alternanta pe coloane
- alternanta pe randuri

La hover, randul isi schimba si el culoarea.

## 63. De ce am pus taburile video intr-un container separat?
Pentru ca cerinta cere:
- un container pentru linkuri
- un container care grupeaza linkurile si iframe-ul

Asa se controleaza mai usor layout-ul cu flexbox.

## 64. De ce butoanele din taburi sunt de fapt linkuri `<a>`?
Pentru ca ele schimba sursa afisata in `iframe`, nu declanseaza o actiune de formular.

Semantic, linkul este alegerea corecta.

## 65. Cum functioneaza efectiv taburile cu iframe?
Fiecare link are `target="video-produse"`, iar iframe-ul are `name="video-produse"`.

Cand apesi pe un link:
- browserul deschide acel URL
- dar il incarca in iframe-ul cu numele respectiv

## 66. Ce este flexbox si unde l-am folosit?
Flexbox este un sistem de layout bun pentru aliniere pe o directie principala.

L-am folosit in special pentru:
- meniu
- taburile video
- butoane

## 67. Cum este facut link-top?
Este un link fixat pe ecran, pozitionat cu `position: fixed`, in coltul din dreapta jos.

Are:
- un container cu forma speciala
- o sageata in interior
- tooltip
- efecte la hover

## 68. De ce nu functionau linkurile din `Cerinte_Rezolvate.md` pe GitHub?
Pentru ca erau linkuri locale absolute catre calculatorul tau.

Exemplu de problema:
- `C:/Users/...`

GitHub nu are acces la sistemul tau local, deci astfel de linkuri nu pot functiona in repo online.

## 69. Care este solutia corecta pentru documentatia din repo?
Sa pui:
- numele fisierului
- linia

sau, daca vrei linkuri reale pe GitHub, sa folosesti linkuri relative catre fisiere din repo, nu catre discul local.

## 70. Ce este un reset CSS?
Un reset CSS elimina diferentele implicite dintre browsere pentru:
- margini
- padding
- liste
- tabele
- afisarea unor elemente semantice

## 71. De ce am pus resetul in fisier separat?
Pentru ca aceasta este chiar cerinta bonusului si, in plus, separa:
- normalizarea de baza
- stilizarea efectiva

## 72. Cum este stilizata formula MathML?
Sunt colorate diferit:
- variabilele
- numerele
- operatorii

Astfel, formula este mai lizibila si bifeaza bonusul de stilizare.

## 73. Ce sa spun la prezentare despre etapa 2?
Poti explica simplu asa:
- am plecat de la structura HTML din etapa 1
- am adaugat doua fisiere CSS, unul de reset si unul de stil
- am construit layout-ul primei pagini cu CSS Grid
- am adaptat designul pentru desktop, mediu si mobil
- am implementat cerintele individuale pentru tabel, taburi si link-top
- am folosit variabile CSS pentru consistenta

## 74. Ce este nou in etapa 3?
Etapa 3 adauga doua lucruri mari:
- meniul responsive al site-ului
- stilul special pentru printare

## 75. De ce am avut nevoie de pagini noi?
Pentru ca cerinta pentru meniu spune ca trebuie sa existe o optiune care grupeaza alte pagini ale site-ului.

De aceea au fost adaugate:
- `catalog.html`
- `configuratii.html`
- `ghiduri.html`
- `contact.html`

## 76. Cum este organizat meniul?
Meniul are:
- optiuni principale
- icon pentru fiecare optiune principala
- submenu pentru pagini
- submenu pentru sectiuni

## 77. Ce se intampla pe ecran mare?
Pe ecran mare:
- textul din meniu este vizibil
- apare bara glisanta la hover
- submenu-ul se deschide prin scalare
- optiunile din submenu isi schimba fundalul la hover

## 78. Ce se intampla pe ecran mediu?
Pe ecran mediu:
- textul principal din meniu se ascunde
- raman doar iconurile

Aceasta respecta exact cerinta individuala pentru varianta medie.

## 79. Ce se intampla pe ecran mic?
Pe ecran mic:
- apare iconul de hamburger
- meniul se deschide din colt cu efect de tip clip-path circular
- submenu-urile raman vizibile in interiorul meniului deschis

## 80. Cum este facut hamburgerul?
Nu este imagine.

Este facut din 3 bare:
- 3 elemente `span`
- cu `width`, `height`, `background`
- pozitionate absolut in interiorul containerului

## 81. Ce bonusuri sunt bifate la hamburger?
Sunt bifate:
- hamburger din 3 bare HTML/CSS
- animatie la aparitia iconului
- schimbare de culoare
- transformare geometrica
- opacitate
- delay diferit pentru fiecare bara

## 82. De ce exista si fisierul `stil.scss` daca pagina foloseste `stil.css`?
Pentru ca enuntul cere explicit SASS/SCSS ca sursa pentru meniu.

Practic:
- `stil.scss` arata structura SCSS
- `stil.css` este varianta folosita efectiv de browser

## 83. Unde se vede nesting-ul din SCSS?
Nesting-ul este atunci cand un selector este scris in interiorul altuia.

Exemplu:
- `.menu-root`
- apoi `.menu-item`
- apoi `> a`

## 84. Ce face `@extend` in SCSS?
`@extend` permite reutilizarea unui bloc de stiluri comune.

In proiect este folosit pentru suprafata comuna a elementelor de meniu.

## 85. Ce face `@for` in SCSS?
`@for` genereaza cod repetitiv automat.

Aici este folosit pentru:
- `animation-delay` diferit pe fiecare bara din hamburger

## 86. Ce inseamna stil de printare?
Este un set de reguli CSS care se aplica doar cand pagina este tiparita sau deschisa in print preview.

## 87. De ce avem fisier separat `print.css`?
Pentru ca cerinta spune explicit ca stilul de print trebuie implementat separat.

## 88. Ce se ascunde la print?
La print sunt ascunse:
- imagini
- videoclipuri
- iframe-uri
- PDF embedded
- butonul `link-top`
- alte elemente vizuale dependente de media

## 89. De ce se scoate gridul la print?
Pentru ca cerinta spune ca pagina printata trebuie afisata ca bloc, nu in grid.

## 90. Cum apare meniul la print?
La print:
- sub titlul site-ului
- ca lista neordonata
- pe verticala
- fara suboptiuni

## 91. Ce este bannerul de print?
Este paragraful cu textul:
- `Acesta este un proiect scolar.`

La print apare separat, centrat, cu border inset, conform cerintei.

## 92. Ce este watermark-ul?
Este o eticheta semi-transparenta care apare pe fiecare pagina printata, in coltul din dreapta jos.

In proiect, watermark-ul contine:
- `Ristea`
- `Alexandru`

## 93. Ce fac regulile `@page :left` si `@page :right`?
Controleaza marginile diferit pentru:
- paginile din stanga
- paginile din dreapta

## 94. Ce inseamna page break?
Inseamna fortarea trecerii la pagina urmatoare in modul de print.

In proiect exista:
- un break dupa prima pagina
- un break inainte de footer

## 95. Ce sa spun la prezentare despre etapa 3?
Poti explica simplu asa:
- am extins site-ul la mai multe pagini
- am construit un meniu comun cu variante pentru desktop, tablet si mobil
- am facut hamburgerul din elemente HTML, nu din imagine
- am folosit si o sursa SCSS pentru bonusurile cerute
- am separat stilul de print intr-un fisier dedicat
