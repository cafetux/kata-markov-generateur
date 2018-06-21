# kata-markov-generateur
Les repertoires contiennent des ressources textes pour alimenter une chaine de markov.


# But du kata

Créer un générateur de paroles de chanson punk-rock (par exemple) via une chaîne de Markov, en s'appuyant sur la technique du TDD.

# Chaine de Markov

Un processus de Markov est un processus stochastique possédant la propriété de Markov : l'information utile pour la prédiction du futur est entièrement contenue dans l'état présent du processus et n'est pas dépendante des états antérieurs (le système n'a pas de « mémoire »).

# Oui, mais concrétement ?

L'idée est de créer un arbre à partir de textes existants, permettant de connaitre les probabilités qu'un mot suive un autre.
Une fois l'arbre créé, il suffira de le parcourir au hasard pour générer des phrases. 
Un processus de validation à postériori permettra de trier les phrases utiles ou non.




