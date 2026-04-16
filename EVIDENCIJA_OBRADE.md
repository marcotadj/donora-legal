# Evidencija aktivnosti obrade osobnih podataka

**Temelj:** Članak 30. Uredbe (EU) 2016/679 (GDPR)
**Voditelj obrade:** Donora, obrt za ugostiteljstvo, vl. Marko Kunštek
**OIB:** 48726073820 · **MBO:** 98607545
**Sjedište:** Ulica dr. Ljudevita Gaja 5, 49000 Krapina
**Kontakt:** obrt.donora@gmail.com · 092 263 1136
**Odgovorna osoba:** Marko Kunštek (vlasnik obrta)
**Datum uspostave evidencije:** 16.04.2026.

---

> **Napomena:** Ovo je interni dokument koji se ne objavljuje javno. Služi kao dokaz usklađenosti s GDPR-om (čl. 30.) i pokazuje se nadzornom tijelu (AZOP) na zahtjev. Čuvati u papirnatom ili elektroničkom obliku minimalno 5 godina.

## 1. Obrada podataka — Mobilna aplikacija „Burger Bar by Art"

### 1.1. Kategorije ispitanika
- Registrirani korisnici mobilne aplikacije (kupci)

### 1.2. Kategorije osobnih podataka
| Kategorija | Primjer |
|---|---|
| Identifikacijski podaci | E-mail, ime i prezime, Firebase UID |
| Komunikacijski podaci | Sadržaj chata s kuhinjom |
| Podaci o narudžbi | Stavke menija, količine, vrijeme, napomene |
| Lojalty podaci | Broj pečata, referral kod, broj preporuka |
| Tehnički podaci | FCM token (push), verzija app-a, tip uređaja (Android) |

### 1.3. Svrhe obrade
1. Izvršenje ugovora o naručivanju hrane i pića
2. Vođenje korisničkog računa i komunikacija s kupcem
3. Provođenje loyalty programa (pečati, nagrade, referral)
4. Slanje obavijesti o statusu narudžbe
5. Slanje promotivnih obavijesti (samo uz privolu)

### 1.4. Pravna osnova (čl. 6. GDPR)
- **čl. 6(1)(b)** — izvršenje ugovora: narudžbe, chat, loyalty, račun
- **čl. 6(1)(a)** — privola: promotivne push obavijesti
- **čl. 6(1)(c)** — zakonska obveza: čuvanje poreznih podataka

### 1.5. Primatelji podataka
- Google LLC / Google Ireland Ltd. (Firebase Authentication, Cloud Firestore, Firebase Cloud Messaging) — obrađivač
- Vlasnik obrta i zaposlenici u objektu (pristup narudžbama)

### 1.6. Prijenos u treće zemlje
- Google kao obrađivač može pohranjivati podatke na poslužiteljima u SAD-u. Prijenos je osiguran **Standard Contractual Clauses (SCC)** koje je Google prihvatio. Dokumentacija: https://cloud.google.com/terms/data-processing-addendum

### 1.7. Rok čuvanja
- Aktivan račun: za vrijeme trajanja računa
- Nakon brisanja računa: osobni identifikatori trenutno se brišu; porezno-relevantni podaci o računima čuvaju se **11 godina** (Zakon o računovodstvu, Opći porezni zakon)
- Chat: briše se s narudžbom/računom

### 1.8. Tehničke i organizacijske mjere sigurnosti
- **Prijenos:** TLS 1.2+ (HTTPS)
- **Autentifikacija:** Firebase Auth (hash lozinki, OAuth 2.0 za Google prijavu)
- **Pristup bazi:** Firebase Firestore Security Rules (samo autenticirani korisnici, pristup ograničen po UID-u)
- **Lozinka vlasničkog računa (admin panel):** jaka lozinka, nije dijeljena
- **Fizička sigurnost:** uređaj s admin pristupom pod nadzorom vlasnika
- **Edukacija osoblja:** informirani o zabrani dijeljenja korisničkih podataka

---

## 2. Obrada podataka — Poslovna komunikacija

### 2.1. Primljene porukes/e-mailovi kupaca
- **Kategorija ispitanika:** kupci koji se obrate na obrt.donora@gmail.com
- **Podaci:** e-mail adresa, ime, sadržaj poruke
- **Svrha:** odgovor na upit / reklamaciju
- **Pravna osnova:** čl. 6(1)(b) ili čl. 6(1)(c) (reklamacije)
- **Rok čuvanja:** do 2 godine nakon završetka komunikacije

---

## 3. Obrada podataka — Fiskalizirani računi

### 3.1. Izdani računi
- **Kategorija ispitanika:** kupci u ugostiteljskom objektu
- **Podaci:** prema Zakonu o fiskalizaciji (nisu osobni podaci u klasičnom smislu, osim ako kupac zatraži račun na OIB)
- **Svrha:** izvršenje zakonske obveze
- **Pravna osnova:** čl. 6(1)(c) — zakonska obveza
- **Rok čuvanja:** 11 godina (Zakon o računovodstvu)

---

## 4. Prava ispitanika

Sva prava iz poglavlja III. GDPR-a (čl. 15-22) osigurana su putem:
- Funkcionalnosti „Obriši račun i sve podatke" u aplikaciji
- E-maila obrt.donora@gmail.com
- Odgovora u roku od 30 dana

## 5. Obavijesti o povredi podataka

U slučaju povrede sigurnosti osobnih podataka:
- **72 sata** za prijavu AZOP-u (čl. 33. GDPR)
- Obavještavanje ispitanika ako postoji visok rizik (čl. 34.)
- Vođenje internog registra povreda

## 6. Revizija evidencije

| Datum | Promjena | Potpis |
|---|---|---|
| 16.04.2026. | Uspostava evidencije | Marko Kunštek |

---

**Potpis vlasnika:** _______________________ (Marko Kunštek)

**Datum:** _______________________
