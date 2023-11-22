# TP de modélisation de problèmes d'optimisation combinatoire avec julia et JuMP

Ce dépôt contient les supports de TP pour le module d'OC de l'institut Galilée (2ème année).

Contributeurs :

* Roland Grappe
* Mathieu Lacroix

Pour faire les TP, le plus simple est d'utiliser le [jupyterhub de l'institut Galilée](https://si-galilee.univ-paris13.fr/jupyter/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FmathieuLacroix%2FG4SIOC&urlpath=lab%2Ftree%2FG4SIOC%2F&branch=master).

Il est aussi possible d'utiliser le jupyter en local. Pour cela, il faut suivre les instructions données ci-dessous.

Pour cloner le dépôt la première fois : 
```bash
git clone https://github.com/mathieuLacroix/G4SIOC.git
```

Pour lancer les notebooks julia :

1. Ouvrir un terminal et exécuter les commandes suivantes :
   ```bash
   cd G4SIOC
   julia
   ```
2. Exécuter le code julia suivant :
   ```julia
   using IJulia
   notebook()
   ```



Pour obtenir les nouveaux tps, taper dans le répertoire G4SIOC :

```bash
./updateDepot
```

Cette mise-à-jour automatique se fait via le script `pull.py` provenant du projet [nbgitpuller](https://github.com/jupyterhub/nbgitpuller/).
