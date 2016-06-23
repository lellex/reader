# Reader

Module Reader utilisé pour [la démo d'une app hybride electron / cordova](https://github.com/lellex/demo-electron-cordova).

Ce module permet d'utiliser la fonction Text To Speech (synthèse vocale) sur n'importe quel environnement, en utilisant un service qui doit lui être passé en paramètre.

## Utilisation du module Reader

```
Reader.init({
  container: 'container',  // Id de l'élément DOM où sera insérer notre app
  tts: ttsWebApi,          // Service TTS
  text: 'Bonjour, bienvenue sur cette démonstration d\'une application Electron !'  // Texte à lire
});
```
