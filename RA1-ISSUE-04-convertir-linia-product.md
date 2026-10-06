# RA1-ISSUE-04 - Convertir linia de text a `Product`

- Prioritat: P0
- PDE vinculat: PDE3
- CE principal: CE5
- Milestone: M1 - Inventari llegit
- Labels: `RA1`, `PDE3-parser-conversio`, `P0`, `IA-1`, `starter`, `codi`
- Fitxer o component afectat: parser o metode de conversio
- Impacte sobre codi: codi_obligatori

## Objectiu

Transformar cada linia valida del fitxer en un objecte `Product` coherent amb el model del projecte.

## Tasca

1. Implementa `parseProductLine(String line)` a `Shop.java`.
2. Separa camps i clau/valor, i converteix preu i estoc al tipus adequat.
3. Retorna un `Product` i fes que la lectura l'afegeixi quan la línia és vàlida.

## Criteris d'acceptacio

- [ ] Una linia valida genera un `Product`.
- [ ] Els valors numerics es converteixen de forma controlada.
- [ ] El codi queda localitzat en una responsabilitat clara.

## Rastre requerit

- *Issue* actualitzada, *commit* amb *push* i estat final.
- Una fila al `README` amb una línia vàlida i el resultat observat.

## Fora d'abast

No canviar el format del fitxer ni resoldre el desament; el desament correspon a `RA1-ISSUE-09`.
