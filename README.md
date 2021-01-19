# Apunts_UF2

## Proves

### Què són
Quan parlem de proves de software, ens referim a comprovar el correcte funcionament d’aquest, el rendiment, la seva seguretat, etc.

### Estratègies de prova
  - **Caixa negra**: S'estudia el sistema des de fora (proves de funcionalitat).
    - Estudia el sistema desde l'exterior.
    - Es treballa directament sobre l'interficie.
    - No es tenen en compte els detalls interns del funcionament del programa.
    - Es proporcionen entrades i s'estudïen les sortides.
    
  - **Caixa blanca**: s'examina el codi font I la seva execució (proves estructurals).
    - S'examina el codi font i la seva execució.
    - Es comprova la execució de cada unitat (funcions, classes, mòduls, etc), entre unitats o fins i tot entre subsistemes.

### Tipus de proves
  - **Funcionals**: Es fa una evaluació del cumpliment dels requisits   .
  - **No funcionals**: Es fa una evaluació dels aspectes addicionals (rendiment, seguretat, etc).

## Framework

### Què és un Framework?
Un Framework és un entorn de treball de la programació orientada a objectes que facilita la realització de proves de software, amb suport per a programes, llibreries i un llenguatge interpretat.

### De què es composa un Framework?
  - **Controlador**: És la part del framework que gestiona l'accés a l'aplicació. Inclou els programaris necessaris perquè l'aplicació funcioni, els scripts (arxius per a l'execució de múltiples tasques) i altres tipus d'arxius.
  - **Model**: És la part del framework que gestiona les operacions lògiques.
  - **Vista**: És la interfície, és a dir, la part gràfica o visible amb la qual interactua l'usuari.

## Integració

### Tipus d'integració
  - Continua
  - Ascendent
  - Descendent
  
#### Serveis web Integració continua
  - Jenkins
  - Bamboo
  - Travis CI
  - Circle CI

### Cobertura del codi
  - Indica el percentatge de la prova realitzada(execució)
  - Es aconsellable que el percentatge arribi al 100%
  - Possibilitat de realitzar les cobertures a diferents IDE's que es basin en java.

## Qualitat

### Tipus de qualitat
  - QA(Quality Assurance): conjunt d'activitats per a garantir la qualitat dels processos.
  - QC(Quality Control): conjunt d'activitats per a garantir la qualitat dels productes.
  
### Factors de qualitat
  - **Operació del producte**
    - Correcció: que el software faci el que es busca.
    - Fiabilitat: que el software ho faci de forma correcta sempre.
    - Eficiència: que s’executi de la millor manera possible.
    - Seguretat: que sigui el més segur possible.
    - Facilitat d’ús: que sigui fàcil d’utilitzar
  - **Revisió del producte**
    - Manteniment: que es pugui arreglar
    - Flexibilitat: que es pugui modificar
    - Facilitat de prova: que es pugui provar
  - **Transició del producte**
    - Portabilitat: que es pugui utilitzar a una altre màquina
    - Reusabilitat: que es pugui reutilitzar part del software
    - Interoperativitat: que ho puguis comunicar amb una altre màquina
