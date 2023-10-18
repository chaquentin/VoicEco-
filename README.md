# VoiceEcoPlus

Le projet VoiceEcoPlus est un projet visant à développer une retranscription écrite de la voix d'un utilisateur, généralement un animateur radio. Il permettra de calculer la part d'information à caractère écologique dans les propos de cet utilisateur.

## Installation

Pour installer le projet, vous devez cloner le projet sur votre machine

```bash
git clone https://github.com/chaquentin/VoicEcoPlus.git
```

Assurez-vous d'avoir correctement installé les librairies suivantes :
 - vosk
 - sounddevice

```bash
pip install vosk sounddevice
```

Si jamais vous avez des problèmes lors du lancement de vosk, il faut installer libportaudio2

 - Ubuntu :
```bash
sudo apt-get install libportaudio2
```

 - Fedora :
```bash
sudo dnf install libportaudio

## Utilisation

Pour lancer le projet, il suffit d'exécuter le fichier hackathon.py avec comme argument fr pour avoir la transcription en français.

```bash
python hackathon.py -m fr
```