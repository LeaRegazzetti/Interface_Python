Il s’agit dans ce projet de réaliser une interface graphique permettant d’appliquer des algorithmes de prédiction sur un jeu de données.
Les utilisateurs de votre outil sont supposés ne rien connaître en programmation python. Le cahier des charges est le suivant :

1. L’outil prendra en entr ée un jeu de données annoté au format csv (avec une virgule pour séparateur). Le jeu de données comportera des noms de colonnes à la première ligne.

2. L’application permettra à l’utilisateur de définir les variables prédictives, et la variable cible.

3. En fonction du type de la variable cible (catégorielle ou numérique), l’application proposera au moins 3 algorithmes de classification, ou 3 algorithmes de régression que l’utilisateur peut appliquer.

4. L’utilisateur pourra choisir un ou plusieurs de ces algorithmes à appliquer aux données. Pour chaque algorithme à appliquer, les valeurs optimale des principaux hyper-paramètres pourront être soit définies par l’utilisateur, soit identifiées automatiquement.

5. Pour chacun des modèles à appliquer, on utilisera une validation croisée et on fournira en sortie les métriques d’évaluation, le temps de calcul, et surtout une/des figure(s) permettant de percevoir de façon synthétique la différence entre les prédictions et la réalité.

6. Vous devrez utiliser l’une des deux biblothèques ≪ Dash ≫ ou ≪ Bokeh ≫ pour la conception de l’interface graphique et y intégrer les visualisations à l’aide de ≪ Plotly ≫ (pour les rendre interactives).
