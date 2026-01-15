# NeoFlow Planner 🚀

**Osebni planer, ki varuje tvojo energijo** ⚡

NeoFlow je **MVP** (minimal viable product) – preprost osebni koledar/planer, ki ti pomaga razporediti naloge tako, da se izogneš preveliki obremenitvi in izgorelosti.

Posebej namenjen programerjem in ljudem z intelektualno zahtevnim delom 💻

**Trenutno stanje:** samo Windows desktop različica (šolski projekt – 1 mesec razvoja)

## Kaj MVP res zmore (core features) ✨

- 📅 Lokalni koledar + seznam nalog (vse shranjeno samo na tvojem računalniku – SQLite)
- 🔋 Ročna ocena energije/fokusa za vsako nalogo in dogodek (1–10)
- 🧠 Enostavno pametno razporejanje:
  - izogne se nalaganju visoko-energijskih nalog zaporedoma
  - vstavlja kratke pavze po zahtevnih blokih ☕
  - upošteva tvoj dnevni energijski budget (nastavljiv)
- 🎨 Barvno označevanje (zelena = lahka, rumena = srednja, rdeča = visoka obremenitev)
- ⚡ Gumb »Načrtuj moj dan« – hitro prerazporedi naloge okoli fiksnih dogodkov
- 🔒 **Popolna zasebnost** – nič oblaka, nič sinhronizacije, nič podjetja, nič sledenja

## Kaj MVP (še) NE zmore

- Ni mobilne različice (Android/iOS) – možna kasneje, če bo projekt nadaljevan 📱
- Ni avtomatskega zaznavanja energije (npr. iz ure, spanja...)
- Ni naprednega AI razporejanja
- Ni sinhronizacije med napravami (možen ročni izvoz/uvoz .db3 datoteke)
- Ni timskega pogleda ali deljenja

## Tehnologije (uporabljene v MVP) 🛠️

- .NET MAUI (.NET 9 ali 10)
- SQLite – lokalna podatkovna baza
- CommunityToolkit.Mvvm + XAML
- [Ime koledarskega kontrolnika, npr. XCalendar.Maui / Syncfusion Scheduler Community]

## Kako zagnati (Windows) ▶️

1. Odpri projekt v **Visual Studio 2022** ali novejši
2. Izberi konfiguracijo **Windows** (Machine) kot ciljno platformo
3. Pritisni **F5** → zažene se aplikacija

## Namen projekta

To je **šolski projekt** – izdelan januar 2026 v okviru [ime predmeta].  
Namenjen je izključno **osebni rabi** in dokazovanju koncepta.

**Ni namenjen**  
- nadzoru zaposlenih  
- uporabi v podjetjih  
- kakršnemukoli zbiranju podatkov s strani tretjih oseb

---
Če ti je všeč ideja – uporabi ga zase in varuj svojo energijo! 😊  
Če se bo projekt nadaljeval, pridejo mobilna različica, lepši dizajn in morda še kaj pametnejšega 🌟
