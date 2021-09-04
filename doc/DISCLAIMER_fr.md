### Configuration

Il y a peu de configuration dans Wetty :
* La configuration de démarrage (port d'écoute, chemin d'URL, hôte SSH) est contenue dans le fichier de service systemd
* La configuration de l'interface utilisateur se fait via l'interface graphique Web elle-même.

* L'authentification LDAP et HTTP est-elle prise en charge ? **Non**
  * Vous devez vous connecter manuellement.
  * Vous pouvez spécifier l'utilisateur en accédent directement `https://<host>/wetty/ssh/<username>`

* Vous pouvez spécifier à l'installation si Wetty devrait être accessible par des visiteurs non connectés sur YunoHost.

* Vous ne pouvez pas vous authentifier par une clé SSH.
