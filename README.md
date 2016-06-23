# Reader

Module Reader utilisé pour [la démo d'une app hybride electron / cordova](https://github.com/lellex/demo-electron-cordova).

Ce module permet d'utiliser la fonction Text To Speech (synthèse vocale) sur n'importe quel environnement, en utilisant un service qui doit lui être passé en paramètre.

## Utilisation du module Reader

```
Reader.init({
  container: 'container',
  tts: ttsWebApi,
  text: 'Bonjour, bienvenue sur cette démonstration d\'une application Electron !'
});
```

Reader en options un objet contenant :

* **container** : l'id de l'élément HTML dans lequel nous voulons initialiser notre app
* **tts** : un service de TTS
* **text** : Le texte que nous voulons lire

## Services TTS

* [tts.webapi](https://github.com/lellex/tts.webapi) : un module spécifique pour utiliser le talk to speech dans un environnement web
* [tts.cordova](https://github.com/lellex/tts.cordova) : un module spécifique pour utiliser le talk to speech dans un environnement cordova
