# NeoFlow
**Namizna aplikacija za preprečevanje izgorelosti v IT okolju**

NeoFlow je osebni razporejevalnik nalog, ki upošteva **miselno obremenitev** in preprečuje preobremenitev z avtomatskim vstavljanjem pavz ter inteligentnim razporejanjem nalog glede na tvojo dnevno kapaciteto.

## Problem
V IT podjetjih je pogosto problem igorelosti (burnout) zaposlenih zaradi prevelikega obsega dela, nepravilnega razporejanja nalog in pomanjkanja ravnotežja med delom in odmori. Zaposleni pogosto presegajo svoje miselne kapacitete, kar vodi do zmanjšanje produktivnosti, stresa in dolgoročnih zdravstvenih težav.

## Kupci
Glavni kupci so zaposleni v IT podjetjih, kot so programerji, razvijalci, vodja projektov in drugi strokovnjaki, ki delajo v dinamičnem okolju z veliko sestanki in nalogami. To vključuje posameznike, ki želijo ohraniti privatnost svojih podatkov in se izogniti mikromanagementu s strani delodajalca.

## Edinstvena vrednost
- **100% offline in popolna zasebnost**: Podatki ostanejo SAMo na tvoji napravi (SQLite), brez oblaka -> Popolno za programerje, ki nočejo sledenja in mikromenegementa.
- Fokus izključno na **ročno energijsko oceno (1-10**.
- Prilagoejo specifično programerjem (barvno kodiranje glede na miselno zahtevnost)

## Rešitev
NeoFlow je namizna aplikacija, ki pomaga preprečevati izgorelost z inteligentnim razporejanjem nalog. Aplikacija se povezuje z Microsoft Teams in Google Calendar za pridobivanje fiksnih terminov (kot so sestanki in dogodki), upravlja TODO listo in avtomatsko razporeja naloge glede na njihovo miselno zahtevnost (ocena od 1 do 10). Uporablja lokalno SQLite bazo za shranjevanje podatkov, kar zagotavlja privatnost. Uporabnik nastavi dnevni limit miselnih točk, aplikacija pa samodejno razporedi naloge iz TODO liste in vstavlja pavze za odmor.

## Funkcije 
- **Integracija koledarjev**: Povezava z Microsoft Teams in Google Calendar za uvoz fiksnih dogodkov (sestanki, termini, dogodki)
- **TODO lista**: Upravljanje nalog
- **Miselne točke**: Nastavljanje miselnih točk fiksnim dogodkom in nalogam iz TODO liste (1-10)
- **Avtomatsko razporejanje**: Naloge se razporedijo v proste časovne okvirje v delovnem dnevu, upoštevajoč dnevnega limita miselnih točk.
- **Pavze za odmor**: Samodejno vstavljanje kratkih pavz med naloge za preprečevanje izgorelosti
- **Privatnost**: Vsi podatki shranjujejo lokalno v SQLite bazi, brez dostopa podjetja
