# Simulateur Citoyen — Présidentielle 2027

Application web statique permettant d'estimer l'impact direct et mécanique des programmes des candidats à l'élection présidentielle française de 2027 sur la vie quotidienne.

👉 **Accéder au simulateur en ligne :** `https://votre-pseudo.github.io/nom-du-depot/` *(remplacez par votre lien GitHub Pages)*

## Fonctionnalités

* **Profil quotidien personnalisable :** revenus et impôts, prestations CAF (APL, RSA, Prime d'activité, AAH, bourses), Sécurité sociale et mutuelle, logement, énergie, courses alimentaires, transports et retraite.
* **Comparaison neutre :** affichage côte à côte de 2 candidats ou vue globale, triés par ordre alphabétique sans note ni classement.
* **Transparence des calculs :** chaque estimation affiche la formule mathématique utilisée. Les postes non chiffrés par un candidat apparaissent explicitement avec la mention *« Mesure non précisée »*.
* **Mise à jour simplifiée :** éditeur JSON intégré dans l'interface pour actualiser les propositions ou importer des données au fil de la campagne.

## Méthodologie et sources

* **Effets directs uniquement :** le simulateur calcule uniquement des effets mécaniques directs (barèmes, seuils, taux de TVA, âge légal de départ) et ne modélise pas les effets macroéconomiques indirects (inflation, croissance, emploi).
* **État des données :** les propositions intégrées reflètent l'état des programmes publiés au **26 novembre 2026**. La liste officielle des candidats par le Conseil constitutionnel sera arrêtée après la clôture des parrainages le **12 mars 2027** (1er tour le 18 avril 2027).
* **Sources ouvertes :** les données s'appuient sur les programmes officiels publiés par les candidats et peuvent être actualisées à partir des jeux de données ouverts recensés sur [data.gouv.fr](https://www.data.gouv.fr).

## Utilisation technique

Le projet fonctionne sans serveur ni base de données : tout est contenu dans un seul fichier `index.html` (HTML, CSS et JavaScript pur), hébergé via GitHub Pages.
