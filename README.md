Différence entre merge et rebase dans quel cas les utiliser

warning: push.default n'est pas défini ; sa valeur implicite change dans Git 2.0
de 'matching' vers 'simple'. Pour supprimer ce message et maintenir
le comportement actuel après la modification de la valeur de défaut, utilisez :

  git config --global push.default matching

Pour supprimer ce message et adopter le nouveau comportement maintenant, utilisez :

  git config --global push.default simple

Quand push.default vaudra 'matching', git poussera les branches locales
sur les branches distantes qui existent déjà avec le même nom.

Dans Git 2.0 Git utilisera par défaut le comportement plus conservatif 'simple'
qui ne pousse la branche courante vers la branche distante que 'git pull' utilise
pour mettre à jour la branche courante.
 
Voir 'git help config' et chercher 'push.default' pour plus d'information.
(le mode 'simple' a été introduit dans Git 1.7.11. Utilisez le mode similaire
'current' au lieu de 'simple' si vous utilisez de temps en temps d'anciennes versions de Git)

