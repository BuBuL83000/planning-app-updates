# planning-app-updates

Serveur de mises a jour automatiques de Planning App.

- `latest.json` : version publiee, notes, signature et lien de telechargement.
- `planning-app-<version>.msi.zip` : archive signee de cette version.

Les applications installees lisent `latest.json` au demarrage et telechargent l'archive indiquee.
Seule la version en cours doit etre presente ici.
