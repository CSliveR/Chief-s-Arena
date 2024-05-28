Planification de l'organisation d'un colloque scientifique
## 1. Identification des tâches et de leurs successeurs
Comité d'organisation (Logistique)

Constitution du comité d'organisation (1 semaine)

Successeur : Sélection de l'hôtel
Sélection de l'hôtel (3 semaines)

Successeur : Choix des menus et des repas, Fixation de la première réunion du comité de programme
Choix des menus et des repas (1 semaine)

Successeur : Détermination du prix payé par les conférenciers
Choix du lieu de banquet (2 semaines)

Successeur : Fixation de la deuxième réunion du comité de programme, Détermination du prix payé par les conférenciers
Détermination du prix payé par les conférenciers (0 semaine, dépend des tâches précédentes)

Successeur : Appel à communications
Appel à communications (8 semaines)

Successeur : Réception des contributions
Réception des contributions (8 semaines)

Successeur : Sélection des articles
Sélection des articles (8 semaines)

Successeur : Fixation de la deuxième réunion du comité de programme
Homogénéisation des articles (4 semaines)

Successeur : Impression des Proceedings
Impression des Proceedings (6 semaines)

Successeur : Réception des Proceedings
Réception des Proceedings (0 semaine, dépend de l'impression)

Successeur : Début du colloque
Comité de programme (Scientifique)

Constitution du comité de programme (3 semaines)

Successeur : Première réunion du comité de programme
Première réunion du comité de programme (0 semaine)

Successeur : Appel à communications
Deuxième réunion du comité de programme (0 semaine)

Successeur : Fixation du programme final


## 2. Graphe équivalent au tableau des tâches
Voici une représentation des tâches sous forme de graphe :

graph TD
  A1[Constitution du comité d'organisation] --> B1[Sélection de l'hôtel]
  B1 --> C1[Choix des menus et des repas]
  B1 --> D1[Fixation de la première réunion du comité de programme]
  C1 --> E1[Détermination du prix payé par les conférenciers]
  D1 --> A2[Constitution du comité de programme]

  A2 --> B2[Première réunion du comité de programme]
  E1 --> B2
  B2 --> F1[Appel à communications]
  B1 --> G1[Choix du lieu de banquet]
  G1 --> H1[Fixation de la deuxième réunion du comité de programme]
  H1 --> I1[Sélection des articles]
  F1 --> I1
  I1 --> J1[Homogénéisation des articles]
  J1 --> K1[Impression des Proceedings]
  K1 --> L1[Réception des Proceedings]
  L1 --> M1[Début du colloque]




## 3. Date de début de l'organisation
Pour calculer la date de début, nous devons déterminer la durée totale du projet et soustraire cette durée à la date de début du colloque.

La tâche la plus longue est la sélection des articles et les contributions, soit 8 + 8 = 16 semaines.

Le chemin critique le plus long (celui déterminant la durée totale du projet) inclut :

Constitution du comité d'organisation : 1 semaine
Sélection de l'hôtel : 3 semaines
Première réunion du comité de programme : 0 semaine (après 3 semaines)
Appel à communications : 8 semaines (après 4 semaines)
Réception des contributions : 8 semaines (après 12 semaines)
Sélection des articles : 8 semaines (après 20 semaines)
Homogénéisation des articles : 4 semaines (après 28 semaines)
Impression des Proceedings : 6 semaines (après 32 semaines)
Réception des Proceedings : 1 semaine avant le colloque
Total: 33 semaines.

Pour un début du colloque le 10 mars 2025, nous devons reculer de 33 semaines.

Calcul de la date de début :

10 mars 2025 - 33 semaines ≈ 16 juillet 2024.
La date de début de l'organisation doit être le 16 juillet 2024 au plus tard.




## 4. Marges pour les réunions du comité de programme
Pour fixer une date sans que cela ne rallonge la préparation, nous devons considérer les marges disponibles.

Première réunion du comité de programme : Cette réunion doit avoir lieu après la sélection de l'hôtel (3 semaines) et après la constitution du comité de programme (3 semaines), soit après 3 semaines. Cette réunion est critique car elle déclenche l'appel à communications (8 semaines). La marge est nulle car elle est sur le chemin critique.

Deuxième réunion du comité de programme : Doit avoir lieu après la sélection des articles (8 semaines) et le choix du banquet (2 semaines), et au moins 3 semaines avant le colloque.

Elle doit donc avoir lieu après 26 semaines et avant la semaine 29.
Si la sélection des articles est faite à la semaine 20, nous avons une marge de 3 semaines pour fixer la date de la deuxième réunion.
La marge pour fixer la date de la deuxième réunion du comité de programme est de 3 semaines.

Ainsi, il faut bien coordonner les dates de réunion en tenant compte des marges disponibles pour éviter de retarder la préparation du colloque.
