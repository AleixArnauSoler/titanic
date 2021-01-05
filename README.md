# Titanic

Aquest repositori conté el codi, dades i respostes per a la realització de la pràctica 2 de l'assignatura "Tipologia i cicle de vida de les dades" del Màster en Ciència de Dades de la Universitat Oberta de Catalunya. La pràctica elaborada consisteix en la implementació de tècniques de neteja i anàlisis de dades. Podeu trobar més informació al pdf adjunt (PRAC2.pdf)

##  Descripció

L’enfonsament del Titanic és un dels naufragis més famosos de la història. El 15 d'abril de 1912, durant el seu viatge inaugural, el considerat "inenfonsable" RMS Titanic es va enfonsar després de xocar amb un iceberg. Malauradament, no hi havia prou bots salvavides per a tothom a bord, cosa que va provocar la mort de 1502 de 2224 passatgers i tripulants. Tot i que hi va haver algun element de sort per sobreviure, sembla ser que alguns grups de persones tenien més probabilitats de sobreviure que d’altres.

El dataset utilitzat en aquesta pràctica és *Titanic: Machine Learning from Disaster*, disponible clicant a [*aquí*](https://www.kaggle.com/c/titanic). 


## Objectiu del dataset

L'objectiu d'aquesta pràctica és la creació final d'un o varis models predictius que responguin a la pregunta: **"quin tipus de persones tenien més probabilitats de sobreviure?"**. Per això, caldrà primer netejar i analitzar les dades dels passatgers a bord del RMS Titanic (*i.e.* nom, edat, sexe, classe socioeconòmica, etc.) abans de construir els models per a predir quins passatgers van sobreviure a l'enfonsament del Titanic.


## Membres de l'equip

Les diferents tasques de la pràctica (i.e. recerca, desenvolupament de codi, redacció, etc) han estat elaborades de manera igualitaria per part dels alumnes Aleix Arnau Soler (aarnauso; @github/AleixArnauSoler) i Adrià Tarradas Planella (atarradasp; @github/latp)


## Fixers disponibles

Aquest repositori consta dels seguents fitxers:

- **README.md**: informació sobre el contingut del repositori i els fitxers disponibles.
- **practica_2.Rmd**: codi en RMarkdown de la pràctica
- **practica_2.pdf**: informe de la pràctica generat a partir del fitxer practica_2.Rmd
- **data/train.csv**: dataset descarregat de Kaggle per entrenar els models
- **data/test.csv**: dataset descarregat de Kaggle per avaluar els models 
- **data/gender_submission.csv**: dataset descarregat de Kaggle que serveix d'exemple del format que s'ha de presentar a la competició
- **out/dataset_titanic_clean.csv**: fitxer generat amb les dades processades
- **out/prediction_comp.csv**: fitxer presentat a la competició de Kaggle


## Llibreries utilitzades

El codi està elaborat en llenguatge R. El desenvolupament de la pràctica ha estat utilitzant l'entorn de treball RStudio. En cas que no s'hagin instal·lat prèviament, per executar el codi serà necessari instalar les següents llibreries:

```
install.packages(readr)
install.packages(stringr)
install.packages(kableExtra)
install.packages(tibble)
install.packages(dplyr)
install.packages(ggplot2)
install.packages(plyr)
install.packages(ggpubr)
install.packages(gmodels)
install.packages(e1071)
```


# Bibliografia

- Gibergans, J. (2019). Regressió lineal simple. Editorial UOC.
- Gibergans, J. (2019). Regressió lineal múltiple. Editorial UOC.
- Guillén, M., Alonso, M. T. (2019). Models de regressió logística. Editorial UOC.
- Liviano, D., Pujol, M. (2019). Models de regressió i anàlisi multivariant amb R-Commander. Editorial UOC.
