# Développement Web PHP

## Principe du cours

Découvrir les étapes pour créer un outils de gestion en PHP.
Création des maquettes, réalisation d'un schema de base de données (MCD), réalisation d'un diagramme de gantt.
Durée: du 15/01/2024  au 22/03/2024

## Compétence à obtenir

- Découvert de l'envrionnement PHP
- Connexion et utilisation d'une base de donnée (Mysql)
- Faire un CRUD au niveau de ces données

## Notation

Tout au long du projet, les notes seront mise au faire et a mesure de l'avancement et de l'implication des chacuns. Il y aura trois présentations:

1/ En semaine 4 où seront noté les maquettes, les schemats de base de données et le planning.

2/ En semaine 6 pour valider la partie authentification et accès au service (travail fait ensemble).

3/ En semaine 10 pour faire un point et valider les pistes de développement mise en place.

4/ En semaine 12 Tout devra être terminé.

## Le projet

Développement d'un outils de gestion d'intervention pour la société AccordEnergie (Fictive).

La personne devra se connecter pour avoir accès au service.

Il y a quatre types de rôle qui peuvent utiliser l'application:
- Les standardistes
- Les intervenants
- Les clients
- Les admins

Les admins ont accès à tout et peuvent modifier les infos dans les listes (réalisation de CRUD)

Tout le monde peux créer un compte qui est de type client par défaut. Les admins peuvent changer le type de compte d'un utilisateur.

Les clients voient l'état d'avancement de leurs interventions, et peuvent ajouter des infos sous forme de commentaire. Ils ont bien sûr accès à leurs anciennes interventions

Les intervenants voient les interventions qui leur sont attribuer et peuvent modifier les status, et laisser des commentaires.

Les standardistes peuvent créer, modifier, annuler et/ou cloturer des interventions, mais uniquement les leurs. Bien sûr ils ont aussi la possibilité d'ajouter des commentaires. Par contre ils peuvent voir toute les interventions et tous les clients.

Un intervention se passe chez un client et est effectué par un ou plusieurs intervenants à une date donnée. Elle ont un status de suivit et un degré d'urgence. On peut leur ajouter des commentaires afin de donnér plus d'informations.

Les admins peuvent modifier la liste des degré d'urgence et les status de suivit des interventions.

On doit pouvoir order les tableaux en fonction de la case sur laquelle on clique (Par exemple si on clique sur les noms, la liste s'affiche ordonnée de A à Z et si on reclique dessus elle s'ordonne de Z à A)
