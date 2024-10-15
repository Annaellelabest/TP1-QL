# TP 1 : Test unitaire avec Eclipse

## Exercice 1 : Préparation

## Exercice 2 : Création d’un TU vide
Observer le code généré par Eclipse dans la classe PersonTest.
Tracer vos remarques sur la structure de code : héritage, etc.

Mes classes utilsent des annotations particulières: @org.junit.jupiter.api.Test car j'utilise JUnit 5. 
De plus mes tests sont indépendants et peuvent être exécutés dans n'importe quel ordre. 
Pour l'héritage, il n'y a pas d'héritage dans mes classes de test car j'utilise JUnit 5.


## Exercice 3 : Exécution de TU
Expliquer les résultats obtenus dans la vue JUnit.

La vue JUnit, afficher une liste des tests avec un indicateur de réussite ou d'échec.
Mes tests sont vides pourtant ils sont considérés comme réussis, car aucune condition de test n'a échoué.


## Exercice 4 : Ecriture d’un TU
Exécuter le test et interpréter le résultat obtenu. Continuer avec les autres méthodes.

J'ai eu quelques erreurs de compilation, que j'ai pu visualiser dans ma fenêtre et j'ai donc pu corriger mes erreurs.
Les tests sont réussis car les conditions de test sont respectées.
Nos tests sont bien validée:
- Pour les setters on verifie que l'on peut modifier la valeur de name et years.
- Pour les getters on verifie que l'on peut récupérer la valeur de name et years définis par défaut : "unknown" et 22.

 