<a href="https://loot.klasicangejming.com/"><img src="media/cover.jpg" alt="KG Loot, naslovna strana na laptopu i telefonu" width="100%"></a>

# KG Loot

Platforma za oglase polovne gaming opreme, napravljena uz portal Klasičan Gejming, sa pretragom, porukama između korisnika i kreditima za oglase.

**[loot.klasicangejming.com](https://loot.klasicangejming.com/)** · [English](README.md)

> [!NOTE]
> Klijentski projekat. Izvorni kod pripada klijentu i čuva se u privatnom repozitorijumu. Ova stranica opisuje šta sam uradio i kako.

<table>
  <tr><td><b>Klijent</b></td><td>Klasičan Gejming</td></tr>
  <tr><td><b>Delatnost</b></td><td>Oglasi za polovnu gaming opremu</td></tr>
  <tr><td><b>Lokacija</b></td><td>Srbija</td></tr>
  <tr><td><b>Vrsta</b></td><td>Platforma za oglase (PWA)</td></tr>
  <tr><td><b>Moj deo posla</b></td><td>Dizajn, izrada, SEO, hosting i održavanje</td></tr>
  <tr><td><b>Tehnologije</b></td><td>PHP, MariaDB, PWA</td></tr>
</table>

## O projektu

KG Loot je platforma za oglase zajednice Klasičan Gejming, na kojoj gejmeri prodaju grafičke karte, konzole, igre i periferiju koju više ne koriste. Napravio sam je uz portal, sa 18 kategorija, od grafičkih karata i SSD diskova do retro gejminga i opreme za striming.

Svaki oglas je strana sa slikama, stanjem, gradom, cenom i brojem pregleda, uz dugmad za poziv, poruku prodavcu na sajtu ili WhatsApp. Objavljivanje ide preko kredita, a svaki nov nalog dobija tri besplatna. Oglas može biti običan, istaknut na vrhu kategorije, premium na naslovnoj ili označen kao hitna prodaja, a istekao oglas se vraća iz sekcije Moji oglasi.

## Šta sam uradio

- Pretraga po reči, kategoriji, gradu, stanju i rasponu cene, sa sortiranjem po najnovijem, najstarijem ili ceni
- Strane oglasa sa savetima za bezbednu kupovinu i sličnim oglasima iz iste kategorije
- Poruke između kupca i prodavca unutar platforme, pored dugmadi za poziv i WhatsApp
- Krediti za vrste oglasa, sa trajanjem od 30 dana, odnosno 14 za hitnu prodaju, i tri besplatna kredita pri registraciji
- Pravila korišćenja sa starosnom granicom, jednim nalogom po osobi, zabranjenim predmetima i sankcijama
- Instalira se kao PWA, a forme štiti nevidljiva provera koju pregledač rešava u pozadini, uz proveru jednim klikom kad to ne uspe

## Merenja

| | Performanse | Pristupačnost | Dobre prakse | SEO |
| :-- | :-: | :-: | :-: | :-: |
| Telefon | 100 | 100 | 100 | 100 |
| Desktop | 100 | 98 | 100 | 100 |

Lighthouse, laboratorijsko merenje živog sajta, septembar 2026.

## Snimci ekrana

<table>
  <tr>
    <td width="68%" valign="top"><img src="media/desktop.webp" alt="KG Loot, naslovna strana na ekranu širine 1440 px"></td>
    <td width="32%" valign="top"><img src="media/mobile.webp" alt="KG Loot, naslovna strana na telefonu"></td>
  </tr>
</table>

---

<sub>Izrada: [D. Svilenković](https://svilenkovic.rs).</sub>
