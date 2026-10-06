# RA1-ISSUE-02 - Localitzar `items.txt` i `users.txt`

- Prioritat: P0
- PDE vinculat: PDE1
- CE principal: CE1
- Milestone: M0 - Preparacio local
- Labels: `RA1`, `PDE1-rutes`, `P0`, `IA-1`, `starter`, `codi-condicional`
- Fitxer o component afectat: `files/items.txt`, `files/users.txt`
- Impacte sobre codi: codi_condicional

## Objectiu

Confirmar que el projecte utilitza rutes portables cap als fitxers de dades.

## Tasca

1. Identifica on es carreguen els fitxers.
2. Comprova si hi ha rutes absolutes.
3. Anota la ruta relativa que hauria de funcionar en qualsevol ordinador.

## Criteris d'acceptacio

- [ ] Els fitxers es localitzen amb ruta relativa o mecanisme portable.
- [ ] No hi ha dependencia d'una ruta local del professor o alumne.
- [ ] La decisio queda explicada en una nota curta.

## Rastre requerit

- *Issue* actualitzada, *commit* amb *push* i estat final.
- Una fila al `README` que indiqui la ruta relativa comprovada i el resultat.

## Fora d'abast

No introduir configuracio externa, bases de dades ni serveis.
