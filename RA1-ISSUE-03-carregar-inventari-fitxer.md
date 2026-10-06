# RA1-ISSUE-03 - Carregar inventari des de fitxer

- Prioritat: P0
- PDE vinculat: PDE2
- CE principal: CE3
- Milestone: M1 - Inventari llegit
- Labels: `RA1`, `PDE2-lectura-escriptura`, `P0`, `IA-1`, `starter`, `codi`
- Fitxer o component afectat: `files/items.txt`, capa de lectura
- Impacte sobre codi: codi_obligatori

## Objectiu

Llegir `files/items.txt` de manera seqüencial, una línia cada vegada, sense interpretar encara el contingut.

## Tasca

1. Obre el fitxer amb un `BufferedReader` dins d'un `try-with-resources`.
2. Llegeix i tracta cada línia com a text.
3. Deixa preparada la crida a la conversió que completaràs a `RA1-ISSUE-04`.

## Criteris d'acceptacio

- [ ] El fitxer es llegeix línia a línia i el recurs es tanca automàticament.
- [ ] La lectura no depèn de dades escrites directament al codi.
- [ ] No s'interpreten camps ni es construeixen `Product` en aquesta issue.

## Rastre requerit

- *Issue* actualitzada, *commit* amb *push* i estat final.
- Una fila al `README` que indiqui el cas de lectura i el resultat.

## Fora d'abast

No convertir la línia a `Product` ni desar canvis; això correspon a issues posteriors.
