# Carnet casino

Mon carnet de figures de salsa cubaine (casino) et de rueda :

- **Carnet** : les figures par niveau (Bases, Intermédiaire, Avancé), avec pour chacune la durée, les positions de départ et d'arrivée, l'appel en rueda, le déroulé par blocs de 8 temps, mes points de vigilance, un lien vidéo et ma maîtrise (À revoir, En cours, Maîtrisée).
- **Réviser** : le cantante annonce des figures tirées au sort (celles à revoir reviennent plus souvent), au rythme d'une clave 2-3 ou 3-2, en lent (160), moyen (190) ou timba (210). « Je l'ai » fait monter la figure d'un cran, « Ratée » la remet à revoir.
- **Enchaîner** : composer une suite de figures, vérifier les raccords de position, la répéter en musique.

## Mettre en ligne avec GitHub Pages

1. Sur GitHub, créer un dépôt public, par exemple `carnet-casino`.
2. « Add file » → « Upload files » : déposer **le contenu** de ce dossier (`index.html`, `sw.js`, `manifest.webmanifest`, `icon-192.png`, `icon-512.png`, `README.md`), puis « Commit changes ».
3. « Settings » → « Pages » → Source : « Deploy from a branch », branche `main`, dossier `/ (root)` → « Save ».
4. Après une à deux minutes, l'appli est à l'adresse `https://VOTRE-NOM.github.io/carnet-casino/`.

## Installer sur le téléphone

- Android (Chrome) : ouvrir l'adresse, menu ⋮ → « Ajouter à l'écran d'accueil ».
- iPhone / iPad (Safari) : bouton Partager → « Sur l'écran d'accueil ».

L'appli fonctionne ensuite sans connexion.

## Le son et la voix

- La clave est produite par le téléphone lui-même : vérifier que le mode silencieux est coupé.
- La voix du cantante utilise la synthèse vocale espagnole du téléphone. Si aucune voix espagnole n'est installée, le téléphone lit avec sa voix par défaut : on peut en ajouter une dans les réglages de synthèse vocale (Android : Paramètres → Accessibilité → Synthèse vocale).
- L'écran reste allumé pendant la révision quand le navigateur le permet. Si l'écran s'éteint ou si l'on change d'appli, la révision s'arrête.

## Vos données

Tout est enregistré **sur l'appareil**, dans le navigateur, sans compte ni partage. Pour transférer le carnet ou le mettre à l'abri : roue crantée dans le Carnet → « Sauvegarder dans un fichier », puis « Restaurer une sauvegarde » sur l'autre appareil.

## Mettre à jour

Remplacer les fichiers dans le dépôt et changer le numéro dans `sw.js` (`carnet-casino-v1` → `carnet-casino-v2`) pour que les téléphones prennent la nouvelle version.
