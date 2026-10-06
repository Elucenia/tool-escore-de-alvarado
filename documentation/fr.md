<!-- ELUCENIA technical documentation · escore-de-alvarado · fr · no clinical/professional/rights approval -->

# Score d’Alvarado

[conditions, sources et autorisations](https://elucenia.org/fr/outils/escore-de-alvarado)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Migration de la douleur vers la fosse iliaque droite

`migra`

### Anorexie (ou acétone urinaire)

`anorex`

### Nausées ou vomissements

`nausea`

### Douleur à la palpation de la fosse iliaque droite

`dor`

### Douleur à la décompression brusque (signe de Blumberg)

`desc`

### Température ≥ 37,3 °C

`febre`

### Hyperleucocytose \> 10 000/mm³

`leuco`

### Déviation à gauche (neutrophiles \> 75 %)

`desvio`

## Édition de la méthode

Alvarado 1986 : MANTRELS 8 items, 0–10 ; version avec déviation gauche

## Formule documentée

MANTRELS : Migration (1), Anorexie (1), Nausées/vomissements (1), T douleur fosse iliaque droite (2), R douleur au relâchement (1), E élévation de température (1), Leucocytose (2), S déviation gauche (1). Total 0 à 10.

## Limites et population

L’Alvarado 1986 a été élaboré à partir de 305 patients hospitalisés pour des douleurs abdominales évocatrices d’appendicite et de huit facteurs cliniques et biologiques. Le résumé original ne valide pas automatiquement différentes tranches d’âge, les femmes enceintes ou des stratégies de sortie ou d’imagerie. Les seuils décisionnels et la population de la version utilisée doivent être vérifiés séparément ; l’outil implémente la variante incluant la déviation à gauche.

## Références

- [Alvarado A. A practical score for the early diagnosis of acute appendicitis. Ann Emerg Med, 1986.](https://doi.org/10.1016/S0196-0644(86)80993-3)

- [Di Saverio S et al. Diagnosis and treatment of acute appendicitis: 2020 update of the WSES Jerusalem guidelines. World J Emerg Surg, 2020.](https://doi.org/10.1186/s13017-020-00306-3)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Résultats documentés

Les informations ci-dessous conservent les sorties de la méthode pour des exemples synthétiques. Elles ne constituent pas une validation clinique indépendante.

### 1

Appendicite improbable (0 à 4)

Envisager d'autres causes ; réévaluer si les symptômes persistent.


### 2

Compatible avec une appendicite (5 à 6)

Observation et réévaluation sériée ou examen d'imagerie.


### 3

Appendicite probable (7 à 8)

Évaluation chirurgicale ; imagerie selon le profil du patient.


### 4

Appendicite très probable (9 à 10)

Évaluation chirurgicale.

