# Installation rapide

On a écrit un script qui installe Geth et créé un compte, tout d'un seul coup.

C'est le script [`auto_install.sh`](https://github.com/baptistecolin/minecoin/blob/master/scripts/auto_install.sh) du dossier `scripts/`.

### Utilisation

Dans le Terminal, tapez :

```bash
$ cd scripts/
$ sudo ./auto_install.sh <password> <fichier minecoin_genesis.json>
```

  * A la place de `<password>`, entrez le mot de passe que vous désirez avoir pour votre compte MineCoin.
  * A la place de `<fichier minecoin_genesis.json>`, entrez l'emplacement du fichier `minecoin_genesis.json`. Si vous ne savez pas quoi mettre, essayer `../data/minecoin_genesis.json`.

Des opérations vont s'effectuer. Des confirmations vous seront demandées, tapez alors `y` (yes) ou `o` (oui) selon la langue de votre PC. L'installation et la création du compte devraient prendre 2 minutes environ.

### Annexes

Vous pouvez lire la procédure d'installation "en détail" sur [`/docs/install.md`](https://github.com/baptistecolin/minecoin/blob/master/docs/install.md). Elle vous fait faire manuellement les mêmes opérations que l'installation automatisée.

## HELP

Si t'y comprends rien tu peux m'appeler au secours : [`baptiste.colin@mines-paristech.fr`](mailto:baptiste.colin@mines-paristech.fr)