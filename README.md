# Le Bureau de Hugo — guide des cas d'usage Claude

Prototype HTML autonome destiné à expliquer les usages possibles de Claude et Claude Code à un responsable opérationnel d'un groupe de restaurants et de bars.

## Ouvrir le prototype

Double-cliquer sur `index.html`, ou lancer un serveur statique depuis la racine du dépôt :

```bash
python3 -m http.server 4173 --directory prototype-use-cases
```

Puis ouvrir `http://localhost:4173`.

## Contenu

- 22 actions opérationnelles réparties par catégorie ;
- 6 idées de micro-outils réalisables avec Claude Code autour d’Excel, Google Sheets et Drive ;
- un circuit simple de remontée terrain via formulaire, Sheet partagé et digest Gmail ;
- recherche conversationnelle locale par mots-clés ;
- filtre de mise en place rapide ;
- méthode, prompt de départ et point de vigilance pour chaque cas ;
- questionnaire de qualification avec recommandations et message Gmail prérempli ;
- interface responsive et utilisable au clavier ;
- aucune API métier, aucun traitement réel de fichiers et aucune donnée opérationnelle réelle.

La zone conversationnelle est volontairement simulée dans le navigateur. Elle oriente vers les fiches sans envoyer de contenu à un service externe. Les micro-outils sont présentés comme des projets à construire : le guide ne prétend pas les exécuter lui-même.
