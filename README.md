web-kiosk
=========

Page d'accueil pour présenter quelque sites web dans les intêrets de l'association, accessible [ici](http://linux-sur-yvette.github.io/web-kiosk/).

Pour mettre à jour la version web à partir de la branche master il faut faire :

```shell
git checkout gh-pages
git rebase master
git push origin gh-pages
git checkout master
```