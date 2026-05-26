# Dronexperts — Formation Thermographie par Drone

Cours en ligne d'initiation à la thermographie par drone, format 2 jours présentiel (14h pédagogiques), destiné aux télépilotes certifiés (RS6982 ou équivalent) novices en thermographie.

Matériel cible : **DJI Mavic 3T** et **DJI Matrice 4T**.

## Langue française : accents obligatoires

Tous les documents produits (HTML, PPTX, PDF, Markdown) doivent respecter l'orthographe française avec les accents corrects. Ne jamais produire de texte sans accents.

### Accents courants à vérifier systématiquement

| Incorrect | Correct |
|-----------|---------|
| thermographie | thermographie (déjà correct, accent inutile) |
| emissivite | émissivité |
| reflexion | réflexion |
| theorique | théorique |
| methodologie | méthodologie |
| reglementation | réglementation |
| materiel | matériel |
| pedagogique | pédagogique |
| referentiel | référentiel |
| emargement | émargement |
| controle | contrôle |
| meteo | météo |
| operationnel | opérationnel |
| electrique | électrique |
| a la / a l' | à la / à l' |
| tres | très |
| pret | prêt |
| degagement | dégagement |
| degats | dégâts |
| degradation | dégradation |
| renovation | rénovation |
| evaluation | évaluation |
| preparation | préparation |
| categorie | catégorie |
| specifique | spécifique |

### Règle de vérification

Après chaque génération de contenu en français, effectuer un contrôle visuel des accents manquants sur les mots du tableau ci-dessus.

## Charte graphique

Se référer à la charte Dronexperts v2.3 (commune à tous les cours en ligne) :
- Police : **Inter** (Google Fonts) exclusivement
- Couleur primaire : **#0E74DA**
- Dégradé logo : **#1E3A8A → #04355D**
- Texte principal : **#0F172A**
- Texte secondaire : **#475569**
- Réussite : **#10B981** · Alerte : **#F59E0B** · Erreur : **#EF4444**

## Structure des fichiers

```
template/
  index.html                       ← Démo des 11 types de slides Reveal.js (thèmes thermo)
  index-formation.html             ← Sommaire formation 2 jours
  livret-instructeur.html          ← Livret d'accueil instructeur (imprimable)
  formation-jour1-matin.html       ← J1 AM : Fondamentaux IR & thermique bâtiment
  formation-jour1-aprem.html       ← J1 PM : Matériel DJI & préparation mission
  formation-jour2-matin.html       ← J2 AM : Méthodologie & cas d'usage
  formation-jour2-aprem.html       ← J2 PM : Post-traitement, normes, rapport, exercices
  formation-qcm-j1.html            ← QCM Jour 1 (interactif)
  formation-qcm-j2.html            ← QCM Jour 2 (interactif)
  css/dronexperts-theme.css        ← Thème CSS partagé (charte v2.3)
  assets/img/                      ← Logos SVG/PNG + visuels
```

## Sources pédagogiques (non versionnées)

Le dossier `_sources_extraction/` à la racine du projet contient les extractions texte des PPTX du cours historique 4 jours :
- `jour1.txt` — Module A « Initiation/Tour d'horizon » (109 slides)
- `jour2.txt` — Module B « Métier de thermicien » (138 slides)
- `jour3_jour4_exercice.txt` — Module C (mission), Module D (post-traitement) et 16 exercices d'interprétation

Le cours 2 jours en présentiel est une **condensation pédagogique** de ces 315 slides en ~130 slides répartis sur 4 demi-journées + 2 QCM.

## Conventions pédagogiques

- **Réglementation pilotage** : rappel court uniquement (3-4 slides), le public est censé déjà certifié télépilote
- **Matériel** : Mavic 3T et Matrice 4T traités à parité dans les comparatifs ; pas de promotion d'autres marques
- **Logiciel principal** : DJI Thermal Analysis Tool ; FLIR Tools / Studio Thermal mentionnés brièvement en alternative
- **Normes** : citer NF EN 13187, APSAD D19, NF A09-400 — extraits courts uniquement (droits)
- **Cœurs pédagogiques à conserver intégralement** : les 12 pièges d'interprétation, les fondamentaux physique (lois Stefan-Boltzmann/Wien/Planck), la méthodologie de relevé (5 règles), les 19 points du rapport NF EN 13187
