# Développement Service Web

## Principe du cours

Découvrir les étapes pour créer un outils de gestion en PHP.
Création des maquettes, réalisation d'un cahier des charges, réalisation d'un diagramme de gantt.
Durée: du 15/01/2024  au 22/03/2024

## Compétence à obtenir

- Découvert de l'envrionnement Python et du framework FastAPI
- Connexion et utilisation d'une base de donnée (Mysql)
- Comprendre la notion de route
- Faire un CRUD au niveau de ces données

## Notation

Tout au long du projet, les notes seront mise au faire et a mesure de l'avancement et de l'implication des chacuns. Il y aura trois présentations:
1/ En semaine 4 où seront noté les maquettes, les schemats de base de données et le planning.
2/ En semaine 6 pour valider la partie authentification et accès au service (travail fait ensemble).
4/ En semaine 10 pour faire un point et valider les pistes de développement mise en place.
3/ En semaine 12 Tout devra être terminé.

## Le projet

Développement d'un outils de gestion d'intervention pour la société AccordEnergie.

La personnes devra se connecter pour avoir accès au service.

Il y a trois types de rôle qui peuvent utiliser l'application:
- Les standardistes
- Les intervenants
- Les clients
- Les admins

Les admins ont accès à tout et peuvent modifier les infos dans les listes (réalisation de CRUD)

Les clients voient l'état d'avancement de leurs interventions, et peuvent ajouter des infos sous forme de commentaire Ils ont bien sûr accès à leurs anciennes interventions

Les intervenants voient les interventions qui leur sont attribuer et peuvent modifier les status, et laisser des commentaires

Les standardistes peuvent créer, modifier, annuler et/ou cloturer des interventions, mais uniquement les leurs. Bien sûr ils ont aussi la possibilité d'ajouter des commentaires

Un intervention se passe chez un client et est effectué par un intervenant. Elle ont un status de suivit et un degrée d'urgence. On peut leur ajouter des commentaires afin de donnér plus d'information.