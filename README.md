# Biračka mesta Savskog venca

Pregled rezultata, izlaznosti i primedbi iz zapisnika biračkih odbora za sva biračka mesta opštine Savski venac (Beograd), na osam izbora od 2022. do 2026:

- 3. 4. 2022: gradski, parlamentarni i predsednički izbori
- 17. 12. 2023: parlamentarni i gradski izbori
- 2. 6. 2024: gradski izbori i izbori za opštinu Savski venac
- 25. 10. 2026: parlamentarni izbori (39 biračkih mesta; službeni rezultati RIK-a, stanje 28. 10. 2026; zapisnici još nisu pročitani)

Prototip je napravljen za kontrolore na parlamentarnim izborima 25. oktobra 2026.

## Sadržaj

- `index.html`: cela stranica (HTML, CSS i JavaScript u jednom fajlu, bez eksternih biblioteka)
- `data.json`: isti podaci kao oni ugrađeni u stranicu

Na stranici svakog biračkog mesta, u tabeli „Rezultati po izborima“, nalaze se linkovi ka skenovima zapisnika na sajtu RIK-a (RG-2, RG-11, RG-7).

## Izvor i ograničenja

- Izvor su javno objavljeni skenovi zapisnika sa sajta RIK-a (rik.parlament.gov.rs). Brojevi su ručno prepisani, pa ih pre citiranja proverite u izvornom zapisniku.
- Razvrstavanje lista na vlast, satelite, prebegle, opoziciju i nejasno je procena, sa izvorima na kartici „O podacima“.
- Napomene i primedbe su kategorisane automatski.
- Statističko odstupanje (više od 2,5 standardne devijacije među biračkim mestima) pokazuje gde da pogledate zapisnik. Nije dokaz nepravilnosti.
- Imena pojedinačnih posmatrača su izostavljena.
