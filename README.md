# Tableau de Bord RH – Analyse des Données RH
Dashboard Power BI pour l'analyse des ressources humaines : effectifs, salaires, performance, absentéisme et formation.

 Contenu du projet
FichierDescriptionAnalyse_de_RH-DATA.pbix 
Fichier Power BI principal 
dataset_rh_maroc.xlsx
Dataset source (600 employés)

 ### Page 1 — Vue Effectifs & Salaires
 Ancienneté Moyenne par Type_Contrat
Donut chart qui compare l'ancienneté moyenne selon le type de contrat.

CDI : 3.50 ans (33.83%)
CDD : 3.35 ans (32.38%)
Intérim : 3.50 ans (33.78%)
Insight : Les trois contrats ont une ancienneté similaire — pas de différence significative.

#### Nombre Employés par Département
Bar chart horizontal montrant la répartition des effectifs par département.

Commercial domine avec le plus grand nombre d'employés.
Finance et Production arrivent ensuite.
Insight : L'entreprise est orientée commerce et production.

#### Salaire Moyen par Niveau
Bar chart comparant les salaires selon le grade.

Manager : salaire le plus élevé (~30K MAD)
Senior : ~20K MAD
Intermédiaire : ~12K MAD
Junior : ~6K MAD
Insight : Progression salariale cohérente avec la hiérarchie.

#### % Hommes et % Femmes par Département
Donut chart montrant la répartition par genre dans chaque département.

Répartition quasi-équilibrée dans la plupart des départements (~50/50).
RH : légèrement plus féminin.
Production : légèrement plus masculin.
Insight : Bonne parité globale dans l'entreprise.


### Page 2 — Vue Géographie & Performance
#### KPI Cards
IndicateurValeur👥 Nombre Employés600💰 Total Masse Salariale6.98M MAD⭐ Score Moyen Performance7.12 / 10💵 Salaire Moyen11.64K MAD
#### Total Masse Salariale par Ville
Bar chart horizontal comparant la masse salariale par ville.

Agadir et Casablanca en tête.
Oujda et Fes en bas.
Insight : Les grandes villes concentrent les salaires les plus élevés.

#### Nombre Employés par Région (Map)
Carte géographique du Maroc montrant la densité d'employés par région.

Grand Casablanca et Souss-Massa : régions les plus actives.
Oriental : moins représentée.
Insight : Concentration dans les pôles économiques majeurs.

#### Score Moyen Performance et Salaire Moyen par Département (Scatter)
Scatter plot croisant le score de performance et le salaire moyen par département.

Salaire moyen entre 11K et 13K MAD selon les départements.
Score de performance entre 7.0 et 7.4.
Insight : Pas de corrélation forte — certains départements bien payés n'ont pas forcément les meilleurs scores.

#### Somme des Jours_Absence par Département
Bar chart vertical montrant les absences cumulées.

Commercial : département avec le plus d'absences.
IT et RH : moins d'absences.
Insight : Le département Commercial mérite une attention particulière.

#### KPI — Taux Absentéisme

Taux global : 1.33% — niveau acceptable.


### Page 3 — Formation, Contrats & Heures Sup
#### Nombre Employés par Formation_Suivie
Donut chart sur la participation aux formations.

Non : 329 employés (54.83%)
Oui : 271 employés (45.17%)
Insight : Plus de la moitié des employés n'ont pas suivi de formation — axe d'amélioration important.

#### Nombre Employés par Département et Type_Contrat (Stacked Bar)
Bar chart empilé montrant la répartition CDI/CDD/Intérim dans chaque département.

CDI domine dans tous les départements.
Commercial et Logistique ont plus d'Intérim.
Insight : Bonne stabilité contractuelle globale, mais précarité dans certains départements.

#### Nombre Employés par Mois (Line Chart)
Courbe montrant les recrutements mois par mois.

Fluctuations entre 40 et 70 employés recrutés par mois.
Insight : Pas de saisonnalité forte — recrutement régulier tout au long de l'année.

#### Somme Heures_Sup par Département et Genre (Stacked Bar)
Bar chart comparant les heures supplémentaires par département et genre.

Direction et Logistique : plus d'heures sup.
RH et Finance : moins d'heures sup.
Répartition hommes/femmes visible par couleur.
Insight : Certains départements ont une charge de travail supplémentaire élevée.


 #### Technologies utilisées

Power BI Desktop
Microsoft Excel (source de données)
Dataset : 600 employés — contexte marocain


#### Comment utiliser

Cloner le repository :

bash   git clone https://github.com/Faridoumnay/Analyse de RH-DATA.git

Ouvrir Analyse_de_RH-DATA.pbix avec Power BI Desktop
Re-lier le dataset si nécessaire : Transform Data → Data Source Settings


#### Auteur

#### Farid Oumnay
