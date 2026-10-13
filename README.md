# Italiano 🇮🇹

Petit site personnel pour apprendre et réviser du vocabulaire italien.

## Utilisation
- Ouvre `index.html` dans un navigateur pour utiliser les cartes (pour charger `vocabulary.json`, utilise de préférence GitHub Pages ou un petit serveur local).
- Révise dans les deux sens : français → italien et italien → français.
- Ajoute des cartes locales, recherche dans le vocabulaire et exporte une sauvegarde JSON.
- Le vocabulaire partagé du dépôt est défini dans `vocabulary.json`.

## Ajouter des mots partagés
Ajoute une entrée dans `vocabulary.json` avec un identifiant unique, une traduction, un thème et un exemple facultatif :

```json
{
  "id": "v011",
  "fr": "Je ne sais pas",
  "it": "Non lo so",
  "cat": "Expressions",
  "ex": "Non lo so, devo controllare."
}
```

Les nouvelles cartes du fichier partagé apparaissent au prochain chargement du site. La progression et les cartes ajoutées depuis l'interface sont conservées localement dans le navigateur et ne sont pas envoyées automatiquement sur GitHub.
