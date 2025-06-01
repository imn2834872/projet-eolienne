# Projet : Impact des éoliennes sur les prix de l'immobilier

## Description
Ce dépôt contient le code R, les données (légères) et le rapport PDF associés à un projet d'économétrie mené dans le cadre du parcours CMI L3 D3S (Université Paris Nanterre).

L’objectif est d’analyser l’impact de la présence d’éoliennes sur les prix de l’immobilier en France à l’aide de techniques économétriques (statistiques descriptives, régressions linéaires, etc.).

---

## Contenu du dépôt

| Fichier | Description |
|--------|-------------|
| `ProjetFinal_Econometrie.Rmd` | Code source RMarkdown contenant tout le projet |
| `Projet_Final_Econometrie_et_SIG.pdf` | Rapport final généré à partir du `.Rmd` |
| `parc_national_20241221.csv` | Base de données sur les parcs éoliens en France |
| `aerogenerateur_national_20241221.csv` | Données caractéristiques sur les éoliennes |
| *(non inclus)* `maison_geo.csv` | Base immobilière complète sur trop lourde pour GitHub (voir ci-dessous) |

---

## Fichier manquant

> Le fichier `maison_geo.csv` n’est **pas inclus** dans ce dépôt, car sa taille dépasse les limites autorisées par GitHub.

**Taille estimée :** > 100 Mo  
**Accès :** sur demande (me contacter)  
**Emplacement attendu :** même dossier que le `.Rmd`

---

## Reproduire l’analyse

1. Cloner ce dépôt :
   ```bash
   git clone https://github.com/ImeneZebiri/projet-eolienne.git
