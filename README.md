# EDEN
Experimental Development Environment for Newbies, ou Environnement de Développement Éxpérimental pour Newbies, est un petit ensemble d'outils destiné à simplifier la gestion de développement expérimental, notamment pour le suivi, la sauvegarde et l'accès aux résultats.

Il a pour but d'être utilisé en complémentarité avec git, notamment pour gérer l'exploration de plusieurs directions en simultanée, et la possibilité de tester très rapidement, en sauvegardant les résultats, des configurations non finalisées qui n'ont pas vocation à êtrer gittées.

## TODO : 
- Voir dans le fichier expator.sh
- Spécifier la nomenclature : expérimentation, run, ... 
- Ma proposition : ou initialise un projet et crée des freeze (freeze Statement) 
- Spécifier dans un README l'architecture décidée en brainstorming. (pour un projet, on a quels dossiers. Où est-ce qu'on met les freeze/run etc ...)

## Fonctionnalités

- Lancement d'une expérimentation, dans un dossier dédié, avec une copie des scripts utilisés
- Interface avec git : une branche par expérimentation
- Annotation d'expérimentation : Invalide (error), Dépassée, Valide, avec commentaires et descriptions
- Recherche simplifiée
- Archivage

## expator sh 

```
expator.sh [nom de l'experience en camelCase] 

# exemple 
expator.sh monExperience
```

