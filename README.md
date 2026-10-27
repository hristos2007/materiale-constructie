# Materiale de construcție

Site web de prezentare pentru un magazin de materiale de construcție. Pagina conține informații despre magazin, serviciile oferite și un catalog de materiale cu prețuri.

Proiectul este realizat în cadrul lucrării „Gestionarea versiunilor unui proiect software utilizând Git și GitHub".

## Descriere

Magazinul se prezintă ca partener de încredere în crearea, repararea și îmbunătățirea oricăror obiecte, oferind materiale de înaltă calitate la prețuri competitive.

Site-ul este o pagină unică (single page) cu navigare prin secțiuni.

## Structura paginii

| Secțiune | Conținut |
|----------|----------|
| **Header** | Titlul magazinului și meniul de navigare (Despre noi, Servicii, Catalog, Contacte) |
| **Despre noi** | Scurtă prezentare a magazinului și a scopului acestuia |
| **Serviciile noastre** | Vânzare de materiale de construcții, livrare la domiciliu, consultații de specialitate |
| **Catalogul de materiale** | Carduri cu imagine, denumire și preț pentru fiecare produs |
| **Contacte** | Datele de contact ale magazinului |

## Serviciile oferite

1. **Vânzare materiale de construcții**: gamă largă, de la cărămizi și ciment până la materiale de finisare și unelte, la prețuri competitive.
2. **Livrare la domiciliu**: livrare rapidă, indiferent de volumul comenzii, la un moment convenabil pentru client.
3. **Consultații de specialitate**: ajutor din partea specialiștilor la alegerea materialelor în funcție de sarcinile clientului.

## Catalog

| Produs | Preț |
|--------|------|
| Fortan | 500 lei/m³ |
| Ciment | 200 lei/sac |
| Cărămidă | 700 lei/m³ |
| Scânduri | 300 lei/m³ |

## Tehnologii utilizate

- HTML5: structura paginii
- CSS3: stilizare și aranjarea cardurilor din catalog
- Git și GitHub: controlul versiunilor

## Structura proiectului

```
.
├── index.html     # pagina principală
├── style.css      # stilurile paginii
├── .gitignore     # fișiere ignorate de Git
└── README.md      # descrierea proiectului
```

## Rulare locală

1. Clonați repozitoriul:
   ```bash
   git clone https://github.com/NUME_UTILIZATOR/NUME_REPOZITORIU.git
   cd NUME_REPOZITORIU
   ```
2. Deschideți fișierul `index.html` într-un browser.

Nu sunt necesare instalări suplimentare sau un server web.

## Lucrul cu Git

Proiectul este dezvoltat folosind ramuri separate pentru fiecare componentă (header, footer, contact, stiluri), care sunt integrate în ramura principală `main` prin operația `merge`. Versiunile stabile sunt marcate cu tag-uri (de exemplu, `v1.0`).

## Autor

Pogolsa Constantin, grupa AAW-231
