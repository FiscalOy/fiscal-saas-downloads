# Fiscal Info TV - Asennuspaketit

![Status](https://img.shields.io/badge/Status-Public-green)
![Type](https://img.shields.io/badge/Type-Installation%20Packages-blue)
![License](https://img.shields.io/badge/License-Proprietary-red)

*Päivitetty: 2025-10-15*

---

## ⚠️ TÄRKEÄÄ - Pakettityypit

Fiscal Info TV:stä on **kaksi eri pakettityyppiä**:

### 📦 **Täysi asennuspaketti** (`Fiscal_Info_TV_versio.msi`)
- ✅ Uusi asennus tyhjälle koneelle
- ✅ Sisältää kaikki tarvittavat komponentit
- ✅ Voidaan asentaa ilman aikaisempaa versiota
- 📝 Esimerkki: `Fiscal_Info_TV_25.10.10.1.msi`

### 🔄 **Päivityspaketti** (`Fiscal_Info_TV_upd_versio.msi`)
- ⚠️ **VAATII täyden asennuspaketin!**
- ⚠️ Täysi paketti täytyy olla asennettuna ennen päivitystä
- ✅ Pienempi tiedostokoko
- ✅ Nopeampi asennus
- 📝 Esimerkki: `Fiscal_Info_TV_upd_25.10.15.3.msi`

---

## 📥 Lataukset

### 📦 Täysi asennuspaketti
**Uusille käyttäjille tai uusille koneille:**

👉 **[Lataa täysi asennuspaketti (Releases)](https://github.com/FiscalOy/fiscal-saas-downloads/releases)**

### 🔄 Päivityspaketit
**Olemassa oleville käyttäjille (täysi paketti jo asennettuna):**

👉 **[Lataa päivitys (Releases)](https://github.com/FiscalOy/fiscal-saas-downloads/releases)**

---

## 📋 Yleiskuvaus

**Fiscal Info TV** on ammattimainen Digital Signage -ratkaisu, joka koostuu kahdesta pääkomponentista:
- 🎬 **Fiscal Player** - Full-screen mediasoitin (kuvat, videot, PDF, HTML)
- ✅ **Fiscal Checker** - Taustapalvelu (SignalR, tiedostojen lataus)

---

## 🚀 Asennus

### 📦 UUSI ASENNUS (Täysi paketti)

1. **Lataa täysi asennuspaketti:**
   - Mene [Releases-osioon](https://github.com/FiscalOy/fiscal-saas-downloads/releases)
   - Etsi paketti jonka nimi alkaa `Fiscal_Info_TV_` (ilman `upd`)
   - Esimerkki: `Fiscal_Info_TV_25.10.10.1.msi`
   - Lataa tiedosto

2. **Asenna ohjelma:**
   - Kaksoisklikkaa `.msi` -tiedostoa
   - Seuraa asennusohjelman vaiheita
   - Vaatii järjestelmänvalvojan oikeudet

3. **Valmis!**
   - Fiscal Player ja Checker käynnistyvät automaattisesti

---

### 🔄 PÄIVITYS (Päivityspaketti)

⚠️ **VARMISTA ENSIN että täysi asennuspaketti on asennettu!**

1. **Tarkista nykyinen versio:**
   - Avaa Fiscal Player tai Checker
   - Katso versionumero (esim. `25.10.10.1`)

2. **Lataa päivityspaketti:**
   - Mene [Releases-osioon](https://github.com/FiscalOy/fiscal-saas-downloads/releases)
   - Etsi paketti jonka nimi alkaa `Fiscal_Info_TV_upd_`
   - Esimerkki: `Fiscal_Info_TV_upd_25.10.15.3.msi`
   - Lataa tiedosto

3. **Asenna päivitys:**
   - Kaksoisklikkaa `upd`-tiedostoa
   - Päivitys asentuu olemassa olevan version päälle
   - Asetukset säilyvät

4. **Uudelleenkäynnistys:**
   - Ohjelmat käynnistyvät uudelleen automaattisesti

---

## 📋 Järjestelmävaatimukset

### Vähimmäisvaatimukset:
- **Käyttöjärjestelmä:** Windows 10 (64-bit) tai uudempi
- **Prosessori:** Intel/AMD dual-core 2.0 GHz
- **RAM:** 4 GB
- **Levytila:** 32 GB (vapaa tila vähintään 4 GB)
- **.NET Runtime:** .NET 9.0 Runtime (sisältyy täyteen asennuspakettiin)
- **Verkko:** Internet-yhteys

### Suositellut vaatimukset:
- **Käyttöjärjestelmä:** Windows 11 (64-bit)
- **Prosessori:** Intel/AMD quad-core 2.5 GHz
- **RAM:** 8 GB
- **Levytila:** 128 GB SSD (vapaa tila vähintään 8 GB)
- **Näyttö:** Full HD (1920x1080)

---

## 📝 Versiohistoria

Katso kaikki julkaistut versiot ja muutokset:

**[📖 MUUTOSHISTORIA.md](./MUUTOSHISTORIA.md)**

---

## 🔧 Yleiset ongelmat

### ❌ "Täysi asennuspaketti puuttuu" -virhe
```
Syy: Yrität asentaa päivityspakettia ilman täyttä asennusta.
Ratkaisu: Lataa ja asenna ensin täysi asennuspaketti (ilman "upd").
```

### ❌ Asennusohjelma ei käynnisty
```
Ratkaisu:
1. Oikea klikkaus .msi → "Run as administrator"
2. Tarkista Windows Defender / Antivirus-asetukset
```

### ❌ ".NET Runtime puuttuu" -virhe
```
Ratkaisu:
1. Lataa .NET 9.0 Runtime: https://dotnet.microsoft.com/download/dotnet/9.0
2. Asenna Runtime
3. Yritä asennusta uudelleen
```

---

## 🆘 Tuki

**📧 Sähköposti:** [tuki@fiscalinfotv.fi](mailto:tuki@fiscalinfotv.fi)
**🌐 Verkkosivusto:** [https://fiscalinfotv.fi](https://fiscalinfotv.fi)
**📚 Käyttöopas:** [Fiscal Info TV -käyttöopas](https://fiscalinfotv.fi/fiscal-info-tv-ratkaisun-kayttoopas/)

---

## ⚖️ Lisenssi

**Fiscal Oy** - Kaikki oikeudet pidätetään.

Tämä ohjelmisto on tarkoitettu vain Fiscal Oy:n asiakkaille.

**Copyright © 2025 Fiscal Oy**

---

*Fiscal Info TV - Ammattimainen Digital Signage -ratkaisu*
